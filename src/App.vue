<template>
  <div id="app" class="app">
    <div class="title">
      <h1>根组件</h1>
    </div>
    <div>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
.title {
  text-align: center;
}
</style>
