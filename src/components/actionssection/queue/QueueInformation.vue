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
  width: 300px;
  margin: 0 auto; 
  padding: 20px; 
  margin-left: 5px;
  margin-right: 5px; 
  background-color: pink;
}
</style>
