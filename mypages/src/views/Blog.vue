<template>
  <div class="about">
    {{ $route.path == "/Blog/server-subscriptions-updates-media-channels-tier-templates-and-more" }}
    <div
      v-if="showContentBlog"
    >
      <h1>Blog</h1>
      <br />
      <RouterLink to="/Blog/server-subscriptions-updates-media-channels-tier-templates-and-more">
        <img src="../assets/Motor.png" />
      </RouterLink>
    </div>
    <button @click="change()">
      Zmień 
    </button>
    <router-view />
  </div>
</template>

<script>
import { RouterLink, RouterView, useRoute } from 'vue-router'
import { ref, defineComponent } from 'vue'
export default defineComponent({
  name: 'Blog',
  components: {},
  props: {
    options: {
      type: Array
    },
    'show-labels': {
      type: Boolean
    }
  },
  // data() { } dla vue 2, można tez stosowac we vue3
  setup(props) {
    const route = useRoute();
    // tylko dla vue3
    console.log(props.options)
    const showContentBlog = ref(route.path != "/Blog/server-subscriptions-updates-media-channels-tier-templates-and-more")

    function change() {
      showContentBlog.value = !showContentBlog.value
    }
    return {
      showContentBlog,
      change
    }
  },
  methods: {
    firstFunction(params) {
      console.log(params)
      console.log(this.options)
      return params
    }
    // change() {
    //   this.showContentBlog = !this.showContentBlog
    // }
  }
})
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
