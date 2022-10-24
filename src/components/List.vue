<template>
  <div class="list">
    <button class="btn" @click="clickOk">Вибро денс</button>
  </div>
</template>

<script>
export default {
  methods: {
    clickOk() {
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
