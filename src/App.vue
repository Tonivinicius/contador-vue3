<script>

export default{
  data:() => ({
    contador: 10,
  }),
  methods:{
    incrementar() {
      this.contador++;
    },
    diminuir() {
      this.contador--;
    },
    resert(){
      this.contador = 10;
    }
  },
};
  
</script>
 

<template>
<!DOCTYPE html>
<html lang="Pt">
<head>

  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VueApp</title>

</head>
<body>
  <div class="container">
    
    <img src="./assets/logo.svg" alt="logo vue" width="125" height="125">
    
    <small>
      <h1>Olá Mundo Vue 3</h1>
    </small>
    
    <h2>Contador: {{contador}}</h2>
    <button @click="incrementar">+1</button>
    <button @click="diminuir">-1</button>
    <button @click="resert">Resert</button>
  
  </div>
  


</body>
</html>
</template>
