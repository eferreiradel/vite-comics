<template>
  <nav class="navbar p-0">
    <div class="container p-0">
      <div class="navbar-brand p-0">
        <img src="../img/dc-logo.png" />
      </div>
      <nav class="nav-item p-0">
        <span>
          <a>characters </a>
          <span class="underline"></span>
        </span>
        <span>
          <a>comics</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>movies</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>tv</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>games</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>collectibles</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>videos</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>fans</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>news</a>
          <span class="underline"></span>
        </span>
        <span>
          <a>shop</a>
          <span class="underline"></span>
        </span>
      </nav>
    </div>
  </nav>
</template>
<script>
export default {
  name: "navBar",
  data() {
    return {};
  },
  methods: {},
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
    display: flex;
    align-items: center;
    gap: 2em;
    span {
      position: relative;

      .underline {
        opacity: 0;
        background-color: rgb(0, 89, 255);
        position: absolute;
        height: 10px;
        width: 100%;
        bottom: 0;
        left: 0;
        transition: 0.1s ease-in-out;
      }
    }
    span:hover {
      .underline {
        opacity: 100;
        display: block;
      }
    }

    a {
      font-weight: bolder;
      font-size: smaller;
      text-transform: uppercase;
      line-height: $container-height;
    }
  }
}
</style>
