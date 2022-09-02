<template>
  <div class="hello">
    <home></home>
    <logo></logo>
    <h1>{{ msg }}</h1>
    <button-counter></button-counter>
  </div>
</template>
<script>
import ButtonCounter from "../components/ButtonCounter.vue";
import Logo from "../components/Logo.vue";
import Home from './Home.vue';

export default {
  name: "HelloWorld",
  components: {
    ButtonCounter,
    Logo,
    Home,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
a {
  color: #42b983;
}
</style>
