<template>
    <div class="about">
      <h1></h1>
      <RouterLink to="/Blog/Server-subscriptions-updates-media-channels-tier-templates-and-more.vue">Server-subscriptions
        <img src="../assets/Diskoła8.png">
      </RouterLink>
      <router-view/>
    </div>
  </template>
  
  
  <script>
  import { RouterLink, RouterView } from 'vue-router'
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
      // tylko dla vue3
      console.log(props.options)
    },
    methods: {
      firstFunction(params) {
        console.log(params)
        console.log(this.options)
        return params
      }
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
