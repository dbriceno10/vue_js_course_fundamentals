<template>
  <div>
    <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "Hello Vue"
    }
  }
}
</script>

<style>
p {
  color: red;
}
</style>