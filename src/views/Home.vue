<template>
  <div class="home">
    <FirstComponent msg="FIRST VIEW HOURA" />
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import FirstComponent from "@/components/FirstComponent.vue";

export default {
  name: "home",
  components: {
    FirstComponent,
    HelloWorld
  }
};
</script>
