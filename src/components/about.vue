<template>
  <div id="about">
  <v-container style="width: 1000px; height: 500px">
      <v-row>
        <v-col>
          <ol start="1" class="mb-n8">
            <li class="menu-margin mt-3 li-ordering">
              <a
                text
                class="mr-6 ml-1 header-menu mt-3 ordering"
                >About</a
              >
            </li>
          </ol>
          <v-divider class="grey darken-3 mt-8 mb-n4"></v-divider>
          <p class="eEjAsd mt-5">
            Hello! My name is al mahmud and I enjoy creating things that live on the internet.
            My interest in web development started back in 2016 when I decided to try editing custom
            Tumblr themes — turns out hacking together a custom reblog button taught me a lot about HTML & CSS!
          </p>
            <br>
          <p class="eEjAsd">
            Fast-forward to today, and I’ve had the privilege of working at
            <span>
                <a
                    href="https://spagreen.net/"
                    class="inline-link target-link"
                    rel="noopener noreferrer"
                    target="_blank"
                >Spagreen</a
                >
              </span>
          </p>
          <p class="eEjAsd">
            My main focus these days is provides both cutting edge solutions and legacy system maintenance and also write clean, modern, reliable code
          </p>
        </v-col>
        <v-col class="mt-16 ml-5" cols="4">
          <!-- <a class="ml-5">
            <v-img
            class=""
              color="#3b958b"
              src="me.jpg"
              max-width="400"
              max-height="300"
            ></v-img>
          </a> -->
          <template>
            <v-hover v-slot="{ hover }">
              <v-card
                :elevation="hover ? 12 : 0"
                :class="{ 'on-hover': hover }"
                rounded
                
              >
                <v-img
                  class="iTdkQf"
                  src="me.jpeg"
                  max-width="350"
                  max-height="250"
                ></v-img>
              </v-card>
            </v-hover>
          </template>
        </v-col>
      </v-row>
  </v-container>
  </div>
</template>
<script>
export default {
  data: () => ({
    icons: ["mdi-rewind", "mdi-play", "mdi-fast-forward"],
    items: [
      {
        title: "New Releases",
        text: `It's New Release Friday`,
        subtext: "Newly released songs. Updated daily.",
        img: "https://images.unsplash.com/photo-1429514513361-8fa32282fd5f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=3264&q=80",
      },
    ],
    transparent: "rgba(255, 255, 255, 0)",
  }),
};
</script>
<style scoped>

</style>