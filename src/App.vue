<template>
  <div id="app">
   <div class="he"></div>
   <div id="dados">

      <Dados id="dados-in"/>
      <div id="protocol"></div>

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
  width: 100%;
  display: grid;

  grid-template-columns: 50% 50% ;
  grid-template-rows: 50px 600px;
  grid-template-areas: 
    "head head"
    "da re";
}

.he {
  grid-area: head;
}

#dados {
  grid-area: da;
}

#results {
  grid-area: re;
}


</style>
