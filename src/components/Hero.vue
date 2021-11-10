<template>
  <div>
    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h2 class="display-4">{{titleJumbotron}}</h2>
        <p class="lead">This is a Bootstrap jumbotron imported as component.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "Hero",
props: {
    titleJumbotron: String
  }
}
</script>

<style>
  .container{
    background-color: darkgray;
    padding: 50px;
  }
  h2{
    color: black;
  }
  p{

  }
</style>