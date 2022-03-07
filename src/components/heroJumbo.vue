<template>
  <div class="container">
    <h1>Jumbotron</h1>
  </div>
</template>

<script>
export default {
  name: "heroJumbo",
};
</script>

<style scoped lang="scss">
.container {
  height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: url(https://picsum.photos/1000) no-repeat center;
  background-size: cover;
}

h1 {
  padding: 50px 100px;
  border-radius: 10px;
  font-size: 60px;
  color: white;
  background: rgba($color: #000000, $alpha: 0.5);
}
</style>
