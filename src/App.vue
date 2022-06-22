<script>
export default {
  data() {
    return {
      titleClass: 'title',
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++;
    }
  }
}
</script>

<template>
  <h1 :class="titleClass">Hello World!</h1>
  <button @click="increment">count is: {{ count }}</button>
</template>

<style>
.title {
  color: red;
}
</style>