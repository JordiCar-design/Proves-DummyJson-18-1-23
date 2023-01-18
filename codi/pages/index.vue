<template>
  <div>
    <h1>Productes</h1>
  </div>
</template>

<script> 
export default {
data(){
  return{
    productes:null
  }
},
mounted(){
  this.descarregarProductes(
    let self = this
    this.$axios.get('https://dummyjson.com/docs/products?limit=2&')
  )
},
methods:{
  descarregarProductes(){
    this.$axios.get('htpps://https://dummyjson.com/docs/products')
    .then(

      resposta=>{
        console.log('resposta')
      }
    )
  }
},
.catch{

}

}
</script>
