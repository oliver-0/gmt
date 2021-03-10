<template>
  <div>
    <TopNavbar />
    <HeroSection />
    <IntroSection />
    <section class="section">
      <div class="container">
        <div class="content">
          Carousel, definitely a possibility
        </div>
      </div>
      <div class="container is-max-desktop">
        <Carousel />
      </div>
    </section>
    <DetailsSection />
    <Bottom />
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style lang="scss" scoped>
</style>
