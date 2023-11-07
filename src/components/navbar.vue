<template>
  <v-app-bar height="100" app color="#0a192f" dark flat>
    <a class="ml-5" href="/">
      <v-img color="#3b958b" src="13.svg" max-width="50" max-height="50"></v-img>
    </a>
    <v-spacer></v-spacer>
    <ol class="justify-space-around d-flex text-center">
      <li class="menu-margin">
        <a text class="mr-6 ml-1 header-menu" @click="scroll('about')">About</a>
      </li>
      <li class="menu-margin">
        <a text class="mr-6 ml-1 header-menu" @click="scroll('experience')">Experience</a>
      </li>
      <li class="menu-margin">
        <a text class="mr-6 ml-1 header-menu" @click="scroll('work')">Work</a>
      </li>
      <li class="menu-margin">
        <a text class="mr-6 ml-1 header-menu" @click="scroll('contact')">Contact</a>
      </li>
    </ol>
    <v-btn class="ma-2 text-capitalize" @click="openPDF" href="mailto:almahmud.job49@gmail.com" target="_blank" outlined
           color="#60e6cb">
      Resume
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({
        behavior: "smooth"
      });
    },
    openPDF() {
      window.open('/resume.pdf', '_blank');
    }

  }
}
</script>

<style>

</style>
