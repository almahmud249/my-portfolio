<template>
<v-container class="line-mrg">
    <p style="color:#60e6cb" class="ml-3">Hi, my name is</p>
    <h2 class="big-heading mt-3">Al Mahmud.</h2>
    <h5 class="big-heading mt-3">I build things for the web.</h5>
    <div class="mt-5">
        <p class="eEjAsd mt-5">Hello! My name is al mahmud and I enjoy creating things that live on the internet. My interest in web development started back in 2016 when I decided to try editing custom Tumblr themes — turns out hacking together a custom reblog button taught me a lot about HTML & CSS!
<!--          <a href="https://upstatement.com/" target="_blank" rel="noreferrer">Upstatement</a>.-->
        </p>
    </div>
    <div class="mt-10">
        <v-btn class="ma-2 text-capitalize" href="mailto:almahmud.job49@gmail.com" target="_blank" outlined color="#60e6cb">

            Say Hello
        </v-btn>
    </div>
</v-container>  
</template>

<style>
.line-mrg {
    width: 1100px !important;
    height: 600px !important;
    line-height: 10px !important;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
}

.big-heading {
    font-size: clamp(40px, 8vw, 60px);
}

h2.big-heading.mt-3 {
    margin-top: 60px !important;
    color: #ccd6f6;
}

h5.big-heading.mt-3 {
    margin-top: 60px !important;
    color: #8892b0;
}

p.eEjAsd.mt-5 {
    margin-top: 46px !important;
    max-width: 540px !important;
    font-size: 17px;
    color: #8892b0;
    line-height: normal;
}
</style>
