<template>
  <div class="about">
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import About from "@/components/About.vue";

export default {
  name: "about",
  components: {
    About,
  },
  data: () => ({
    title: "ROCKY MTN RECREATION CENTER",
    coverurl:
      "http://christianjmcclellan.com/rockymtnrecreation/images/cd-background-4.jpg",
  }),
};
</script>
<style>
.about {
  padding-top: 30px;
}
</style>
