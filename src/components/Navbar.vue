<template>
  <nav class="tf-header__navbar">
    <div class="container">
      <router-link to="/">Home</router-link><span>|</span>
      <router-link to="/about">About Us</router-link><span>|</span>
      <router-link to="/services">Services</router-link><span>|</span>
      <router-link to="/pricing">Pricing</router-link><span>|</span>
      <router-link to="/team">Team</router-link><span>|</span>
      <router-link to="/contact">Contact</router-link>
    </div>
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
@import '@/styles.scss';

.tf-header {
  &__navbar {
    width: 100%;
    background-color: rgba(0, 0, 0, .2);
    padding: 30px 0;
    font-size: 18px;
    span{
      color: $tf-font-lg;
      margin: 0 10px;
    }
    
    a{
      color: $tf-font;
      text-decoration: none;
      &:hover{
        color: $tf-yellow;
      }
    }
  }
}
</style>
