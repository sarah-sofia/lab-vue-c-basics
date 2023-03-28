<script>
import navbar from './components/navbar.vue';
import afooter from './components/afooter.vue';
import iteration2 from './components/iteration2.vue';
import iteration3 from './components/iteration3.vue';
import iteration4 from './components/iteration4.vue';

export default {
  name: 'App',
  components: {
    navbar,
    afooter,
    iteration2,
    iteration3,
    iteration4,
  }
}

</script>

<template>
  <div>
    <navbar />
    <h1>Hello World!</h1>
    <iteration2 />
    <iteration3 />
    <iteration4 />
    <afooter />
  </div>
</template>

<style scoped>

</style>
