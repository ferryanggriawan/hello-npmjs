<template>
  <div>
    <h3>{{ title }}</h3>
    <span>{{ name }}</span>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: "Hello Man",
    },
    name: {
      type: String,
      default: "Ferry",
    },
  },
}
</script>

<style></style>
