<template>
  <div>
    <todolist></todolist>
  </div>
  <router-view></router-view>
</template>

<script>
import todolist from './components/todolist';

export default {
  data() {
    return {

    }
  },
  components: {
    todolist
  }
}

</script>

<style>

</style>
