<template>
<div>
  <h1>{{titleText}}</h1>
</div>
</template>

<script>
export default {
  name: "Title",
  props: {
    titleText: String
  }
}
</script>

<style>
  h1{
    color: red;
  }
</style>