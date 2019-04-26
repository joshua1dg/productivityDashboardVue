<template>
  <div class="wrapper container">
    <nav id="sidebar center">
      <div class="sidebar-header">
        <h3>Dashboard</h3>
      </div>

      <ul class="list-unstyled components">
        <p>Dummy Heading</p>
        <li class="active nav-link">
          <a href="#">Summary</a>
        <li class="nav-link">
          <a href="#">Stats</a>
        </li>
        <li class="nav-link">
            <a href="#">Feeds</a>
        </li>
      </ul>
    </nav>

    <div id="content">

    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Sidebar',
  components: {
  }
}

</script>

<style lang='scss' scoped>
  .wrapper {
    display: flex;
    // height: 100vh;
    #sidebar{
      // align-items: stretch;
    }
  }
</style>