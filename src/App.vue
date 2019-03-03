<template>
  <div id="app" class="container d-flex w-100 h-100 p-3 mx-auto flex-column">
    <SiteHeader />
    <router-view/>
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from "./components/Shared/SiteHeader.vue";
import SiteFooter from "./components/Shared/SiteFooter.vue";

export default {
  components: {
    SiteHeader,
    SiteFooter
  }
};
</script>


<style>
html,
body {
  height: 100%;
  background: linear-gradient(rgba(51, 51, 51, 0.9), rgba(51, 51, 51, 0.9)),
    url("./assets/j-434646-unsplash.jpg");
  background-attachment: fixed;
  background-size: cover;
}

body {
  display: -ms-flexbox;
  display: flex;
  color: #fff;
  text-shadow: 0 0.05rem 0.1rem rgba(0, 0, 0, 0.5);
  box-shadow: inset 0 0 5rem rgba(0, 0, 0, 0.5);
}

.cover-container {
  max-width: 42em;
}

.cover {
  padding: 0 1.5rem;
}

.cover .btn-lg {
  padding: 0.75rem 1.25rem;
  font-weight: 700;
}
</style>
