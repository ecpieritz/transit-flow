<template>
    <nav class="tf-header__navbar">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About Us</router-link> |
      <router-link to="/services">Services</router-link> |
      <router-link to="/pricing">Pricing</router-link> |
      <router-link to="/team">Team</router-link> |
      <router-link to="/contact">Contact</router-link>
    </nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
  }
}
</script>

<style lang="scss">

</style>
