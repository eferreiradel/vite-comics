<template>
  <nav class="navbar p-0">
    <div class="container p-0">
      <div class="navbar-brand p-0">
        <img src="../img/dc-logo.png" />
      </div>
      <nav class="nav-item p-0">
        <a>characters </a>
        <a>comics</a>
        <a>movies</a>
        <a>tv</a>
        <a>games</a>
        <a>collectibles</a>
        <a>videos</a>
        <a>fans</a>
        <a>news</a>
        <a>shop</a>
      </nav>
    </div>
  </nav>
</template>
<script>
export default {
  name: "navBar",
};
</script>

<style scoped lang="scss">
$container-height: 7em;
$underline-height: 5px;

.container {
  display: flex;

  .navbar-brand {
    display: flex;
    align-items: center;
    justify-content: center;

    img {
      width: 70%;
    }
  }

  .nav-item {
    position: relative;
    display: flex;
    align-items: center;
    gap: 2em;

    a {
      font-weight: bolder;
      font-size: smaller;
      text-transform: uppercase;
      line-height: $container-height;
    }
  }
}
</style>
