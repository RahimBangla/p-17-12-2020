<template>
  <div class="home">
    <v-parallax dark :src="coverurl">
      <v-col align="center" justify="center">
        <br />
        <br />
        <br />
        <br />
        <v-col class="text-center cd-fixed-bg" cols="12">
          <h1 class="display-2 font-weight-bold mb-6">
            {{ title }}
          </h1>
        </v-col>
      </v-col>
    </v-parallax>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
  data: () => ({
    title: "ROCKY MTN RECREATION CENTER",
    coverurl:
      "http://christianjmcclellan.com/rockymtnrecreation/images/cd-background-4.jpg",
  }),
};
</script>

<style >
.cd-fixed-bg {
  padding-top: 50%;
}
.cd-fixed-bg h1,
.cd-fixed-bg h2 {
  position: absolute;
  left: 50%;
  top: 50%;
  bottom: auto;
  right: auto;
  -webkit-transform: translateX(-50%) translateY(-50%);
  -moz-transform: translateX(-50%) translateY(-50%);
  -ms-transform: translateX(-50%) translateY(-50%);
  -o-transform: translateX(-50%) translateY(-50%);
  transform: translateX(-50%) translateY(-50%);
  width: 90%;
  max-width: 1170px;
  text-align: center;
  font-size: 58px;
  font-weight: 200;
  text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.7);
  color: white;
}
</style>
