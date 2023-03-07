<template>
  <div class="hero">
    <div class="hero__image-background">
      <img src="https://via.placeholder.com/1920x650" alt="">
    </div>
    <div class="hero__wrapper">
      <div class="hero__wrapper-content">
        <h1>Hello Developers!</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
