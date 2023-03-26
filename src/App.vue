<script>
import navbar from './components/navbar.vue';
import afooter from './components/afooter.vue';

export default {
  name: 'App',
  components: {
    navbar,
    afooter,
  }
}

</script>

<template>
  <div>
    <navbar />
    <h1>Hello World!</h1>
    <afooter />
  </div>
</template>

<style scoped>

</style>
