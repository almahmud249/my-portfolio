<template>
  <div id="contact">
    <v-container style="width: 1100px; height: 500px">

      <v-row class="mt-4">
        <v-col>
          <v-card
              class="mx-auto text-center"
              color="basil"
              dark
              flat
              max-width="550"
          >
            <ol start="4" class="mb-2 center">
              <li class="menu-margin mt-3 li-ordering">
                <a
                    text
                    class="mr-6 ml-1 header-menu mt-3 ordering"
                    @click="scroll('project')"
                >What’s Next?</a
                >
              </li>
            </ol>
            <h1 class="text-h3 mt-n3 font-weight-bold">Get In Touch</h1>
            <v-card-text>
              Although currently i am looking for new opportunities, my inbox is always open. Whether you have a question or just want to say hi, I’ll try my best to get back to you!
            </v-card-text>
            <div class="mt-10">
              <v-btn class="ma-2 text-capitalize" href="mailto:almahmud.job49@gmail.com" target="_blank" outlined color="#60e6cb">
                Say Hello
              </v-btn>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
  data() {
    return {

    };
  },
};
</script>
<style>
.center {
  text-align: center;
  list-style-position: inside;
}
</style>