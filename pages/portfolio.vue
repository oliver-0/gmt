<template>
  <div>
    <TopNavbar />
    <section class="section">
      <div class="container">
        <div class="content">
          <h1>Portfolio Page</h1>
          <p>
            here is a list of content for your perusal: <br>
          </p>
        </div>
      </div>
      <div class="container">
        <div v-for="(item, itemIndex) in portfolio" :key="itemIndex" class="content">
          <article class="media">
            <figure class="media-left image is-640x360">
              <iframe
                class="has-ratio"
                width="640"
                height="360"
                :src="`${item.youtubeEmbed}`"
                frameborder="0"
                allowfullscreen
              />
            </figure>
            <div class="media-content">
              <div class="content">
                <h3>{{ item.title }}</h3>
                <p>
                  <nuxt-content :document="item" />
                </p>
              </div>
              <div class="level is-mobile">
                <div class="tags">
                  <div v-for="(tag, tagIndex) in item.tags" :key="tagIndex" class="tag">
                    {{ tag }}
                  </div>
                </div>
              </div>
            </div>
          </article>
          <!-- debug: -->
          <!-- <p>{{ item }}</p> -->
        </div>
      </div>
    </section>
    <Bottom />
  </div>
</template>

<script>
export default {
  name: 'PortfolioPage',
  data() {
    return {
      portfolio: [],
    };
  },
  async fetch() {
    this.portfolio = await this.$content('portfolio')
      .sortBy('createdAt', 'desc')
      .fetch();
  },
};
</script>

<style lang="scss" scoped>
.about {
  padding-bottom: 20px;
}
</style>
