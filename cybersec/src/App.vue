<template>
  <div id="app">
    <Navbar
      name="Logo"
      :navLinks="[
        {
          name: 'Inicio',
          link: '/home',
          dropdown: false,
        },
        { name: '1980', 
        link: '/1980', 
        dropdown: false },

        { name: '1990', 
        link: '/1990', 
        dropdown: false },

        { name: '2000', 
        link: '/2000', 
        dropdown: false },

        { name: 'Fim', 
        link: '/Fim', 
        dropdown: false },

       
      ]"
    />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'App',
  components: {
    Navbar,
  },
}
</script>

<style>

body{
  overflow-x: hidden;
  background-color: #000000;
  
}

</style>