<template>
  <div class="profile">
    <Header/>
    <Navprofile/>

    
     
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Navprofile from "@/components/Navprofile.vue";



export default {
  name: "Profile",
  components: {
    Header,
    Navprofile,
    
  },
};
</script>
<style>
@import url('../assets/styles/profile-page.css');
a{
  text-decoration: none;
}
</style>