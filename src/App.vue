<script>
export default {
  data() {
    return {
      titleClass: 'title'
    }
  }
}
</script>

<template>
  <h1 :class="titleClass">Brutalism</h1>
</template>

<style>
.title {
  color: red;
}
</style>