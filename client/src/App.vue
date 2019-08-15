<template>
  <div>
    <navbar></navbar>
    <uploadForm></uploadForm>
  </div>
</template>

<script>
import navbar from './components/navbar'
import uploadForm from './components/uploadForm'
export default {
  data() {
    return {
      message: 'Hello world',
    };
  },
  components:{
    navbar: navbar,
    uploadForm
  },
  methods:{
  }
};
</script>

<style scoped>
</style>    