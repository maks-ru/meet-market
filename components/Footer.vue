<template>
  <v-footer class="footer">
    <div class="container">
      <div class="footer-top">
        <div class="map">
          <img src="icons/map.png" alt="map" />
        </div>
        <div class="region">
          <span>Ваш регион - <a href="/">Владивосток</a></span>
        </div>

        <div class="icon">
          <div class="icon-title">
            <span>Платёжные системы</span>
          </div>
          <ul class="icon-items">
            <li><img src="icons/visa.png" alt="visa" /></li>
            <li>
              <img src="icons/mastercard.png" alt="mastercard" />
            </li>
            <li><img src="icons/maestro.png" alt="maestro" /></li>
            <li><img src="icons/applepay.png" alt="applepay" /></li>
            <li><img src="icons/gpay.png" alt="gpay" /></li>
          </ul>
        </div>
      </div>

      <v-divider></v-divider>

      <div class="footer-center">
        <div class="footer-center-menu">
          <div class="left-menu">
            <ul>
              <li class="child">Магазин</li>
              <li><a href="/">Обувь</a></li>
              <li><a href="/">Одежда</a></li>
              <li><a href="/">Аксессуары</a></li>
            </ul>
          </div>

          <div class="right-menu">
            <ul>
              <li class="child">О компании</li>
              <li><a href="/">О Meet</a></li>
              <li><a href="/">Доставка</a></li>
              <li><a href="/">Цена и оплата</a></li>
              <li><a href="/">Контакты</a></li>
            </ul>
          </div>
        </div>

        <div class="footer-center-form">
          <div class="footer-center-form-title">
            <span>Будь первым в курсе акций и релизов!</span>
          </div>
          <form>
            <input type="text" placeholder="Ваш email" />
            <button>Подписаться на рассылку</button>
          </form>
        </div>

        <div class="footer-center-social">
          <div class="footer-center-social-title">
            <span>Телефон</span>
          </div>
          <div class="footer-center-phone">
            <img src="icons/phone-border.png" alt="phone" />
            <div>
              <span>+7 (924) 240-90-77</span>
            </div>
          </div>

          <div class="footer-center-social-icons">
            <span>Мы в социальных сетях</span>
          </div>
          <div class="social-icon-groupe">
            <ul class="social-list">
              <li class="vk"><img src="icons/social/vk.png" alt="vk" /></li>
              <li class="instagram">
                <img src="icons/social/instagram.png" alt="instagram" />
              </li>
              <li class="facebook">
                <img src="icons/social/facebook.png" alt="facebook" />
              </li>
              <li class="telegram">
                <img src="icons/social/telegram.png" alt="telegram" />
              </li>
            </ul>
          </div>

          <div class="footer-center-social-icon"></div>
        </div>
      </div>

      <v-divider></v-divider>

      <div class="footer-bottom">
        <div class="footer-bottom-staus">
          <a href="/">ООО “Статус”, 2020. Все права защищены</a>
        </div>
        <div class="footer-bottom-politics">
          <a href="/">Политика конфиденциальности</a>
        </div>
      </div>
    </div>
  </v-footer>
</template>


<script>
export default {};
</script>


<style scoped lang="scss">
.container {
  width: 1625px;
  height: 620px;
  padding: 0;
}
a {
  text-decoration: none;
}
li {
  list-style: none;
}
.footer {
  background-color: #f3f3f3;
  padding: 0;
}
.icon {
  margin: 0 auto;
}
.icon-title {
  span {
    font-weight: 600;
    font-size: 15px;
    color: #b7bec4;
  }
}
.icon-items {
  padding: 0;
}
.footer-top {
  display: flex;
  align-items: center;
  margin-top: 40px;
  margin-bottom: 50px;
}
.region {
  margin-left: 20px;
  a {
    color: #84a2fc;
    border-bottom: 2px solid #84a2fc;
  }
  span {
    font-size: 16px;
  }
}
.icon-title {
  padding-bottom: 20px;
}
.icon-items {
  display: flex;
  li {
    list-style: none;
    margin-right: 16px;
  }
}
.footer-center {
  display: flex;
  justify-content: space-between;
  margin-top: 45px;
  margin-bottom: 100px;
}
.left-menu {
  margin-right: 35px;
}
.footer-center-menu {
  display: flex;
  li {
    margin-bottom: 20px;
  }
  .child {
    color: #b7bec4;
    font-weight: 600;
    font-size: 15px;
  }

  a {
    color: #1d1d20;
    font-size: 18px;
  }
}

.footer-center-form {
  text-align: center;
  input {
    background: #fefefe;
    border-radius: 6px;
    padding: 20px 0 20px 24px;
    margin-bottom: 18px;
    width: 354px;
    outline: none;
  }
  button {
    padding: 20px 88px;
    background: #1d1d20;
    border-radius: 6px;
    color: #fefefe;
    font-size: 15px;
  }
}
.footer-center-form-title {
  margin-bottom: 22px;
  span {
    color: #1d1d20;
    font-weight: bold;
    font-size: 18px;
  }
}

.footer-center-social-title {
  margin-bottom: 18px;
  span {
    color: #b7bec4;
    font-weight: 600;
    font-size: 15px;
  }
}

.footer-center-social-icons {
  margin-bottom: 18px;
  span {
    color: #b7bec4;
    font-weight: 600;
    font-size: 15px;
  }
}
.footer-center-phone {
  display: flex;
  align-items: center;
  margin-bottom: 50px;
  img {
    margin-right: 20px;
  }
  span {
    color: #1d1d20;
    font-weight: 600;
    font-size: 18px;
  }
}
.social-list {
  padding: 0;
  display: flex;
  li {
    margin-right: 16px;
  }
}
.footer-bottom {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 50px;
}
.footer-bottom-staus {
  margin-bottom: 50px;
  a {
    color: #b7bec4;
    font-size: 18px;
  }
}
.footer-bottom-politics {
  margin-bottom: 50px;
  a {
    color: #b7bec4;
    font-size: 18px;
    border-bottom: 2px solid #b7bec4;
  }
}
</style>