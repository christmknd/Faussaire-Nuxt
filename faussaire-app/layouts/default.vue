
<script>
import Navbar from '../components/layout/Navbar.vue'
export default {
    components: {Navbar}
}
</script>

<template>
    <div>
      <Navbar/>
      <slot/>
    </div>
  </template>
  

<style>

</style>