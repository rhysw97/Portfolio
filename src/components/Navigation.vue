<template>
  <nav class="desktop-nav">
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/projects">Projects</router-link></li>
      <li><router-link to="/contact">Contact Me</router-link></li>
    </ul>
  </nav>
</template>

<script lang="ts">


export default class TopNav extends Vue {}
</script>

<style lang="scss">
nav {
  padding: 20px 0;
  ul {
    display: flex;
    list-style: none;
    justify-content: space-evenly;
  }
  a {
    color: white;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
}
</style>