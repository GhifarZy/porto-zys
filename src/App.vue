<template>
<div class="App">
    <!-- <Navbar /> -->
     <router-view/>
     <Footer />
</div>

</template>

<script>

import Footer from '@/components/Footer'
// import Navbar from '@/components/Navbar'
export default {  
  name: 'App',
  components:{
    Footer
  }
}
</script>

<style>

</style>

