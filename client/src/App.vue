<template>
<div>
  <uploadForm></uploadForm>

</div>
</template>

<script>
import uploadForm from './components/uploadForm'
export default {
  data() {
    return {
      message: 'Hello world',
    };
  },
  components:{
    uploadForm
  },
  methods:{
  }
};
</script>

<style scoped>
</style>    