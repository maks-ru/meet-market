<template>
  <div class="container">
    <div class="compilation">
      <span>Подборки Meet-market</span>
    </div>
    <ul>
      <li><a href="/">Все товары</a></li>
      <li><a href="/">Популярные</a></li>
      <li><a href="/">Экспресс-доставка</a></li>
      <li><a href="/">Новинки</a></li>
      <li><a href="/">Black&White</a></li>
      <li><a href="/">Зима</a></li>
      <li><a href="/">Подборка Light</a></li>
      <li><a href="/">Подборка Multicolor</a></li>
      <li><a href="/">Подборка Dark</a></li>
    </ul>
  </div>
</template>
<script>
export default {};
</script>
<style scoped lang="scss">
.container {
  margin-right: 10px;
  width: 245px;
}
.compilation {
 margin-left: 25px;
}
ul {
  li {
    list-style: none;
    margin-bottom: 28px;
    color: #1D1D20;
    font-size: 21px;
  }
}
a {
  text-decoration: none;
  color: #1d1d20;
}
.compilation {
  margin-bottom: 28px;
  span {
    color: rgba(29, 29, 32, 0.3);
  }
}
</style>