<template>
  <footer class="footer">
    <p>Make Your Burger &copy; 2022</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 200px;
  width: 100%;
  bottom: 0;
  background: #222;
  border-top: 4px solid #111;
  color: #fcba03;
}
</style>
