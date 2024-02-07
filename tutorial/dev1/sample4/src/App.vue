<script setup>
const handleClick = () => {
  alert("ボタンがマウスオーバーされました")
}
const handleMouseOver = () => {
  alert("ボタンがマウスオーバーされました")
}
</script>

<template>
  <h1>Sample4</h1>
  <button @click="handleClick">Click</button>
  <button @mouseover="handleMouseOver">MouseOver</button>
</template>
