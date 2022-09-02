<template>
<div>
    <div>
        <h2>{{ count }}</h2>
    </div>
    <button @click="count++">You clicked me!</button>
</div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<style scoped>
button {
  height: 50px;
  font-size: 2ch;
  border-bottom-color: #42b983;
  border-radius: 10px;
  background-color: #42b983;
}
</style>