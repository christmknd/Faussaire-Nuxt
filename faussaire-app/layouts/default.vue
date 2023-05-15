
<script>
import Navbar from '../components/Navbar.vue'
export default {
    components: {Navbar}
}
</script>

<template>
    <div>
      <body>
        <Navbar/>
      <slot/>
      </body>
    </div>
  </template>
  

<style>

</style>