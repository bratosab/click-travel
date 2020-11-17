<template>
  <div class="logo"></div>
</template>

<style>
.logo {
  animation: 1s appear;
  margin: auto;
  background-image: url('~assets/logo.png');
  background-size: contain;
  background-repeat: no-repeat;
  height: 80px;
  margin-left: 12px;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
