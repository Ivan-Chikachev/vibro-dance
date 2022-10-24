<template>
  <div class="list">
    <button class="btn" @click="click">Вибро клик</button>
    <button class="btn" @click="clickDance">Вибро денс</button>
  </div>
</template>

<script>
export default {
  methods: {
    click() {
      window.navigator.vibrate([200]);
    },
    clickDance() {
      window.navigator.vibrate([50, 10, 100, 100, 50,50, 400,400,10,10,10,10,5,5,5,5,1000]);
    }
  }
};
</script>

<style lang="scss">
html, body, #app {
  height: 100%;
}
.list {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.btn {
  padding: 20px 40px;
}
</style>
