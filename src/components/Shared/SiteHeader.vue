<template>
    <header class="masthead mb-auto">
      <div class="inner">
          <img
          src="../../assets/soup-bowl-white-60px.png"
          alt="Steaming bowl icon"
          class="float-left"
          />
          <router-link to="/">
          <h3 class="masthead-brand py-3 px-2 text-light">
            Esuna Noodles
          </h3>
          </router-link>
          <nav id="nav" class="nav nav-masthead justify-content-center">
              <router-link class="nav-link text-light" exact-active-class="exact-active" to="/">Home</router-link>
              <router-link class="nav-link text-light" exact-active-class="exact-active" to="/about">About</router-link>
              <router-link class="nav-link text-light" exact-active-class="exact-active" to="/menu">Menu</router-link>
              <router-link class="nav-link text-light" exact-active-class="exact-active" to="/contact">Contact</router-link>
          </nav>
      </div>
    </header>
</template>

<script>
export default {};
</script>


<style scoped>
.masthead {
  margin-bottom: 2rem;
}

.masthead-brand {
  margin-bottom: 0;
}

.nav-masthead .nav-link {
  padding: 0.25rem 0;
  font-weight: 700;
  color: rgba(255, 255, 255, 0.5);
  background-color: transparent;
  border-bottom: 0.25rem solid transparent;
}

.nav-masthead .nav-link:hover,
.nav-masthead .nav-link:focus {
  border-bottom-color: #fff;
}

.nav-masthead .nav-link + .nav-link {
  margin-left: 1rem;
}

.nav-masthead .exact-active {
  color: #fff;
  border-bottom-color: #fff;
}

@media (min-width: 48em) {
  .masthead-brand {
    float: left;
  }
  .nav-masthead {
    float: right;
  }
}
</style>
