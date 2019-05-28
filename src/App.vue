<template>
  <div id="app">
   <div id="he"></div>
   <div id="dados">

      <Dados/>

   </div>

    <div id="results"></div>
  </div>
</template>

<script>
import Dados from './components/Dados'

export default {
 
  components: {
    Dados
  }
}
</script>

<style>
body {
  padding: 0%;
  margin: 0%;
  background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(0,255,166,1) 100%);
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 100%;


 
}
</style>
