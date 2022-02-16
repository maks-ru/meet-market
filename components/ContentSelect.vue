<template>
  <div>
    <v-row>
      <div class="selec-groupe">
        <div class="select-item">
          <button v-on:click="greet">По популярности</button>
        </div>
        <div class="select-item">
          <button v-on:click="greet">Бренд (2)</button>
        </div>
        <div class="select-item">
          <button v-on:click="greet">Модель</button>
        </div>
        <div class="select-item">
          <button v-on:click="greet">Стоимость (1)</button>
        </div>
        <div class="select-item">
          <button v-on:click="greet">Размер</button>
        </div>
        <div class="select-item">
          <button v-on:click="greet">Пол</button>
        </div>       
      </div>
    </v-row>
  </div>
</template>

<script>
export default {
  data: () => ({
    selected: "",
  }),
  methods: {
    greet:  () => {
      alert('HI')
    },
  },
};
</script>


<style scoped lang="scss">
.selec-groupe {
  display: flex;
}
.select-item {
  margin-left: 10px;
}
select {
  outline: none;
  border: 1px solid black;
  border-radius: 6px;
  width: 170px;
  margin-bottom: 104px;
  // margin-right: 12px;
  padding: 16px 0 17px 22px;
}
button {
  outline: none;
  border: 1px solid black;
  border-radius: 6px;
  width: 150px;
  margin-bottom: 104px;
  // margin-right: 12px;
  padding: 16px 0 17px 0;
}
</style>