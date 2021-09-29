<template>
  <div class="services">
    <Header/>
    <Canvas/>
    <Footer/>
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Canvas from '../components/Canvas.vue'
import Footer from '../components/Footer.vue'
export default{
  name: 'Services',
  components:{
    Header,
    Canvas,
    Footer,

  }
}
</script>
