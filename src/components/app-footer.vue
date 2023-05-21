<template>
  <div class="container-fluid main">
    <div class="container">
      <nav>
        <div class="navbar-item">
          <button class="btn">
            <a href="#"> SIGN-UP NOW </a>
          </button>
        </div>
        <div class="navbar-item">
          <h5>Follow us</h5>
        </div>
      </nav>
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
  nav {
    display: flex;
    justify-content: space-between;
    padding: 2em;
  }
  .navbat--item {
    display: flex;
    align-items: center;
  }
  h5 {
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
