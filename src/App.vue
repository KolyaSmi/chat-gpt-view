<template>
  <HeaderBlock />
  <router-view />
  <FooterBlock />
</template>

<script>
import HeaderBlock from './components/HeaderBlock.vue';
import FooterBlock from './components/FooterBlock.vue';

export default {
  components: {
    HeaderBlock,
    FooterBlock
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #040c18;
  // text-align: center;
  // color: #2c3e50;
}

* {
  color: white;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  min-height: 100vh;
}

.singIn {
  background: none;
  border: none;
  padding: 0 20px;
}

.container {
  max-width: 1170px;
  width: 100%;
  padding: 0 20px;
  margin: 0 auto;
}

a {
  text-decoration: none;
}

p {
  color: #81AFDD;
}

ul {
  list-style: none;
}
</style>
 