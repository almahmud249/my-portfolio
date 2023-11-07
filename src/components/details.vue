<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <v-container style="width: 1100px; height: 500px" class="mb-lg-16">
      <navbar/>
      <v-card :style="{ background: $vuetify.theme.themes.dark.background }"
              class="mx-auto"
      >
        <v-row dense>
          <v-col
              v-for="(card,i) in cards"
              :key="i"
              :cols="card.flex"
              :align="i === 1 || i === 2 ? 'center' : ''"
          >
            <v-card
                :max-width="i === 1 || i === 2 ? '400' : ''"
            >
              <v-img
                  :src="card.src"
                  class="align-end"
                  gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                  height="400px"
                  cover
              >
              </v-img>
              <v-carousel
                  v-if="i===0"
                  cycle
                  height="400"
              >
                <v-carousel-item
                    v-for="(slide, i) in slides"
                    :key="i"
                >
                  <v-sheet
                      :color="colors[i]"
                      height="100%"
                  >
                    <div class="d-flex fill-height justify-center align-center">
                      <div class="text-h2">
                        {{ slide }} Slide
                      </div>
                    </div>
                  </v-sheet>
                </v-carousel-item>
              </v-carousel>
            </v-card>
          </v-col>
        </v-row>
      </v-card>
      <bottom/>
    </v-container>
  </v-app>

</template>

<script>
import navbar from "@/components/navbar.vue";
import bottom from "@/components/bottom-line.vue";

export default {
  name: "details",
  data: () => ({
    cards: [
      {title: 'Pre-fab homes', src: 'http://178.18.243.168/assets/img/baby-sitter.jpg', flex: 12},
      {title: 'Favorite road trips', src: '', flex: 6},
      {title: 'Best airlines', src: '', flex: 6},
    ],
    colors: [
      'indigo',
      'warning',
      'pink darken-2',
      'red lighten-1',
      'deep-purple accent-4',
    ],
    slides: [
      'First',
      'Second',
      'Third',
      'Fourth',
      'Fifth',
    ],
  }),
  components: {
    navbar,
    bottom
  },
}
</script>

<style scoped>

</style>