<template>
  <b-carousel pause-text="Paused">
    <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
      <section :class="`hero is-medium is-${carousel.color}`">
        <div class="hero-body has-text-centered">
          <h1 class="title">
            {{ carousel.text }}
          </h1>
        </div>
      </section>
    </b-carousel-item>
  </b-carousel>
</template>

<script>
export default {
  name: 'Carousel',
  data() {
    return {
      carousels: [
        { text: 'Slide 1', color: 'primary' },
        { text: 'Slide 2', color: 'link' },
        { text: 'Slide 3', color: 'info' },
      ],
      carouselsLong: [
        { text: 'Slide 1', color: 'primary' },
        { text: 'Slide 2', color: 'link' },
        { text: 'Slide 3', color: 'info' },
        { text: 'Slide 4', color: 'success' },
        { text: 'Slide 5', color: 'warning' },
        { text: 'Slide 6', color: 'danger' },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.carousel {
  text-align: center;
}
</style>
