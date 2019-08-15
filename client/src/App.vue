<template>

  <signin>  </signin>
  <uploadForm></uploadForm>
  
</template>

<script>

import signin from './components/signin'

import uploadForm from './components/uploadForm'
export default {
  data() {
    return {
      message: "Hello world"
    };
  },

  components: {
    signin,
    uploadForm
  },
  methods:{
  }
};
</script>

<style scoped>
</style>    