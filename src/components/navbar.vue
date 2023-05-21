<template>
  <nav class="navbar p-0">
    <div class="container">
      <div class="navbar-brand">
        <img src="../img/dc-logo.png" />
      </div>
      <nav class="nav-item">
        <a>characters</a>
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
  height: $container-height;
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
    height: $container-height;
    display: flex;
    align-items: center;
    gap: 2em;

    a {
      font-weight: bolder;
      font-size: smaller;
      line-height: $container-height;
      text-transform: uppercase;
    }
  }
}
</style>
