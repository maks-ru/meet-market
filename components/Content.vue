<template >
  <div class="container">
    <div class="breadcrumbs">
      <span>Главная/</span><span>Кроссовки</span>
      <div class="bannet-title">
        <h3>КРОССОВКИ: НОВИНКИ</h3>
        <span>594 товара</span>
      </div>
    </div>

    <div class="content-menu">
      <div class="sidebar">
        <ContentLeftMenu />
      </div>
    </div>
    <div class="content">
      <div class="card">
        <ContentSelect />
        <div class="content-card">
          <div class="card-item" v-for="item in items" :key="item.id">
            <div class="card-item-img">
              <span>
                <img src="img/card/feature.png" alt="feature" />
              </span>
              <img :src="item.src" alt="card" />
            </div>
            <div class="card-item-price">
              <span>{{ item.price }}</span>
              <h3>{{ item.title }}</h3>
            </div>
            <div class="card-item-button">
              <button class="naw">Новинка</button>
              <button class="recomend">96% рекомендуют</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
        {
          id: Date.now(),
          src: "",
          price: 4500,
          title: "Yeezy Boost 350 V2 Ash Pearl",
          src: "img/image1.png",
        },
      ],
    };
  },
};
</script>
<style scoped lang="scss">
.container {
  width: 1625px;
  padding: 0;
}
.breadcrumbs {
  margin-top: 32px;
  margin-bottom: 40px;
  span {
    color: rgba(29, 29, 32, 0.3);
  }
}
.bannet-title {
  display: flex;
  align-items: center;
  h3 {
    font-size: 28px;
    color: #1d1d20;
    margin-right: 20px;
  }
  span {
    color: rgba(29, 29, 32, 0.3);
  }
}
.content {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.content-menu {
  float: left;
}
.content-card {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  margin-bottom: 80px;
}
.card-item {
  width: 300px;
  border: 1px solid rgba(29, 29, 32, 0.1);
  border-radius: 8px;
  background: #fefefe;
  margin-bottom: 40px;
}
.card-item-img {
  position: relative;
  span {
    position: absolute;
    top: 27px;
    right: 27px;
  }
}
.card-item-price {
  margin-left: 20px;
  margin-top: 16px;
  margin-bottom: 40px;
  span {
    color: #1d1d20;
    font-size: 20px;
  }
  h3 {
    margin-top: 12px;
    color: #1d1d20;
    font-size: 16px;
  }
}
.card-item-button {
  margin-left: 20px;
  margin-bottom: 20px;
  .naw {
    border-radius: 4px;
    background: #84a2fc;
    padding: 10px;
    color: #fefefe;
    margin-right: 7px;
  }
  .recomend {
    border-radius: 4px;
    background: #e1f5c7;
    padding: 10px;
    color: #7cd010;
  }
}
</style>