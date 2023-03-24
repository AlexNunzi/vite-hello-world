<script>

</script>

<template>
  <div class="container-relative">
    <div class="background"></div>
    <h1>La mia prima app con Vite!</h1>
  </div>

</template>

<style scoped>

.container-relative{
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  height: 250px;
  width: 500px;
}
.background{
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background: linear-gradient(-45deg, #BD34FE 50%, #45CCFF 50%);
  animation: pulse 5s infinite;
  filter: blur(50px);
  z-index: 50;
  border-radius: 100%;
}

@keyframes pulse {
  50% {
    transform: scale(1.5);
  }
}

h1{
  white-space: nowrap;
  font-family: sans-serif;
  position: relative;
  z-index: 100;
  color:#FFDC34;
}
</style>
