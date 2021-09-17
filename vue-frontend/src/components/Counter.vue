<template>
  <div>
    <p>I'm a Counter! Current count: {{count}}</p>
    <button @click="count += 1">Add 1</button>
    <button @click="count -= 1">Remove 1</button>
  </div>
</template>

<script>
export default {
  props:['count'],
  data() {
    return {

    };
  }
};
</script>

<style>
</style>
