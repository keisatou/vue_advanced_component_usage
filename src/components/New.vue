<template>
  <div>
    <h3>The Quote</h3>
    <button @click="counter++">Increase!</button>
    {{ counter }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0,
    };
  },
  destroyed() {
    console.log('New.vue Destroyed!');
  },
};
</script>

<style>
</style>
