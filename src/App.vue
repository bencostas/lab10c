<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <HelloWorld msg="Ben Costas CPS530"/>
  <HelloWorld msg="Lab10c deploying on Netlify using Vite and Vue" />
  <div>
    <a href="https://vite.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <p>1. First I used npm to create a new Vue template using Vite </p>
  <p>2. I initialized a local git repository and published it to my github profile</p>
  <p>3. I created an account on Netlify, which is used to deploy web pages and github repositories</p>
  <p>4. Using Netlify, I linked my Vue github repo to Netlify and set the deployment to the master branch</p>
  <p>5. I clicked deploy, and after a few seconds my site was live!!</p>
  <p>The major difficulties I encountered was getting familiar with the component architecture of Vue, as I normally use React as my frontend framework, so learning how components are imported took some time but overall it was an easy process</p>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
