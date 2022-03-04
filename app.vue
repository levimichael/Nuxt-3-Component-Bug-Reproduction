<template>
  <div>
    <component :is="item" v-for="item in componentList" :key="item" />
  </div>
</template>

<script setup>
import Hero from './components/contentSection/Hero';
const componentList = ['Hero'];
</script>

<!--
<script>
import Hero from './components/contentSection/Hero';
export default {
  components: { Hero },
  data() {
    return {
      componentList: ['Hero'],
    };
  },
};
</script>
-->
