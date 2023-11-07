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
          <v-tab v-for="(item,i) in items" :key="i">
            {{ item.name }}
          </v-tab>
        </v-tabs>

        <v-tabs-items v-model="tab" class="mt-8 ml-8">
          <v-tab-item v-for="(item,x ) in items" :key="x" class="basil">
            <h3 class="ml-5">
              <span style="color: #a9b6c7">Engineer</span>
              <span class="ml-1 mr-1 target-link">@</span>
              <span>
                <a
                    :href="item.url"
                    class="inline-link target-link"
                    rel="noopener noreferrer"
                    target="_blank"
                >{{ item.name }}</a
                >
              </span>
            </h3>
            <v-card-text class="text-color ml-2 mt-n3"
            > {{ item.date }}
            </v-card-text
            >
            <div style="color: #7d87a4;font-size: 15px;" class="ml-4">
              <ul class="stl">
                <li v-for="(list,index) in item.para" :key="index">
                  {{ list }}
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
      items: [
        {
          name: "SoftIconic",
          para: {
            0: "Softiconic provide dynamic execution and unique IT solutions to our prestigious clients worldwide and make a profound dedication to the success of our clients",
            1: "Write modern, performant, maintainable code for a diverse\n" + "array of client and internal projects",
            2: "Work with a variety of different languages, platforms,\n" + "frameworks, and content management systems such as JavaScript,\n" + "TypeScript, Gatsby, React, Craft, WordPress, Prismic, and\n" + "Netlify",
            3: "Communicate with multi-disciplinary teams of engineers,\n" + "designers, producers, and clients on a daily basis",
          },
          date: "Mar 2020 - Nov 2020",
          url:"https://www.softiconic.com/"
        },
        {
          name: "Spagreen",
          para: {
            0: "SpaGreen Creative is the company that work codecanyone based project. A team who have vast expertise\n" +
                "to build custom software and help organizations to scale and achieve a competitive advantage by,\n" + "providing powerful and adaptable web and mobile solutions that meet the ultimate need of the clients worldwide",
            1: "Write modern, performant, maintainable code for a diverse\n" + "array of client and internal projects",
            2: "Work with a variety of different languages, platforms,\n" + "frameworks, and content management systems such as JavaScript,\n" + "TypeScript, Gatsby, React, Craft, WordPress, Prismic, and\n" + "Netlify",
            3: "Communicate with multi-disciplinary teams of engineers,\n" + "designers, producers, and clients on a daily basis",
          },
          date: "Dec 2020 - Dec 2022",
          url:"https://spagreen.net/"
        },
        {
          name: "ExcelIt",
          para: {
            0: "Deliver high-quality, robust production code for a diverse array of projects for clients\n" +
                "including API Development, Work with Mobile App Team, Customized Application Development, School Management System, e-commerce solutions, etc",
            1: "Lead Team with 4 members of Junior Developer",
            3: "Maintain and develop E-commerce application Bppshop",
          },
          date: "Jan 2023 - Present",
          url:"https://www.excelitai.com/web/"
        },
      ],
      text: "",
    };
  },
};
</script>
<style>
/* Helper classes */

</style>