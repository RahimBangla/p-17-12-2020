<template>
  <div class="container">
    <div class="row">
      <div class="col-12 text-center">
        <h2>About Us</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <v-img
          contain
          lazy-src="https://picsum.photos/id/11/10/6"
          max-height="300"
          max-width="500"
          :src="info1.photo"
        ></v-img>
      </div>
      <div class="col-sm-8">
        <div class="col-12 text-center">
          <h3>Description</h3>
        </div>
        <p class="text-left">{{ info1.description }}</p>
      </div>
    </div>
    <div class="row">
      <div class="col-6 col-md-2">
        <img class="techpic" :src="info2.photo" alt="Avatar" />
      </div>
      <div class="col-md-10 align-middle">
        <p class="align-middle techtext">
          {{ info2.description }}
        </p>
      </div>
    </div>
    <div class="row clearfix">
      <div class="col-12 col-md-2 float-end">
        <img class="techpic" :src="info3.photo" alt="Avatar" />
      </div>
      <div class="col-md-10 float-start">
        <p class="align-middle techtext">
          {{ info3.description }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "about",
  components: {},
  data: () => ({
    info1: {
      photo: "/img/about.jpg",
      description: `Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged.
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. `,
    },
    info2: {
      photo: "/img/demo.jpg",
      description: `Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. It was popularised in the 1960s
            with the release of Letraset sheets containing Lorem Ipsum passages,
            and more recently with desktop publishing software like Aldus
            PageMaker including versions of Lorem Ipsum.`,
    },
    info3: {
      photo: "/img/demo.jpg",
      description: `Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. It was popularised in the 1960s
            with the release of Letraset sheets containing Lorem Ipsum passages,
            and more recently with desktop publishing software like Aldus
            PageMaker including versions of Lorem Ipsum.`,
    },
  }),
};
</script>

<style>
.techpic {
  border-radius: 50%;
  height: 150px;
  padding: 5px;
}
.techtext {
  padding: 40px;
}
</style>