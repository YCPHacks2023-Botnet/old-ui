<template>
  <div class="item">
    <div class="details">
      <h3>
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.details {
  width: 25%;
  height: 30%;
  margin: 0 auto; 
  padding: 20px; 
  background-color: green;
}
</style>
