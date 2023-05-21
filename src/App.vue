<template>
  <div class="container-fluid p-0">
    <div class="row justify-content-center">
      <div class="col-12 p-">
        <header>
          <navbar></navbar>
        </header>
        <main>
          <jumboMain></jumboMain>
        </main>
        <footer>
          <appFooter></appFooter>
        </footer>
      </div>
    </div>
  </div>
</template>

<script>
import navBar from "./components/navBar.vue";
// jumbo
import jumboMain from "./components/jumbo-main.vue";
//footer
import appFooter from "./components/app-footer.vue";

export default {
  name: "App",
  components: {
    navbar: navBar,
    jumboMain: jumboMain,
    appFooter: appFooter,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
</style>
