<template>
  <section id="sign-off" class="section">
    <div class="tile is-ancestor">
      <div class="tile is-12 is-vertical is-parent">
        <div class="tile is-child notification is-primary sign-off-card">
          <h2 class="title">
            Up your game
          </h2>
          <button class="button is-primary is-inverted is-outlined">
            Get in touch
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SignOffCard',
};
</script>

<style lang="scss" scoped>
#sign-off {
  padding-top: 0;
}
.sign-off-card {
  border-top-left-radius: 0;
  border-top-right-radius: 0;
  text-align: center;
  clip-path: ellipse(75% 100% at center top);
  padding-top: 5em;
  padding-bottom: 4em;
  .title {
    font-style: italic;
    font-size: 2.4rem;
    margin-bottom: 2rem;
  }
}
</style>
