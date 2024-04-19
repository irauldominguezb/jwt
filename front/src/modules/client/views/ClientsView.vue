<template>
    <div class="shape">
        <h1>Bienvenido usuario</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ClientsView',
   
  }
  </script>
  
  <style scoped>
  .shape {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  background-image: url('@/assets/galaxy.jpg');
  backdrop-filter: contrast(0.5);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

  </style>
  