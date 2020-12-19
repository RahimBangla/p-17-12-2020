<template>
  <div class="container">
    <div class="row">
      <div class="col-12 text-center">
        <h2>Title Here</h2>
      </div>
    </div>
    <div class="row d-flex p-2 justify-content-center">
      <div class="col col-md-2 thumbnail_align">
        <img class="techpic" :src="info1.photo" alt="Avatar" />
      </div>
      <div class="col-md-10 align-middle">
        <p class="align-middle techtext">
          {{ info1.description }}
        </p>
      </div>
    </div>
    <div class="row clearfix d-flex p-2 justify-content-center">
      <div class="col col-md-2 thumbnail_align">
        <img class="techpic" :src="info2.photo" alt="Avatar" />
      </div>
      <div class="col-md-10 float-start">
        <p class="align-middle techtext">
          {{ info2.description }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "Home",
  components: {},
  data: () => ({
    info1: {
      photo: "/img/demo.jpg",
      description: `Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book. It has survived not only
          five centuries, but also the leap into electronic typesetting,
          remaining essentially unchanged. It was popularised in the 1960s with
          the release of Letraset sheets containing Lorem Ipsum passages, and
          more recently with desktop publishing software like Aldus PageMaker
          including versions of Lorem Ipsum.`,
    },
    info2: {
      photo: "/img/demo.jpg",
      description: `Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book. It has survived not only
          five centuries, but also the leap into electronic typesetting,
          remaining essentially unchanged. It was popularised in the 1960s with
          the release of Letraset sheets containing Lorem Ipsum passages, and
          more recently with desktop publishing software like Aldus PageMaker
          including versions of Lorem Ipsum.`,
    },
  }),
};
</script>

<style>
.techpic {
  border-radius: 50%;
  height: 200px;
  padding: 5px;
}
.techtext {
  padding: 40px;
}
</style>