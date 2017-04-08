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
  deactivated() {
    console.log('New.vue Deactivated!');
  },
  activated() {
    console.log('New.vue Activated!');
  },
};
</script>

<style>
</style>
