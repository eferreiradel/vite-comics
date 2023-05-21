<template>
  <div class="container-fluid">
    <div class="container">
      <h2>Content Goes Here</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: "jumboContent",
};
</script>
<style scoped lang="scss">
$container-padding: 1.5em;

.container-fluid {
  width: 100%;
  padding: $container-padding;
  background-color: rgb(30, 30, 30);
  .container {
    height: 100%;
    display: flex;
    align-items: center;
  }
  h2 {
    color: white;
  }
}
</style>
