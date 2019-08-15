<template>
  <div>
    <navbar></navbar>
  </div>
</template>

<script>
import navbar from './components/navbar'
export default {
  data() {
    return {
      message: 'Hello world',
    };
  },
  components:{
    navbar: navbar
  }
};
</script>

<style scoped>
</style>    