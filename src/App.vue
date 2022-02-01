<script setup>
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import Navigation from './components/Navigation.vue'


</script>

<template>
   
   <Navigation></Navigation>
   <Main class=" flex-1"></Main>
   <Footer ></Footer>

</template>

<style>
#app{
  @apply min-h-screen flex flex-col font-poppins
}
</style>
