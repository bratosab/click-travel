<template>
  <div class="logo"></div>
</template>

<style>
.logo {
  animation: 1s appear;
  margin: auto;
  background-image: url('~assets/logo.svg');
  background-size: contain;
  background-repeat: no-repeat;
  height: 60px;
  margin: 10px 12px;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
