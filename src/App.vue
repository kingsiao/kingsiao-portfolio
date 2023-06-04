<template>
  <div>
    <v-app-bar
      class="app-bar"
      color="#0a192f"
      height="90px"
      scroll-target="#scrolling-techniques-7"
      elevate-on-scroll
      fixed
    >
      <v-toolbar-title class="title-logo">KiSS</v-toolbar-title>
      
      <v-spacer></v-spacer>

      <v-btn
        href="#about"
        class="button"
        color="indigo"
        outlined
        dark
      >
        <span class="numbers">01.</span> About
      </v-btn>
      <v-btn
        href="#experience"
        class="button"
        color="indigo"
        outlined
        dark
      >
        <span class="numbers">02.</span> Experience
      </v-btn>
      <v-btn
        href="#projects"
        class="button"
        color="indigo"
        outlined
        dark
      >
        <span class="numbers">03.</span> Projects
      </v-btn>
      <v-btn
        href="#contact"
        class="button"
        color="indigo"
        outlined
        dark
      >
        <span class="numbers">04.</span> Contact
      </v-btn>
      <v-btn
        class="button"
        color="indigo"
        outlined
        dark
      >
        Resume
      </v-btn>
    </v-app-bar>

    <section id="main">
      <v-row>
        <div class="container">
          <div>
            <p class="paragraph">Hi, my name is</p>
            <br>
            <h2>King Solomon Siao.</h2>
            <h3>I build things for the web.</h3>
            <div class="subtitle">
              <p>
                I’m a software engineer specializing in building (and occasionally designing) exceptional digital experiences. Currently, I’m focused on building accessible, human-centered products at <span class="paragraph">Yondu Inc.</span>
              </p>
            </div>
          </div>
        </div>
      </v-row>
    </section>

    <section id="about">
      <v-row>
        <div class="container">
          <div class="title-container">
            <h2>
              <span class="section-number">01. </span>
              <span class="section-title">About Me</span>
            </h2>
          </div>
          <div class="subtitle">
            <p>
              Hello! My name is Brittany and I enjoy creating things that live on the internet. My interest in web development started back in 2012 when I decided to try editing custom Tumblr themes — turns out hacking together a custom reblog button taught me a lot about HTML & CSS!
            </p>
            <p :style="{'margin-top': '10px'}">
              Fast-forward to today, and I’ve had the privilege of working at an advertising agency, a start-up, a huge corporation, and a student-led design studio. My main focus these days is building accessible, inclusive products and digital experiences at Upstatement for a variety of clients.
            </p>
            <p :style="{'margin-top': '10px'}">
              I also recently launched a course that covers everything you need to build a web app with the Spotify API using Node & React.
            </p>
            <p :style="{'margin-top': '10px'}">
              Here are a few technologies I’ve been working with recently:
            </p>
          </div>
        </div>
      </v-row>
    </section>

    <section id="experience">
      <v-row>
        <div class="container">
          <div class="title-container">
            <h2>
              <span class="section-number">02. </span>
              <span class="section-title">Experience</span>
            </h2>
            <!-- <div class="section-line"></div> -->
          </div>
          <div>
            <v-tabs 
              dark
              background-color="#0a192f"
            >
              <v-tab class="tab-title">
                Yondu Inc.
              </v-tab>
              <!-- <v-tab class="tab-title">
                Scout
              </v-tab> -->

              <v-tab-item
                class="tab-items"
              >
                <v-card flat>
                  <v-card-text>
                    <h4>
                      <span 
                        :style="{
                          'color':'#fff',
                          'font-size': '20px'
                        }"
                      >
                        Jr. Software Engineer
                      </span>
                      <span 
                        :style="{
                          'color':'#64ffda',
                          'font-size': '20px',
                          'margin-bottom': '20px'
                        }"
                      > @ Yondu Inc.</span>
                    </h4>
                    <p 
                      :style="{
                        'color': '#797f9b',
                        'font-size': '18px',
                        'padding-bottom': '10px'
                      }"
                    >
                      August 2021 - Present
                    </p>
                    <ul 
                      :style="{
                        'color': '#797f9b',
                        'font-size': '16px'
                      }"
                    >
                      <li>
                        Assists in conversion of technical component design into a working back-end code and /or front-end code.
                      </li>
                      <li>
                        Delivers projects on time and budget consistently.
                      </li>
                      <li>
                        Applies generally accepted programming standards and techniques to assure efficient programming logic and data manipulation consistently.
                      </li>
                      <li>
                        Diagnose and resolve software problems quickly and efficiently.
                      </li>
                    </ul>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <!-- <v-tab-item
                class="tab-items"
              >
                <v-card flat>
                  <v-card-text>
                    <h4>
                      <span :style="{'color':'#fff'}">Engineer </span>
                      <span :style="{'color':'#64ffda'}">@ Upstatement</span>
                    </h4>
                    <p :style="{'color': '#797f9b'}">May 2018 - Present</p>
                    <ul :style="{'color': '#797f9b'}">
                      <li>
                        Write modern, performant, maintainable code for a diverse array of client and internal projects
                      </li>
                      <li>
                        Write modern, performant, maintainable code for a diverse array of client and internal projects
                      </li>
                      <li>
                        Communicate with multi-disciplinary teams of engineers, designers, producers, and clients on a daily basis
                      </li>
                    </ul>
                  </v-card-text>
                </v-card>
              </v-tab-item> -->
              
            </v-tabs>
          </div>
        </div>
      </v-row>
    </section>

    <section id="projects">
      <v-row>
        <div class="container">
          <div class="title-container">
            <h2>
              <span class="section-number">03. </span>
              <span class="section-title">Projects</span>
            </h2>
          </div>
          <div class="project-container">
            <v-col>
              <v-row>
                <v-card
                  class="mx-auto card"
                  width="300"
                  height="300"
                >
                  <div class="card-container">
                    <h4 class="card-title">LoadUp, GoCloud</h4>
                    <p class="card-paragraph">
                      Integrates web-based load distribution that automates bulk load distribution to your target recipients.
                    </p>
                    <ul 
                      :style="{
                        'font-size': '14px',
                        'list-style-type': 'none',
                        'font-weight': '300',
                        'display': 'flex',
                        'margin-top': '10px',
                        'color': '#a4b9fd'
                      }"
                    >
                      <li>Vue</li>
                      <li class="card-list-item">BootStrapVue</li>
                      <li class="card-list-item">Postman</li>
                    </ul>
                  </div>
                </v-card>
    
                <v-card
                  class="mx-auto card"
                  width="300"
                  height="300"
                >
                  <div class="card-container">
                    <h4 class="card-title">GoWifi</h4>
                    <p class="card-paragraph">
                      Designed and coded a public WIFI service website where users can connect their devices on WIFI networks available in community centers and other convergence areas that can be turned into WIFI hotspots.
                    </p>
                    <ul 
                      :style="{
                        'font-size': '14px',
                        'list-style-type': 'none',
                        'font-weight': '300',
                        'display': 'flex',
                        'margin-top': '10px',
                        'color': '#a4b9fd'
                      }"
                    >
                      <li>Vue</li>
                      <li class="card-list-item">JQuery</li>
                      <li class="card-list-item">Vuetify</li>
                      <li class="card-list-item">Postman</li>
                    </ul>
                  </div>
                </v-card>

                <v-card
                  class="mx-auto card"
                  width="300"
                  height="300"
                >
                  <div class="card-container">
                    <h4 class="card-title">TMBayan</h4>
                    <p class="card-paragraph">
                      Designed and coded a public WIFI service website where users can connect their devices on WIFI networks available in community centers and other convergence areas that can be turned into WIFI hotspots.
                    </p>
                    <ul 
                      :style="{
                        'font-size': '14px',
                        'list-style-type': 'none',
                        'font-weight': '300',
                        'display': 'flex',
                        'margin-top': '10px',
                        'color': '#a4b9fd'
                      }"
                    >
                      <li>Vue</li>
                      <li class="card-list-item">JQuery</li>
                      <li class="card-list-item">Vuetify</li>
                      <li class="card-list-item">Postman</li>
                    </ul>
                  </div>
                </v-card>

                <v-card
                  class="mx-auto card"
                  width="300"
                  height="300"
                >
                  <div class="card-container">
                    <h4 class="card-title">LCC</h4>
                    <p class="card-paragraph">
                      Designed and coded an ecommerce website where you can buy physical goods online. Implement LCC EStore using Vessell CMS to create attractive and user-friendly ecommerce website.

                    </p>
                    <ul 
                      :style="{
                        'font-size': '14px',
                        'list-style-type': 'none',
                        'font-weight': '300',
                        'display': 'flex',
                        'margin-top': '10px',
                        'color': '#a4b9fd'
                      }"
                    >
                      <li>Vue</li>
                      <li class="card-list-item">Vessell CMS</li>
                      <li class="card-list-item">Vuetify</li>
                      <li class="card-list-item">Postman</li>
                    </ul>
                  </div>
                </v-card>
                
                <v-card
                  class="mx-auto card"
                  width="300"
                  height="300"
                >
                  <div class="card-container">
                    <h4 class="card-title">Vessell CMS</h4>
                    <p class="card-paragraph">
                      Designed and coded Content Management System (CMS) website where you can design and develop your website and to manage all contents to your website.
                    </p>
                    <ul 
                      :style="{
                        'font-size': '14px',
                        'list-style-type': 'none',
                        'font-weight': '300',
                        'display': 'flex',
                        'margin-top': '10px',
                        'color': '#a4b9fd'
                      }"
                    >
                      <li>Vue</li>
                      <li class="card-list-item">Vuetify</li>
                      <li class="card-list-item">Postman</li>
                    </ul>
                  </div>
                </v-card>

                <v-card
                  class="mx-auto card"
                  width="300"
                  height="300"
                >
                  <div class="card-container">
                    <h4 class="card-title">Rex EStore</h4>
                    <p class="card-paragraph">
                      Designed and coded an ecommerce website where you can search and purchase needed reference material online.
                    </p>
                    <ul 
                      :style="{
                        'font-size': '14px',
                        'list-style-type': 'none',
                        'font-weight': '300',
                        'display': 'flex',
                        'margin-top': '10px',
                        'color': '#a4b9fd'
                      }"
                    >
                      <li>Vue</li>
                      <li class="card-list-item">Vuetify</li>
                      <li class="card-list-item">Postman</li>
                    </ul>
                  </div>
                </v-card>
              </v-row>
            </v-col>

            
          </div>
        </div>
      </v-row>
    </section>
  </div>
</template>

<script>

export default {
  name: 'App',

  components: {},

  data: () => ({}),
};
</script>

<style lang="scss" scoped>
.button {
  margin-left: 10px;
  text-transform: unset;
}
.numbers {
  color: #64ffda;
}
.title-logo {
  color: #fff;
}
.app-bar {
  padding: 0 30px 0 30px;
}
#main {
  padding-top: 100px;
  margin-top: 90px;
}
#about,
#work {
  padding-top: 120px;
}
#main,
#about,
#experience,
#projects {
  background-color: #0a192f;
}
.paragraph {
  color: #64ffda;
  font-family: "Roboto Mono", monospace;
  font-size: 16px;
  line-height: 17.6px;
}
h2 {
  font-size: 70px;
  color: #ccd6f6;
}
h3 {
  color:#8892b0;
  font-size: 70px;
  font-family: "apple-system", system-ui, sans-serif;
}
.subtitle {
  width: 600px;
  letter-spacing: normal;
  line-height: 30px;
  font-size: 15px;
  margin-top: 20px;
  color:#8892b0;
  font-family: "apple-system", system-ui, sans-serif;
  font-weight: 500 !important;
}
.container {
  margin: 0 15rem 0 15rem;
}
.card-container {
  padding: 30px;
  font-family: "apple-system", system-ui, sans-serif;
  color: #ccd6f6;
}
.card-title {
  font-size: 22px;
  font-weight: 700;
  letter-spacing: normal;
  padding-bottom: 5px;
}
.card-paragraph {
  font-size: 16px !important;
  font-weight: 300;
  font-size: 18px;
  padding-bottom: 5px;
  text-align: left;
  text-justify: distribute !important;
  text-align-last: left !important;
}
.card-list-item {
  margin-left: 15px;
}
.section-number {
  font-family: "Roboto Mono", monospace;
  color: #64ffda;
  font-size: 30px;
  font-weight: 300;
}
.section-title {
  color: #ccd6f6;
  font-family: "apple-system", system-ui, sans-serif;
  font-size: 35px;
  font-weight: 700;
}
.card {
  background-color: #112240;
  margin-left: 10px;
  margin-bottom: 20px;
}
.v-card.v-card--flat.v-sheet.theme--light {
  background-color: #0a192f;
  border-radius: 0px;
  border: 0px !important;
}
::v-deep .v-tabs-slider,
::v-deep .v-tabs-slider-wrapper {
  background-color: #64ffda !important;
  color: #64ffda !important;
}
::v-deep .v-window-item.tab-items {
  border-bottom: 0px;
  border-left: 0px !important;
}
.v-tab.v-tab--active {
  color: #64ffda !important;
  font-size: 18px !important;
}
::v-deep .tab-title {
  text-transform: unset !important;
}
</style>