<template>
  <div class="todo">

  </div>
</template>

<script setup>

const a = ['asdas', 'asdasd']

fn()

function fn(acc, item) {

  return acc + item
}

console.log(a.reduce(fn, 10));



</script>
