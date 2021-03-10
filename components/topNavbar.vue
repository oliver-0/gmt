<template>
  <b-navbar fixed-top centered wrapper-class="container" :shadow="false">
    <template #brand>
      <b-navbar-item tag="div">
        <img
          id="template-logo"
          src="@/assets/images/template-logo-small.png"
          alt="Stimpack Live - the premier gaming broadcast consultancy"
        >
      </b-navbar-item>
    </template>
    <template #start>
      <b-navbar-item href="/">
        Home
      </b-navbar-item>
      <b-navbar-item href="/portfolio">
        Portfolio
      </b-navbar-item>
      <b-navbar-item href="/about">
        About Us
      </b-navbar-item>
      <!-- <b-navbar-dropdown label="Dropdown">
        <b-navbar-item href="/">
          Item 1
        </b-navbar-item>
        <b-navbar-item href="/">
          Item 2
        </b-navbar-item>
      </b-navbar-dropdown> -->
    </template>

    <template #end>
      <!-- <b-navbar-item href="/">
        Right item
      </b-navbar-item> -->
      <b-navbar-item tag="div">
        <div class="buttons">
          <a class="button is-link">
            <!-- <strong>Contact Us</strong> -->
            Contact Us
          </a>
          <!-- <a class="button is-light">
            Do Something Else
          </a> -->
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
.navbar-item img {
  max-height: 3rem;
}
</style>
