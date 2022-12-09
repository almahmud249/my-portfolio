<template>
  <div id="experience">
    <v-container style="width: 800px; height: 500px">
      <v-card color="basil" tile flat>
        <ol start="2" class="mb-2">
          <li class="menu-margin mt-3 li-ordering">
            <a
              text
              class="mr-6 ml-1 header-menu mt-3 ordering"

              >Where I’ve Worked</a
            >
          </li>
        </ol>
        <v-tabs v-model="tab" background-color="transparent" grow>
          <v-tab v-for="item in items" :key="item">
            {{ item }}
          </v-tab>
        </v-tabs>

        <v-tabs-items v-model="tab" class="mt-8 ml-8">
          <v-tab-item v-for="item in items" :key="item" class="basil">
            <h3 class="ml-5">
              <span style="color: #a9b6c7">Engineer</span>
              <span class="ml-1 mr-1 target-link">@</span>
              <span>
                <a
                  href="https://spagreen.net/"
                  class="inline-link target-link"
                  rel="noopener noreferrer"
                  target="_blank"
                  >Spagreen</a
                >
              </span>
            </h3>
            <v-card-text class="text-color ml-2 mt-n3"
              >Aug 2021 - Present</v-card-text
            >
            <div style="color: #7d87a4;font-size: 15px;" class="ml-4">
              <ul class="stl">
                <li >
                  Write modern, performant, maintainable code for a diverse
                  array of client and internal projects
                </li>
                <li>
                  Work with a variety of different languages, platforms,
                  frameworks, and content management systems such as JavaScript,
                  TypeScript, Gatsby, React, Craft, WordPress, Prismic, and
                  Netlify
                </li>
                <li>
                  Communicate with multi-disciplinary teams of engineers,
                  designers, producers, and clients on a daily basis
                </li>
              </ul>
            </div>
          </v-tab-item>
        </v-tabs-items>
      </v-card>
    </v-container>
  </div>
</template>
<script>
export default {
  data() {
    return {
      tab: null,
      items: ["Spagreen", "SoftIconic", "ExcelIt", "MyWork"],
      text: "",
    };
  },
};
</script>
<style>
/* Helper classes */

</style>