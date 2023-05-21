<template>
  <div class="container-fluid p-0">
    <div class="row justify-content-center">
      <div class="col-12 p-">
        <navbar></navbar>
        <jumboMain></jumboMain>
      </div>
    </div>
  </div>
</template>

<script>
import navBar from "./components/navBar.vue";
// jumbo
import jumboMain from "./components/jumbo-main.vue";

export default {
  name: "App",
  components: {
    navbar: navBar,
    jumboMain: jumboMain,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
</style>
