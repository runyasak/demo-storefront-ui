<template>
  <SfImage
    src="/assets/storybook/SfImage/product-216x326.jpg"
    :srcsets="[
      {
        src: '/assets/storybook/SfImage/product-109x164.webp',
        width: 109,
        breakpoint: 480,
      },
      {
        src: '/assets/storybook/SfImage/product-216x326.jpg',
        width: 1200,
        breakpoint: 1200,
      },
      {
        src: '/assets/storybook/SfImage/product-109x164.webp',
        width: '400px',
        breakpoint: 768,
      },
    ]"
    alt="Vila stripe maxi shirt dress"
    :width="null"
    :height="null"
  />
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import { SfImage } from '@storefront-ui/vue';
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    SfImage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
