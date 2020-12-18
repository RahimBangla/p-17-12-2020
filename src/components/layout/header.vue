<template>
  <div class="center examplex">
    <vs-navbar center-collapsed v-model="active">
      <template #left>
        <img src="/img/logo_flat.png" alt="logo" style="width: 200px" />
      </template>
      <vs-navbar-item to="/" :active="active == 'home'" id="home">
        Home
      </vs-navbar-item>

      <vs-navbar-item
        to="/shoos"
        :active="active == 'components'"
        id="components"
      >
        Shoos
      </vs-navbar-item>
      <vs-navbar-item
        to="/technology"
        :active="active == 'license'"
        id="license"
      >
        Technology
      </vs-navbar-item>
      <vs-navbar-item to="/about" :active="active == 'about'" id="about">
        About
      </vs-navbar-item>
      <template #right>
        <vs-button flat>Login</vs-button>
        <vs-button>Get Started</vs-button>
      </template>
    </vs-navbar>
  </div>
</template>

  <script>
export default {
  data: () => ({
    active: "home",
    link: [
      { url: "/", name: "home", title: "Home" },
      { url: "/about", name: "about", title: "About" },
      { url: "", name: "", title: "" },
      { url: "", name: "", title: "" },
      { url: "", name: "", title: "" },
    ],
  }),
};
</script>