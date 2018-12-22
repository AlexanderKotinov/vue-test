<template>
  <div>
    <p>Quote</p>
    <p>{{ quote }}</p>
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: "Quote",
    props: [
      'quote'
    ]
  }
</script>

<style scoped>
  div {
    border: 1px solid #ccc;
    box-shadow: 1px 1px 2px black;
    padding: 30px;
    margin: auto;
  }
</style>