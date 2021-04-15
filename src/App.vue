<template>
  <div id="app">
      <h1>Problema de Monty Hall</h1>
      <Gift />
  </div>
</template>


<script>
import Gift from './components/Gift'


export default {
    name: 'App',
    components: { Gift }
}

</script>


<style>
* {
    box-sizing: border-box;
    font-family: 'Montserrat', 'sans-serif';
}

body {
    color: #fff;
    background: -webkit-linear-gradient(to right, #A7BFE8, #6190E8);  
    background: linear-gradient(to right, #A7BFE8, #6190E8); 
}

#app {
    display: flex;
    flex-direction: column;
    align-items: center;
}

#app h1 {
    border: 1px solid #000;
    background-color: #0004;
    padding: 20px;
    margin-bottom: 60px;
}
</style>