<script>
export default {
  data() {
    return {
      titleClass: 'title',
      count: 0,
      text: ''
    }
  },
  methods: {
    increment() {
      this.count++;
    }
  }
}
</script>

<!-- where the preview starts -->
<template>

  <h1 :class="titleClass">Hello World!</h1> <!-- text-styling -->

  <button @click="increment">count is: {{ count }}</button> <!-- on-click events -->
  <p></p>
  <input v-model="text" type="text" size="4" placeholder="Watch me change by typing!"> <!-- input text field -->
  <p>{{ text }}</p>

</template>

<!-- where the styling starts -->
<style>
.title {
  color: red;
}
</style>