<template>
  <div class="center examplex">
    <vs-navbar center-collapsed v-model="active">
      <template #left>
        <a href="/">
          <img
            src="/img/logo_flat.png"
            alt="logo"
            class="d-none d-sm-block"
            style="width: 200px"
          />
          <img
            src="/img/logo.png"
            alt="logo"
            class="d-sm-none"
            style="width: 70px"
          />
        </a>
      </template>
      <template #right>
        <vs-navbar-item to="/" :active="active == 'Home'" id="Home">
          Home
        </vs-navbar-item>

        <vs-navbar-item to="/shoes" :active="active == 'Shoes'" id="Shoes">
          Shoes
        </vs-navbar-item>
        <vs-navbar-item to="/technology" :active="active == 'Tech'" id="Tech">
          Technology
        </vs-navbar-item>
        <vs-navbar-item to="/about" :active="active == 'About'" id="About">
          About
        </vs-navbar-item>
      </template>
    </vs-navbar>
  </div>
</template>

  <script>
export default {
  data: () => ({
    active: "",
  }),
  created() {
    // async () => {
    //   this.active = this.$route.name;
    //   console.log(this.active);
    // };
  },
};
</script>

<style>
</style>