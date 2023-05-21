<template>
  <div class="container-fluid main">
    <div class="container">
      <div class="navbar--item">
        <button class="btn">
          <a href="#"> SIGN-UP NOW </a>
        </button>
      </div>
      <div class="navbar--item">
        <h5>Follow us</h5>
        <a href="#">
          <img src="../img/footer-facebook.png" alt="Facebook" />
        </a>
        <a href="#">
          <img src="../img/footer-periscope.png" alt="Facebook" />
        </a>
        <a href="#">
          <img src="../img/footer-pinterest.png" alt="Facebook" />
        </a>
        <a href="#">
          <img src="../img/footer-twitter.png" alt="Facebook" />
        </a>
        <a href="#">
          <img src="../img/footer-youtube.png" alt="Facebook" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "appFooter",
};
</script>

<style scoped lang="scss">
.main {
  background-color: rgb(77, 77, 77);
  .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 2em;
  }
  .navbar--item {
    gap: 1em;
    display: flex;
    align-items: center;
  }
  h5 {
    margin: 0;
    text-transform: uppercase;
    font-weight: bolder;
    color: rgb(0, 115, 255);
  }
  button {
    border: 2px solid rgb(0, 115, 255);
  }
  a {
    text-decoration: none;
    color: white;
  }
}
</style>
