<template>
  <div>
    <v-container style="width: 1100px; height: 500px">
      <ol start="3" class="mb-2">
        <li class="menu-margin mt-3 li-ordering">
          <a
              text
              class="mr-6 ml-1 header-menu mt-3 ordering"
              @click="scroll('project')"
          >Noteworthy Projects</a
          >
        </li>
      </ol>
      <v-divider class="grey darken-3 mb-4"></v-divider>
      <v-row class="mt-4">
        <v-col>
          <v-card
              class="mx-auto"
              color="#112240"
              dark
              max-width="350"
              max-height="400"
          >
           <v-row>
             <v-col class="col-3">
               <v-card-title>
                 <v-icon
                     large
                     left
                     color="#60e6cb"
                 >
                   mdi-folder-outline
                 </v-icon>
               </v-card-title>
             </v-col>
             <v-col>
               <v-card-title>
                 <a
                     href="https://yooriapi.spagreen.net/"
                     target="_blank"
                     text
                     class="text-sm-h6 mr-6 ml-1 header-menu text-ellipse-one"
                 >Yoori e-commerce CMS</a
                 >
               </v-card-title>
             </v-col>
           </v-row>

            <v-card-text>
              Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well.
            </v-card-text>

            <v-card-actions>
              <v-list-item class="grow">
                <v-row
                    align="center"
                    justify="end"
                >
                  <span class="subheading mr-3">PHP</span>
                  <span class="subheading mr-3">Laravel</span>
                  <span class="subheading mr-3">Vue.js</span>
                  <span class="subheading mr-3">jQuery</span>
                </v-row>
              </v-list-item>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card
              class="mx-auto"
              color="#112240"
              dark
              max-width="350"
              max-height="400"
          >
            <v-row>
              <v-col class="col-3">
                <v-card-title>
                  <v-icon
                      large
                      left
                      color="#60e6cb"
                  >
                    mdi-folder-outline
                  </v-icon>
                </v-card-title>
              </v-col>
              <v-col>
                <v-card-title>
                  <a
                      href="https://yooriapi.spagreen.net/"
                      target="_blank"
                      text
                      class="text-sm-h6 mr-6 ml-1 header-menu text-ellipse-one"
                  >Yoori e-commerce CMS</a
                  >
                </v-card-title>
              </v-col>
            </v-row>

            <v-card-text class="font-weight-bold">
              Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well.
            </v-card-text>

            <v-card-actions>
              <v-list-item class="grow">
                <v-row
                    align="center"
                    justify="end"
                >
                  <span class="subheading mr-3">PHP</span>
                  <span class="subheading mr-3">Laravel</span>
                  <span class="subheading mr-3">Vue.js</span>
                  <span class="subheading mr-3">jQuery</span>
                </v-row>
              </v-list-item>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card
              class="mx-auto"
              color="#112240"
              dark
              max-width="350"
              max-height="400"
          >
            <v-row>
              <v-col class="col-3">
                <v-card-title>
                  <v-icon
                      large
                      left
                      color="#60e6cb"
                  >
                    mdi-folder-outline
                  </v-icon>
                </v-card-title>
              </v-col>
              <v-col>
                <v-card-title>
                  <a
                      href="https://yooriapi.spagreen.net/"
                      target="_blank"
                      text
                      class="text-sm-h6 mr-6 ml-1 header-menu text-ellipse-one"
                  >Yoori e-commerce CMS</a
                  >
                </v-card-title>
              </v-col>
            </v-row>

            <v-card-text class="font-weight-bold">
              Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well.
            </v-card-text>

            <v-card-actions>
              <v-list-item class="grow">
                <v-row
                    align="center"
                    justify="end"
                >
                  <span class="subheading mr-3">PHP</span>
                  <span class="subheading mr-3">Laravel</span>
                  <span class="subheading mr-3">Vue.js</span>
                  <span class="subheading mr-3">jQuery</span>
                </v-row>
              </v-list-item>
            </v-card-actions>
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
.text-ellipse-one {
  display: -webkit-box !important;
  -webkit-line-clamp: 1;
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
}
.subheading{
  color: #6d819b !important;
  font-size: 15px;
  font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
}
</style>