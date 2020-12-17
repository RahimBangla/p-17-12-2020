<template>
  <div>
    <v-app>
      <Header />
      <v-main>
        <router-view />
      </v-main>
      <Footer />
    </v-app>
  </div>
</template>

<script>
import Header from "./components/layout/header";
import Footer from "./components/layout/footer";

export default {
  name: "App",

  components: {
    Header,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.v-main__wrap {
  background: #eff5f7;
  padding-top: 20px;
}
</style>
