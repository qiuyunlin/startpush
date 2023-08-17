<script setup>
</script>
<template>
  <div class="container">
    <header class="click"></header>
    <div class="background">
    </div>
  </div>
</template>

<style scoped>
.container {
  position: relative;
  width: 100vw;
  height: 100vh;
}
.head {
  font-size: 16px;
  color: red;
}
.click {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 60px;
  height: 30px;
  color: #fff;
  background-image: linear-gradient(to bottom right, #529199 , #561299);
  border-radius: 5px;
}
.background {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(#000,0.3)
}

</style>