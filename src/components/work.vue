<template>
  <div id="work">
    <v-container style="width: 1100px; height: 500px" class="mb-lg-16">
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
        <v-col class="col-4">
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
                      href="https://yoori.spagreen.net/"
                      target="_blank"
                      text
                      class="text-sm-h6 header-menu text-ellipse-one"
                  >Yoori e-commerce CMS</a
                  >
                </v-card-title>
              </v-col>
              <a
                  href="https://yoori.spagreen.net/"
                  target="_blank"
                  class="header-menu"
              >
                <v-col class="col-3">
                  <v-card-title>
                    <v-icon
                        large
                        left
                        color="#60e6cb"
                    >
                      <!--                    mdi-folder-outline-->
                      mdi-file-link-outline
                    </v-icon>
                  </v-card-title>
                </v-col>
              </a>

            </v-row>

            <v-card-text>
              Yoori include features like customizable home page builder, best payment gateways, full admin control
              panel, full content management system, multiple seller management, and order tracking.
            </v-card-text>

            <v-card-actions>
              <v-list-item class="grow">
                <v-row
                    align="center"
                    justify="left"
                >
                  <v-col
                  >
                      <span><a
                      href="/details"
                      class="inline-link target-link mr-3 mb-5 see-more">Details</a>
                    </span>
                    <!--                  <span class="subheading mr-3 mb-5 target-link">See Details</span>-->
                  </v-col>
                  <v-col>
                    <span class="subheading mr-3">PHP</span>
                    <span class="subheading mr-3">Laravel</span>
                    <span class="subheading mr-3">Vue.js</span>
                  </v-col>

                </v-row>

              </v-list-item>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col class="col-4">
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
                      href="https://cryptocartrader.com/"
                      target="_blank"
                      text
                      class="text-sm-h6 mr-6 ml-1 header-menu text-ellipse-one"
                  >Crypto car trader</a
                  >
                </v-card-title>
              </v-col>
            </v-row>

            <v-card-text>
              This project build on laravel and modern javaScript framework vue.js 3. This project is scalable and write
              clean, modern and reliable code
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
                </v-row>
              </v-list-item>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col class="col-4">
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
                      href="https://thescrapapp.com/"
                      target="_blank"
                      text
                      class="text-sm-h6 mr-6 ml-1 header-menu text-ellipse-one"
                  >The scrap App</a
                  >
                </v-card-title>
              </v-col>
            </v-row>

            <v-card-text>
              This project build on laravel and modern javaScript framework vue.js 3. This project is scalable and write
              clean, modern and reliable code
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
                  <span class="subheading mr-3">Nuxt.js</span>
                </v-row>
              </v-list-item>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col class="col-4">
          <v-card
              class="mx-auto"
              color="#112240"
              dark
              max-width="550"
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
                      href="http://bppshop.com.bd/"
                      target="_blank"
                      text
                      class="text-sm-h6 mr-6 ml-1 header-menu text-ellipse-one"
                  >Bppshop</a
                  >
                </v-card-title>
              </v-col>
            </v-row>

            <v-card-text>
              This project build on laravel and modern javaScript framework vue.js 3. This project is scalable and write
              clean, modern and reliable code
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
                  <span class="subheading mr-3">Nuxt.js</span>
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
    return {};
  },
};
</script>
<style>
.see-more{
  font-size: 13px;
  color: #60e6cb!important;
}
</style>