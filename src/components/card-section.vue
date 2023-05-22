<template>
  <div class="container-fluid">
    <div class="container p-5">
      <div class="row">
        <div class="col-2 p-3" v-for="(comic, i) in comics">
          <div class="card p-0">
            <div class="card-body p-0">
              <img :src="comics[i].thumb" />
            </div>
            <div class="card--footer p-0">
              <div class="container--item">
                 
                <span>{{ comics[i].series }} </span>
              </div>
              <div class="container--item">
                <span> {{ comics[i].price }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "cardList",
  props: ["comics"],
  data() {
    return {};
  },
};
</script>

<style scoped lang="scss">
.container-fluid {
  background-color: black;
  .container {
    background-color: rgb(11, 9, 9);
    .card {
      border: none;
      img {
        border: none;
        object-fit: cover;
        object-position: top;
        width: 100%;
        height: 11rem;
      }
      .card--footer {
        display: flex;
        justify-content: space-between;
        background-color: black;
        text-transform: uppercase;
        font-size: smaller;
        color: white;
      }
    }
  }
}
</style>
