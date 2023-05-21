<template>
  <jumboContent></jumboContent>
  <jumboNavBar></jumboNavBar>
  <div class="container-fluid main p-5">
    <div class="container">
      <div class="main--container">
        <div class="item--container p-0">
          <div class="tem--container p-0">
            <h5>DC COMICS</h5>
            <ul>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">Tv</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Videos</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
            </ul>
          </div>
          <div class="item--container">
            <h5>SHOP</h5>
            <ul>
              <li>
                <a href="#">Shop Dc</a>
              </li>
              <li>
                <a href="#">Shop Dc Collactables</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="item--container p-0">
          <h5>DC</h5>
          <ul>
            <li>
              <a href="#">Terms Of Use</a>
            </li>
            <li>
              <a href="#">Privacy</a>
            </li>
            <li>
              <a href="#">Ad Choices</a>
            </li>
            <li>
              <a href="#">Advertising</a>
            </li>
            <li>
              <a href="#">Jobs</a>
            </li>
            <li>
              <a href="#">Subscriptions</a>
            </li>
            <li>
              <a href="#">Talent Workshops</a>
            </li>
            <li>
              <a href="#">CPSC Certificate</a>
            </li>
            <li>
              <a href="#">Ratings</a>
            </li>
            <li>
              <a href="#">Shop Help</a>
            </li>
            <li>
              <a href="#">Contact Us</a>
            </li>
          </ul>
        </div>
        <div class="container p-0">
          <h5>SITES</h5>
          <ul>
            <li>
              <a href="#">DC</a>
            </li>
            <li>
              <a href="#">MAD Magazine</a>
            </li>
            <li>
              <a href="#">DC Kids</a>
            </li>
            <li>
              <a href="#">DC Universe</a>
            </li>
            <li>
              <a href="#">DC PowerVisa</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import jumboNavBar from "./jumbo-navbar.vue";
import jumboContent from "./jumbo-content.vue";
export default {
  nama: "jumboMain",
  components: {
    jumboNavBar: jumboNavBar,
    jumboContent: jumboContent,
  },
};
</script>

<style scoped lang="scss">
$list-title--color: white;
$list-item--color: rgb(103, 103, 103);

.main {
  background-image: url("../img/footer-bg.jpg");
  background-position: center;
  img {
    height: 120%;
    top: -15%;
    right: 20%;
    z-index: 0;
    position: absolute;
  }
  .main--container {
    display: flex;
  }
  .item--container {
    margin-right: 1em;
  }

  h5 {
    color: $list-title--color;
  }
  ul {
    list-style-type: none;
    padding-left: 0;
    a {
      color: $list-item--color;
      text-decoration: none;
    }
  }
}
</style>
