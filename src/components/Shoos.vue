<template>
  <div>
    <vs-card type="4">
      <template #title>
        <a :href="url" class="href">
          <h3>{{ title }}</h3>
        </a>
      </template>
      <template #img>
        <img :src="picture" alt="" />
      </template>
      <template #text>
        <p>{{ info }}</p>
      </template>
      <template #interactions>
        <vs-button danger icon>
          <i class="bx bx-heart"></i>
        </vs-button>
        <vs-button class="btn-chat" shadow primary>
          <i class="bx bx-chat"></i>
          <span class="span"> 54 </span>
        </vs-button>
      </template>
    </vs-card>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
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
