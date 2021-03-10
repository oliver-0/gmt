<template>
  <section class="hero is-info is-medium">
    <div class="hero-body">
      <div class="container">
        <div class="tile is-ancestor">
          <div class="tile is-5 is-vertical is-parent">
            <div class="tile is-child notification is-info">
              <h3 class="title">
                Level up your broadcasts
              </h3>
              <div class="content">
                <!-- <p>Hero banner text goes here</p> -->
                <div class="buttons">
                  <a class="button is-link is-inverted is-outlined" href="#details">
                    Find out more
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="tile is-parent">
            <div class="tile is-child box">
              probably a big composite image, thinking a fan shape with slices (a bracket screenshot, a shot of a LAN, a shot of someone commentating, etc)
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
};
</script>

<style lang="scss" scoped>
.title {
  font-style: italic;
  font-size: 2.9rem;
}
</style>
