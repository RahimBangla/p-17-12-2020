<template>
  <div class="home">
    <v-parallax height="200px" dark :src="coverurl">
      <v-col align="center" justify="center">
        <v-col class="text-center cd-fixed-bg" cols="12">
          <h3 class="display-2 font-weight-bold mb-6">
            {{ title }}
          </h3>
        </v-col>
      </v-col>
    </v-parallax>
    <Tech />
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
    title: "Technology",
    coverurl: "/img/cd-background-1.jpg",
  }),
};
</script>

<style >
</style>
