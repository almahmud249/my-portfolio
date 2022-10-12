<template>
<v-app-bar height="100" app color="#0a192f" dark flat >
    <a class="ml-5">
        <v-img color="#3b958b" src="13.svg" max-width="50" max-height="50"></v-img>
    </a>
    <v-spacer></v-spacer>
    <ol class="justify-space-around d-flex text-center">
        <li class="menu-margin">
            <a text class="mr-6 ml-1 header-menu" @click="scroll('project')">About</a>
        </li>
        <li class="menu-margin">
            <a text class="mr-6 ml-1 header-menu" @click="scroll('project')">Experience</a>
        </li>
         <li class="menu-margin">
            <a text class="mr-6 ml-1 header-menu" @click="scroll('project')">Work</a>
        </li>
         <li class="menu-margin">
            <a text class="mr-6 ml-1 header-menu" @click="scroll('project')">Contact</a>
        </li>
    </ol>
  <v-btn class="ma-2 text-capitalize" href="mailto:almahmud.job49@gmail.com" target="_blank" outlined color="#60e6cb">
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
        }
    }
}
</script>

<style>
.header-menu {
    display: inline-block;
    text-decoration: none;
    text-decoration-skip-ink: auto;
    color: #a9b6c7 !important;
    position: relative;
    font-size: 14px;
    font-family: "SF Mono","Fira Code","Fira Mono","Roboto Mono",monospace;
    content: "0" counter(item) ".";
    transition: var(--transition);
}
.menu-margin{
    font-size: 13px;
    margin: 1rem;
    color: #60e6cb;
}
.menu-padding{
    padding:1.5rem;
}
a:hover.mr-6.ml-1.header-menu {
    color: #60e6cb !important;
}
</style>
