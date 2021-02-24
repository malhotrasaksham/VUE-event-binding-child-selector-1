<template>
  <button @click="showMessage">Hi</button>
</template>

<script>
export default {
  name: "HelloWorld",
  methods:{
    showMessage() {
      alert('Meh');
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
