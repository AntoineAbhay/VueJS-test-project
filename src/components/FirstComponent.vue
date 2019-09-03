<template>
  <div>
    <h3>{{ msg }}</h3>
    <p>This is my first paragraph</p>
  </div>
</template>

<script>
export default {
  name: "FirstComponent",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
  color: #42b983;
}
</style>
