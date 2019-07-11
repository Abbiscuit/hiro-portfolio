<template>
  <div class="header-container">
    <header class="app-header">
      <AppSideNavToggle @toggle="$emit('sidenavToggle')" />
      <div class="logo">
        <nuxt-link to="/">Hiro's</nuxt-link>
      </div>
      <div class="spacer"></div>
      <div class="navigation-items">
        <ul class="nav-list">
          <li class="nav-item">
            <nuxt-link to="/contact">Contact</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/about">About</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/services">Services</nuxt-link>
          </li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
import AppSideNavToggle from "@/components/Navigation/AppSideNavToggle";

export default {
  name: "AppHeader",
  components: {
    AppSideNavToggle
  }
};
</script>

<style scoped>
.header-container {
  height: 60px;
}

.app-header {
  width: 100%;
  position: fixed;
  height: 60px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background: rgb(255, 255, 255);
  box-shadow: 0px 0px 3px #ccc;
  z-index: 100;
  box-sizing: border-box;
  padding: 0 20px;
}

.logo a {
  text-decoration: none;
  color: black;
  font-size: 0.9em;
}

.logo,
.nav-item a {
  padding: 1rem 2rem;
  display: block;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: bold;
  color: black;
  font-size: 1rem;
}

.spacer {
  flex: 1;
}

.navigation-items {
  display: none;
}

@media (min-width: 768px) {
  .navigation-items {
    display: block;
  }
}

.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}

.nav-item {
  margin: 0 10px;
}

.nav-item a {
  text-decoration: none;
  color: black;
}

.nav-item a:hover,
.nav-item a:active,
.nav-item a.nuxt-link-active {
  color: rgb(252, 101, 81);
}
</style>
