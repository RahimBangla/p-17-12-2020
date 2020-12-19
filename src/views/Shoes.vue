<template>
  <div class="home shoos-container center grid">
    <div class="container">
      <div class="row thumbnail_align">
        <div
          class="col-lg-3 col-sm-4 col-xs-6 col-6"
          :key="index"
          v-for="(card, index) in cards"
        >
          <Shoes
            :title="card.title"
            :url="card.url"
            :picture="card.picture"
            :info="card.info"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Shoes from "@/components/Shoes.vue";

export default {
  name: "Home",
  components: {
    Shoes,
  },
  data: () => ({
    cards: [
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Coming Soon..",
        url: "/img/demo.jpg",
        picture: "/img/demo.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
    ],
  }),
};
</script>

<style >
.shoos-container {
  padding: 40px 0px 20px 0px;
}
</style>
