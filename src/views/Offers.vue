<template>
  <div class="offers">
    <Header/>
    <Canvasofertas/>
    
    
    
  </div>
  
</template>

<script>
import Header from '../components/Header.vue'
import Canvasofertas from '../components/Canvasofertas.vue'

export default{
  name: 'Offers',
  components:{
    Header,
    Canvasofertas,
    
    
    

  },
  data:()=>{
    return{
      home_page:false,
    }
  }
}
</script>

<style scoped>
.offers-text{
    color:orangered;
}

</style>