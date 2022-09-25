<template>
  <v-app id="home">
    <NavigationBar class="sticky-top" />
    <v-container fluid>
      <div class="head">
        <v-row>
          <v-col cols="5" id="home">
            <div
              style="position: relative"
              class="ms-14 further">
              <p class="text-grey" style="font-size: 16px">Hello, my name is</p>
              <h1 class="text-white closer" style="font-size: 120px">Max</h1>
              <p class="closer" style="font-size: calc(12px + 0.5vw)">
                - Software Engineer | Front end webdesign
              </p>
            </div>
          </v-col>
          <v-col cols="2">
            <div
              style="
                position: absolute;
                z-index: 100;
                bottom: 0;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;">
              <v-icon id="aboutMe">fas fa-angle-double-down</v-icon>
            </div>
          </v-col>
          <v-col cols="5">
            <div
              style="
                position: absolute;
                z-index: 100;
                bottom: 100px;
                margin-left: auto;
                margin-right: auto;
                text-align: justify;"
              class="mt-16 pr-16">
              <h4 style="font-size: calc(10px + 0.7vw)">
                I’m a software engineer based in Australia, specialising in
                building (and sometimes designing) exceptional website,
                applications and everything in between.
              </h4>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-col cols="12" class="mt-16">
        <div>
          <v-row>
            <v-col cols="12" sm="6">
              <div>
                <div>
                  <v-card href="https://vuejs.org/" target="_blank">
                    <v-img
                      src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg"
                      class="mx-auto"
                      width="80"/>
                  </v-card>
                </div>
                <div>
                  <v-card href="https://www.javascript.com" target="_blank">
                    <v-img
                      src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
                      class="mx-auto"
                      width="80"/>
                  </v-card>
                </div>
              </div>
            </v-col>
            <v-col cols="12" sm="6">
              <div style="position: relative" class="mt-16">
                <h4
                  class="px-10"
                  style="color: #004e92; font-size: 48px; line-height: 110%">
                  My current technology stack.
                </h4>
                <div class="px-14">
                  <p
                    style="
                      color: #004e92;
                      font-size: 24px;
                      font-weight: 500;
                      text-align: left;">
                    My stack focuses on blazing fast web design. Using modern
                    frameworks and libraries, combined with a fundamental
                    understanding of coding concepts and conventions.
                  </p>
                </div>
              </div>
              <br />
            </v-col>
          </v-row>
        </div>
      </v-col>
      <div class="portHead" id="projects">
        <div
          style="
            position: relative;
            text-align: center !important;
            z-index: 9999;
          "
          class="ms-14 further">
          <v-card elevation="10" height="120px" class="me-16">
            <v-card-text class="mt-9" style="font-size: 3vw">
              Project - This is where my project would go</v-card-text
            >
          </v-card>
        </div>
      </div>
      <div class="space">
        <div class="mt-8">
          <v-btn class="text-white" color="red" rounded>Show me more</v-btn>
          <h2 class="mt-3">
            A Brief description of my project -<span style="font-size: 18px">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras
              pretium lorem ut dui eleifend, facilisis scelerisque orci
              vulputate. Nam at gravida mauris. Proin eu erat ornare, dapibus
              enim in, ornare.</span>
          </h2>
        </div>
      </div>
      <div class="portHead">
        <div
          style="
            position: relative;
            text-align: center !important;
            z-index: 9999;
          "
          class="ms-14 further">
          <v-card elevation="10" height="120px" class="me-16">
            <v-card-text class="mt-9" style="font-size: 3vw">
              Project - This is where my project would go</v-card-text>
          </v-card>
        </div>
      </div>
      <div class="space">
        <div class="mt-8">
          <v-btn class="text-white" color="red" rounded>Show me more</v-btn>
          <h2 class="mt-3">
            A Brief description of my project -<span style="font-size: 18px">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras
              pretium lorem ut dui eleifend, facilisis scelerisque orci
              vulputate. Nam at gravida mauris. Proin eu erat ornare, dapibus
              enim in, ornare.</span>
          </h2>
        </div>
      </div>
      <div class="portHead">
        <div
          style="
            position: relative;
            text-align: center !important;
            z-index: 9999;
          "
          class="ms-14 further">
          <v-card elevation="10" height="120px" class="me-16">
            <v-card-text class="mt-9" style="font-size: 3vw">
              Project - This is where my project would go</v-card-text
            >
          </v-card>
        </div>
      </div>
      <div class="space">
        <div class="mt-8">
          <v-btn class="text-white" color="red" rounded>Show me more</v-btn>
          <h2 class="mt-3">
            A Brief description of my project -<span style="font-size: 18px">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras
              pretium lorem ut dui eleifend, facilisis scelerisque orci
              vulputate. Nam at gravida mauris. Proin eu erat ornare, dapibus
              enim in, ornare.</span>
          </h2>
        </div>
      </div>
      <v-col cols="12" sm="12" class="px-16" id="contact">
        <v-row>
          <v-col cols="12" sm="4" class="mt-8">
            <div>
              <h1>Contact</h1>
              <br />
              <p style="font-size: 20px; color: #004e92">
                maxdgreen@live.com.au
              </p>
              <br />
            </div>
          </v-col>
          <v-col cols="12" sm="8">
            <h1 class="mt-8">Get in touch</h1>
            <v-divider></v-divider>
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field label="Name" variant="outlined"></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Phone No"
                  variant="outlined">
                </v-text-field>
              </v-col>
            </v-row>
            <v-textarea 
              label="Message" 
              variant="outlined">
            </v-textarea>
            <v-btn color="red" class="mt-2">Submit Now</v-btn>
          </v-col>
        </v-row>
      </v-col>
    </v-container>
  </v-app>
</template>

<script>
import { defineComponent } from "vue";

// Components
import NavigationBar from "../components/NavigationBar.vue";

export default defineComponent({
  name: "HomeView",
  setup() {
    return {};
  },

  components: {
    NavigationBar,
  },
});
</script>
<style scoped>
.v-container {
  padding: 16px 0;
}
.gray {
  background-color: #ccc;
}
.gray-l {
  background-color: #ececec;
}
.head {
  position: relative;
  text-align: left;
  padding: 12px;
  margin-bottom: 6px;
  height: 500px;
  width: 100%;
  color: white;
  filter: drop-shadow(5px 1px 5px #000);
}
.head::before {
  content: " ";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: linear-gradient(
    0deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(0, 78, 146, 1) 100%
  );
  transform: skew(0deg, 3deg);
}
.head::after {
  content: " ";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: linear-gradient(
    0deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(0, 78, 146, 1) 100%
  );
  transform: skew(0deg, -3deg);
}
.portHead {
  position: relative;
  text-align: left;
  padding: 12px;
  margin-bottom: 6px;
  height: 350px;
  width: 100%;
  color: white;
  filter: drop-shadow(5px 1px 5px #000);
}
.portHead::before {
  content: " ";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: linear-gradient(
    0deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(0, 78, 146, 1) 100%
  );
  transform: skew(0deg, 3deg);
}
.portHead::after {
  content: " ";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: linear-gradient(
    0deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(0, 78, 146, 1) 100%
  );
  transform: skew(0deg, -3deg);
}
.space {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 300px;
  width: 100%;
  line-height: 150%
}
.closer {
  margin-top: -40px;
}
.further {
  margin-top: 100px;
}
</style>
