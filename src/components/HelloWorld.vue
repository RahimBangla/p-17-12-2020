<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <h1 style="text-align: center">{{ title }}</h1>
        <p class="">
          <br />
          {{ description }}
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    title: "ROCKY MTN RECREATION CENTER",
    description: `Rocky Mtn Recreation provides a state-of-the-art recreation
          experience for residents with dozens of amenities for children,
          adults, seniors, and families. Spend a day at the indoor aquatic
          center, with a pool, slides, saunas, and a hot tub. Or come kick,
          lift, and dance your way to a workout at our fitness mezzanine while
          your kids play on the 4 basketball courts below. This world class
          facility includes 2 pools (one indoor, one outdoor), 3 basketball
          courts, an indoor running track, aerobic and weight equipment, fitness
          studios, child watch, concession stands, 5 racquetball courts, outdoor
          tennis courts, an outdoor playground and more. There is something for
          everyone to enjoy here at Rocky Mtn Recreation.`,
  }),
};
</script>
