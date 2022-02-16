<template >
  <v-app-bar dense height="180">
    <div class="container">
      <div class="wrapper">
        <v-row align="center" class="mt-5">
          <div class="map">
            <img src="icons/map.png" alt="map">
          </div>
          <div class="region">
            <span>Ваш регион - <a href="/">Владивосток</a></span>
          </div>

          <v-row justify="center">
            <div class="meet-menu">
              <ul class="meet-menu-list">
                <li><a href="/">Доставка и оплата</a></li>
                <li><a href="/">Обмен и возврат</a></li>
                <li><a href="/">Контакты</a></li>
                <li><a href="/">Документация</a></li>
              </ul>
            </div>
          </v-row>
          <div class="phone">
            <img src="icons/phone.png" alt="phone" />
            <span>+7 (924) 240-90-77</span>
          </div>
        </v-row>
      </div>
      <!-- <div class="line">
      </div> -->
      <v-divider class="mt-12" />

      <v-row align="center" class="py-7" justify="space-between">
        <a href="/" class="btn-header-top">Стать продавцом</a>

        <a href="/" class="logo">
          <img src="icons/logo.png" alt="logo" />
        </a>

        <div class="menu-blog">
          <ul class="meet-menu-blog">
            <li><a href="/">Наш блог</a></li>
            <li><a href="/">О Meet</a></li>
          </ul>
        </div>
      </v-row>
    </div>
  </v-app-bar>
</template>
<script>
export default {};
</script>

<style scoped lang="scss">
.container {
  width: 1625px; 
}

a {
  text-decoration: none;
  color: #1d1d20;
}
li {
  list-style: none;
}
.region {
  a {
    color: #84a2fc;
    border-bottom: 2px solid #84a2fc;
  }
  span {
    font-size: 16px;
  }
}
.meet-menu-list {
  padding: 0;
  display: flex;
  align-items: center;
  li {
    margin-right: 40px;
  }
  li:last-child {
    margin-right: 0;
  }
}
.phone {
  span {
    color: #1d1d20;
  }
}

.line {
  border: 1px solid rgba(229, 229, 229, 1);
  margin-top: 22px;
}
.meet-menu-blog {
  display: flex;
  align-items: center;
  li {
    margin-right: 40px;
  }
  li:last-child {
    margin-right: 0;
  }
}
.btn-header-top {
  border: 1px solid #1d1d20;
  border-radius: 6px;
  padding: 20px 24px;
}
.btn-header-top:hover {
  background: #1d1d20;
  color: #fefefe;
  transition: 0.7s;
}
span {
  padding-left: 10px;
}
</style>