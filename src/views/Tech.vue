<template>
  <div class="home">
    <v-parallax height="300px" dark :src="coverurl">
      <v-col align="center" justify="center">
        <v-col class="text-center cd-fixed-bg" cols="12">
          <h1 class="display-2 font-weight-bold mb-6 align-middle">
            {{ title }}
          </h1>
        </v-col>
      </v-col>
    </v-parallax>
    <Tech msg="Welcome to Your Vue.js App" />
    <Homeinfo />
  </div>
</template>

<script>
// @ is an alias to /src
import Tech from "@/components/Tech.vue";

export default {
  name: "Home",
  components: {
    Tech,
  },
  data: () => ({
    title: "ROCKY MTN RECREATION CENTER",
    coverurl:
      "http://christianjmcclellan.com/rockymtnrecreation/images/cd-background-4.jpg",
  }),
};
</script>

<style >
</style>
