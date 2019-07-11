<template>
  <button
    type="button"
    @click="clickButton"
  >Click me!!</button>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    clickButton() {
      count++
      console.log(count)
    }
  }
}
</script>

<style lang="scss" scoped>
button {
  background-image: url("example.png");
  display: block;
  margin: 0 0 16px;
}
</style>
