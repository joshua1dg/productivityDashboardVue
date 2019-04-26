<template>
    <div class="home container-fluid">
      <div class="row no-gutters">
        <div class="col-sm-2">
          <Sidebar/>
        </div>
        <div class="col-sm-8">
          <Header/>
          <FollowerSummary/>
          <Weather/>
        </div>
        <div class="col-sm-2">
          <Agenda/>
          <Todo/>
        </div>
      </div>
    </div>
</template>

<script>
// @ is an alias to /src
import Sidebar from '../components/Sidebar.vue';
import Header from '../components/summaryPage/Header';
import FollowerSummary from '../components/summaryPage/FollowerSummary';
import Weather from '../components/summaryPage/Weather';
import Agenda from '../components/summaryPage/Agenda';
import Todo from '../components/summaryPage/TodoList';


export default {
  name: 'home',
  components: {
    Sidebar,
    Header,
    FollowerSummary,
    Weather,
    Agenda,
    Todo
  }
}

</script>

<style lang='scss' scoped>
</style>
