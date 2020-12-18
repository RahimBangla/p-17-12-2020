<template>
  <div class="home shoos-container center grid">
    <div class="container">
      <div class="row row-cols-4">
        <div
          class="col-lg-3 col-sm-4 col-xs-6 text-center d-flex p-2 justify-content-center"
          :key="index"
          v-for="(card, index) in cards"
          vs-type="flex"
          vs-justify="center"
          vs-align="center"
          w="3"
          lg="3"
          sm="4"
          xs="12"
        >
          <Shoos
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
import Shoos from "@/components/Shoos.vue";

export default {
  name: "Home",
  components: {
    Shoos,
  },
  data: () => ({
    cards: [
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
        info:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
      },
      {
        title: "Where does it come from?",
        url: "https://vuesax.com/foto2.jpg",
        picture: "https://vuesax.com/foto2.jpg",
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
