<template>
  <b-navbar fixed-top centered>
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        Brand
      </b-navbar-item>
    </template>
    <template #start>
      <b-navbar-item href="/">
        Link
      </b-navbar-item>
      <b-navbar-dropdown label="Dropdown">
        <b-navbar-item href="/">
          Item 1
        </b-navbar-item>
        <b-navbar-item href="/">
          Item 2
        </b-navbar-item>
      </b-navbar-dropdown>
    </template>

    <template #end>
      <b-navbar-item href="/">
        Home
      </b-navbar-item>
      <b-navbar-item href="portfolio">
        Portfolio
      </b-navbar-item>
      <b-navbar-item tag="div">
        <div class="buttons">
          <a class="button is-primary">
            <strong>Contact Us</strong>
          </a>
          <a class="button is-light">
            Do Something Else
          </a>
        </div>
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {
  name: 'TopNavbar',
};
</script>

<style lang="scss" scoped>

</style>
