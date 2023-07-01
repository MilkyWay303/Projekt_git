<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    

    <div class="wrapper">
      <!-- <HelloWorld msg="You did it!" /> -->

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/Pobierz">Pobierz</RouterLink>
        <RouterLink to="/Nitro">Nitro</RouterLink>
        <RouterLink to="/Odkryj">Odkryj</RouterLink>
        <RouterLink to="/Bezpieczeństwo">Bezpieczeństwo</RouterLink>
        <RouterLink to="/Wsparcie">Wsparcie</RouterLink>
        <RouterLink to="/Blog">Blog</RouterLink>
        <RouterLink to="/Kariera">Kariera</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<!-- <style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style> -->
<style>
        * {
            margin: 0;
        }

        a {
            display: block;
        }

        .container1{
          width: 100%;
          margin: 0 auto;
          /* w pionie w poziomie*/
          text-align: center;
          padding: 150px 100px;
        }

        .container{
            width: 1000px;
            margin: 0 auto;
            /* w pionie w poziomie*/
            text-align: center;
            padding: 150px 0px;
        }

        .section {
            background-color: rgb(64, 78, 237);
            height: 69.25vh;
            /* 80% Twojego rzeczywistego ekranu*/
            position: relative;

        }





        .button1:hover {
            box-shadow: 10px 5px 5px black;
        }

        .button2:hover {
            box-shadow: 10px 5px 5px white;
        }

        .Napis1 {

            font-size: 70px;
            color: white;
        }

        .Napis2 {
            color: white;
            font-size: 20px;
            margin: 0 100px;
        }

        .Przyciski {
            display: flex;
            justify-content: space-around;
            margin: 0 550px;
            margin-top: -100px;
        }

        .obrazki1 {
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        .obrazki2 {
            z-index: 2;
            display: flex;
            justify-content: space-between;
            max-width: 100%;
        }

        .wyobraz{
            color:#5058b0;
            font-family: 'Sigmar', cursive;
        }
         
        .wyobras{
            color:white ;
            font-family: 'Sigmar', cursive;
        }

        .BlueHeather{
            color:#5058b0;
        }

        .blueBorder{
            border-color:#5058b0;
        }

        .multiselect1 .multiselect .multiselect__tags,
        .multiselect1 .multiselect .multiselect__single {
          background: transparent;
          border-width: 0px;
        }
        .multiselect1 .multiselect multiselect__content-wrapper {
        border-radius: 5px;
        }
        .multiselect1{
          width: 200px;
        }

        /* .mediaContainer */

        @media screen and (max-width: 800px) {
          .mediaContainer .tag {
            flex-direction: column!important;
          }
          .ObrMed {
            width: 300px;
          }
          
       }
       
       @media screen and (max-width: 999px) {
          .ObrMed {
            width: 350px;
          }
          .Yes {
            font-size: 40px;
          }
          .mediaContainer .tag {
            flex-direction: column!important;
          }
          .GuzikMed1 {
            font-size: 12px;
          }
          .ButMed2 {
            font-size: 12px;
          }
          
       }
        
        @media screen and (min-width: 1000px) {
          .mediaContainer .tag {
            flex-direction: row!important;
          }
          .mediaContainer .tag img{
            max-width: 500px;
          }
          .mediaContainer .tag h2{
            font-size: 30px;
          }
          .ObrMed {
            width: 350px;
          }
          .NapisMed3 {
            font-size: 50px;
          }
          .GuzikMed1 {
            font-size: 15px;
          }
          .buttonWindows {
            font-size: 25px;
          }
        }
        @media screen and (min-width: 1500px) {
          .mediaContainer .tag h2{
            font-size: 60px;
          }
          .mediaContainer .tag img{
            max-width: 1000px;
          }
          .buttonWindows {
            font-size: 15px;
          }
          .NapisMed3 {
            font-size: 60px;
          }
        }
        @media screen and (min-width: 1562px) {
          .buttonWindows {
            font-size: 0.75rem;
          }
          .NapisMed3 {
            font-size: 65px;
          }
          .buttonWindows {
            font-size: 19px;
          }
        }
        @media screen and (min-width: 1700px) {
          .ObrMed {
            width: 500px;
            height: 500px;
          }
          .NapisMed3 {
            font-size: 75px;
          }
       }
       @media screen and (min-width: 2000px) {
          .ObrMed {
            width: 600px;
            height: 600px;
          }
          .NapisMed3 {
            font-size: 75px;
          }
       }

       @media screen and (min-width: 2400px) {
          .ObrMed {
            width: 800px;
            height: 800px;
          }
          .NapisMed1 {
            font-size: 45px;
          }
          .NapisMed2 {
            font-size: 35px;
          }
          .buttonWindows {
            font-size: 30px;
          }
          .NapisMed3 {
            font-size: 100px;
          }
          .ButMed1 {
            font-size: 40px;
          }
          .GuzikMed1 {
            font-size: 30px;
          }
          .ButMed2 {
            font-size: 20px;
          }
       }
    </style>
