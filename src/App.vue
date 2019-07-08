<template>
  <div id="app">
    <!-- 头部 -->
    <app-header></app-header>
    <div class="container-fluid">
      <div class="row">
        <!-- 左侧 -->
        <app-sidebar></app-sidebar>
        <!-- 右侧 -->
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppSidebar from "./components/AppSidebar.vue";
export default {
  name: "app",
  components: {
    AppHeader,
    AppSidebar
  }
};
</script>

<style lang="scss">
</style>
