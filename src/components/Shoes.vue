<template>
  <div>
    <vs-card type="2">
      <template #title>
        <h3>{{ title }}</h3>
      </template>
      <template #img>
        <img :src="picture" :alt="title" style="height=100px" />
      </template>
      <template #text>
        <p>
          {{ info }}
        </p>
      </template>
      <template #interactions>
        <vs-button danger icon>
          <i class="bx bx-heart"></i>
        </vs-button>
        <vs-button class="btn-chat" shadow primary>
          <i class="bx bx-chat"></i>
          <span class="span"> 54$ </span>
        </vs-button>
      </template>
    </vs-card>
  </div>
</template>

<script>
export default {
  name: "shoes",
  props: {
    title: String,
    url: String,
    info: String,
    picture: String,
  },

  data: () => ({}),
};
</script>

<style>
a:link {
  text-decoration: none;
}
</style>
