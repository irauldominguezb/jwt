<template>
    <div class="background">
        <h1>Bienvenido Admin</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AdminView',
   
  }
  </script>
  
  <style scoped>
  .background{
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    background-image: url('@/assets/imgFoto.jpg');
    backdrop-filter: contrast(0.5);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

  }
  </style>
  