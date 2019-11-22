<template>
  <button class="btn">Hello {{ name }}!</button>
</template>

<script>
export default {
  props: ["name"]
};
</script>

<style scoped>
.btn {
  font-size: 200%;
}
</style>
