<template>
  <section id="details" class="section">
    <div class="notification is-light">
      <div class="container">
        <div class="tile is-ancestor">
          <div class="tile is-4 is-parent">
            <div class="tile is-child notification is-light">
              <span class="material-icons large">
                live_tv
              </span>
              <h3 class="title medium">
                Live Broadcast Production Specialists
              </h3>
              <p>More information goes here</p>
            </div>
          </div>
          <div class="tile is-4 is-parent">
            <div class="tile is-child notification is-light">
              <span class="material-icons large">
                emoji_events
              </span>
              <h3 class="title">
                Expert Event Organisers
              </h3>
              <p>Commentary should probably occupy one of these top-row spots, actually</p>
            </div>
          </div>
          <div class="tile is-4 is-parent">
            <div class="tile is-child notification is-light">
              <span class="material-icons large">
                contact_support
              </span>
              <h3 class="title">
                We're here to help
              </h3>
              <p>We are also happy to coach your own broadcast talent, help source asset/video production, and share our first-hand experience in building communities from the ground up.</p>
            </div>
          </div>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-4 is-parent">
            <div class="tile is-child notification is-light">
              <span class="material-icons large">
                celebration
              </span>
              <h3 class="title">
                Release Showcases
              </h3>
              <p>Show off your a new game with a high-profile launch stream, or run a showmatch to celebrate a major patch release / update</p>
            </div>
          </div>
          <div class="tile is-4 is-parent">
            <div class="tile is-child notification is-light">
              <span class="material-icons large">
                sports_esports
              </span>
              <h3 class="title">
                video games
              </h3>
              <p>genuine e-hyphen-sports pedigree; the cream of the crop</p>
            </div>
          </div>
          <div class="tile is-4 is-parent">
            <div class="tile is-child notification is-light">
              <span class="material-icons large">
                kitesurfing
              </span>
              <h3 class="title">
                Kite Surfing!!!
              </h3>
              <p>Wow!!</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'DetailsSection',
};
</script>

<style lang="scss" scoped>
#details {
  padding-bottom: 0;
}
.tile {
  text-align: center;
  .title {
    font-size: 1.75rem;
  }
  .material-icons {
    &.large {
      font-size: 3rem;
    }
  }
}
</style>
