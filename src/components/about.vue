<template>
  <v-container style="width: 1000px; height: 500px">
    <div>
      <v-row>
        <v-col>
          <ol start="1" class="mb-n8">
            <li class="menu-margin mt-3 li-ordering">
              <a
                text
                class="mr-6 ml-1 header-menu mt-3 ordering"
                @click="scroll('project')"
                >About</a
              >
            </li>
          </ol>
          <v-divider class="grey darken-3 mt-8 mb-n4"></v-divider>
          <p class="eEjAsd mt-5">
            the internet. My interest in web development started back in 2012
            when I decided to try editing custom Tumblr themes — turns out
            hacking together a custom reblog button taught me a lot about HTML &
            CSS! Fast-forward to today, and I’ve had the privilege of working at
            an advertising agency, a start-up, a huge corporation, and a
            student-led design studio. My main focus these days is building
            accessible, inclusive products and digital experiences at
            Upstatement for a variety of clients. I also recently launched a
            course that covers everything you need to build a web app with the
            Spotify API using Node & React. Here are a few technologies I’ve
            been working with recently:
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
                :elevation="hover ? 12 : 10"
                :class="{ 'on-hover': hover }"
                rounded
                
              >
                <v-img
                  class="iTdkQf"
                  src="me.jpg"
                  max-width="350"
                  max-height="250"
                ></v-img>
              </v-card>
            </v-hover>
          </template>
        </v-col>
      </v-row>
    </div>
  </v-container>
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
.ordering {
  font-size: 30px;
}
li.menu-margin.mt-3.li-ordering {
  font-size: 20px;
}
.v-card {
  transition: opacity 0.4s ease-in-out;
}

.v-card:not(.on-hover) {
  opacity: 0.6;
}
.theme--light.v-sheet {
  /* background-color: #FFFFFF; */
  border-color: #ffffff;
  color: rgba(0, 0, 0, 0.87);
}
.iTdkQf {
  position: relative;
  border-radius: var(--border-radius);
  /* mix-blend-mode: multiply; */
  /* filter: grayscale(100%) contrast(1); */
  transition: var(--transition);
}
</style>