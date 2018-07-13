<template>
  <div class="color-button">
    <slot>Button</slot>
  </div>
</template>

<script>
export default {
  name: 'color-button'
}
</script>

<style>
.color-button {
  width: 100px;
  height: 40px;
  border-radius: 4px;
  line-height: 40px;
  text-align: center;
  color: #ffffff;
  background-color: #212121;
}
.color-button:hover {
  color: #212121;
  border: 1px solid #212121;
  background-color: #fff;
}
</style>
