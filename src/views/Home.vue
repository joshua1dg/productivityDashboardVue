<template>
  <div class="home">
    <div class="grid-x">
      <div class="cell large-2 sidebar">

      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
  components: {
  }
}

</script>

<style lang='scss' scoped>
  .sidebar{
    background-color: green;
    height: 100vh;
    .hi{
      background-color: blue;
      height: 5%;
    }
  }
</style>
