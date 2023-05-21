<template>
  <nav class="bg-primary">
    <div class="container d-flex justify-content-between">
      <div class="nav-item">
        <span>
          <img src="../img/buy-comics-digital-comics.png" alt="" />
        </span>
        <span> Digital Comics </span>
      </div>
      <div class="nav-item">
        <span>
          <img src="../img/buy-comics-merchandise.png" alt="" />
        </span>
        <span> DCMERCHANDISE </span>
      </div>
      <div class="nav-item">
        <span>
          <img src="../img/buy-comics-subscriptions.png" alt="" />
        </span>
        <span> SUBSCRIPTION </span>
      </div>
      <div class="nav-item">
        <span>
          <img src="../img/buy-comics-shop-locator.png" alt="" />
        </span>
        <span> COMIC SHOP LOCATOR </span>
      </div>
      <div class="nav-item">
        <span>
          <img src="../img/buy-dc-power-visa.svg" alt="" />
        </span>
        <span> DC power visa </span>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: "jumboNavbar",
};
</script>

<style scoped lang="scss">
$container-height: 8em;
nav {
  display: flex;
  align-items: center;
  height: $container-height;
}
.nav-item {
  color: white;
  text-transform: uppercase;
  display: flex;
  gap: 1em;
  align-items: center;
  img {
    height: 3em;
    width: 100%;
  }
}
</style>
