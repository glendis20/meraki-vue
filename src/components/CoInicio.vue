<template>
  <div class="hello">
    <h1 id="titulo">{{ msg }}</h1>
    <h4 id="tema">Bolsas y Empaques</h4>
    <p id="slogan">Cada centimetro hecho con amor</p>
  </div>
  
</template>

<script>
export default {
  name: 'hello',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

#titulo{
font-size: 80px;
}
#tema{
font-size: 30px;
}
#slogan{
font-size: 20px;
}
</style>
