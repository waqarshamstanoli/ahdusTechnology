<template>
  <v-app light>
    <v-app-bar
      :clipped-left="clipped"
      fixed
      color="white"
    >
     

    
      <v-app-bar-nav-icon @click="drawer = true" class="hidden-md-and-up"></v-app-bar-nav-icon>
<nuxt-link to="/">
        <v-toolbar-title link @click="changeRoute()">
          <img
            :src="require('../assets/logo.png')"
            width="150"
            class="mt-2 ml-5"
            lazy-load
          />
        </v-toolbar-title>
      </nuxt-link>

<v-toolbar class="hidden-sm-and-down elevation-0" color="transparent">

   
      <v-spacer></v-spacer>
        
      <v-toolbar-items class="hidden-sm-and-down">
        <v-menu 
            :close-on-content-click="true"
            transition="scale-transition"
            open-on-hover
            offset-y>
        <template v-slot:activator="{ attrs, on }">
          <v-btn
            class="black--text text-capitalize"
            v-bind="attrs"
            v-on="on"
            text
          >
            Software Product Development
          </v-btn>
        </template>
<!-- <v-card tile class="borderRadius"> -->
        <v-list tile dense class="elevation-0 ">
          <v-list-item v-for="item in items" :key="item" :to="item.to">
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item>
        </v-list>
        <!-- </v-card> -->
      </v-menu>
      <v-btn class="black--text text-capitalize" text to="/data-annotation">
        Computer Vision AI
      </v-btn>

      <v-btn text class="mx-5 text-capitalize" to="/about">About Us</v-btn>

      <v-btn text class="mx-5">Blog</v-btn>

            <v-spacer></v-spacer>

      <v-img :src="require('../assets/flag.webp')" width="60" height="30" lazy-load color="#1AA15F" class="mt-4"
        ></v-img
      >
      </v-toolbar-items>
     
    </v-toolbar>


    </v-app-bar>

    <v-navigation-drawer class="back1" v-model="drawer" absolute temporary>

   
     <v-list-group>
            <template v-slot:activator>
              
              <v-list-item-title class=" text-left align-self-center"
                >Software Product Development</v-list-item-title
              >
            </template>
            <v-list-item link to="/cross-platform-appDevelopment" >
             
              <v-list-item-content>
                <v-list-item-title
                  class=" text-left align-self-center"
                  >Cross Platform App Development</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>
            <v-list-item link to="/innovation-product-development">

              <v-list-item-content>
                <v-list-item-title
                  class=" text-left align-self-center"
                  >Innovation Product Development</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>
            <v-list-item link to="/shopify-ecommerce-development">

              <v-list-item-content>
                <v-list-item-title
                  class=" text-left align-self-center"
                  >Shopify E-Commerce Development</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>
            <v-list-item link to="/devOpps-agile-excellence">

              <v-list-item-content>
                <v-list-item-title
                  class=" text-left align-self-center"
                  >DevOps and Agile Excellence</v-list-item-title
                >
              </v-list-item-content>
            </v-list-item>
          </v-list-group>
          <v-list-item link to="/data-annotation">
            
            <v-list-item-title class=" text-left align-self-center"
              >Computer Vision AI</v-list-item-title
            >
          </v-list-item>
          <v-list-item link to="/about">
           
            <v-list-item-title class=" text-left align-self-center"
              >About Us</v-list-item-title
            >
          </v-list-item>
     
    </v-navigation-drawer>

    <v-main>
      <v-container fluid class=" pa-0">
        <Nuxt />
      </v-container>
    </v-main>
    <v-section class="grey lighten-3">
      <v-container>
        <v-row>
          <v-col cols="12" lg="4" md="12" sm="12">
            <v-toolbar-title class="pl-0 ml-0">
              <v-img
                :src="require('../assets/logo.png')"
                width="160"
                class="mt-4"
                lazy-load
              ></v-img>
            </v-toolbar-title>
            <h4 class="body-2 mt-2">
              Ahdus Technology works to advance the machine elements of digital
              transformation of Enterprise software, machine learning and
              artificial intelligence systems. We develop Enterprise software
              which are used by millions of people around the globe.
            </h4>
            <v-text-field
              outlined
              dense
              label="Type Email"
              class="borderRadius mt-5"
            >
            </v-text-field>

            <v-btn tile class="white--text ml-auto accent text-capitalize"
              >Submit</v-btn
            >
          </v-col>
          <v-col cols="12" lg="4" md="6" sm="6">
            <h3 class="mt-16 font-weight-medium ml-14">Services Link</h3>
            <v-list dense color="transparent" class="ml-10">
              <v-list-item v-for="item in items" :key="item" :to="item.to" link>
                <v-list-item-title>{{ item.title }}</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-col>

          <v-col cols="12" lg="4" md="12" sm="12">
            <h3 class="mt-16 font-weight-medium ml-4">Information</h3>
            <v-list dense color="transparent">
              <v-list-item class="mb-0">
                <v-list-item-icon class="accent--text font-weight-bold mr-2"
                  >TEL:</v-list-item-icon
                >
                <v-list-item-title
                  >+0890-564-5644
                </v-list-item-title></v-list-item
              >
              <v-list-item class="">
                <v-list-item-icon class="accent--text font-weight-bold mr-2"
                  >INFO:</v-list-item-icon
                >

                <v-list-item-title class="">
                  Info@ahdustechnology.com
                </v-list-item-title></v-list-item
              >
              <v-list-item class="">
                <v-list-item-icon class="accent--text font-weight-bold mr-2"
                  >Location:</v-list-item-icon
                >

                <v-list-item-title>
                  143 C PGECHS Phase 2, 54000, Lahore, Pakistan
                  Robert-Bosch-Straße 42, 74072, Heilbronn, Germany
                </v-list-item-title></v-list-item
              >
            </v-list>
            <v-icon color="accent" class="ml-3">mdi-facebook</v-icon>
            <v-icon color="accent" class="mx-1">mdi-twitter</v-icon>

            <v-icon color="accent" class="mx-1">mdi-google-plus</v-icon>

            <v-icon color="accent" class="mx-1">mdi-pinterest</v-icon>
            <v-icon color="accent" class="mx-1">mdi-instagram</v-icon>
          </v-col>
        </v-row>
      </v-container>
    </v-section>
    <div>
      <span
        >Copyright &copy; {{ new Date().getFullYear() }} All Rights
        Reserved</span
      >
    </div>
  </v-app>
</template>

<script>
import lazyLoad from "vue-lazyload";
export default {
  target: 'static',
  components: { lazyLoad },
  name: "DefaultLayout",
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      src: "",
      right: true,
      rightDrawer: false,

      items: [
        {
          title: "Cross-Platform App Development",
          to: "/cross-platform-appDevelopment",
        },

        {
          title: "Innovation Product Development",
          to: "/innovation-product-development",
        },
        {
          title: "Shopify E-Commerce Development",
          to: "/shopify-ecommerce-development",
        },
        {
          title: "DevOps & Agile Excellence",
          to: "/devOpps-agile-excellence",
        },
      ],
    };
  },
  methods: {
    changeRoute() {
      console.log("sdfsaf");
      this.$router.push({ path: "" });
    },
  },
  computed: {
    headerImage() {
      console.log(this.$route.name);
      if (this.$route.name == "index") {
        this.src = "../assets/CV.jpg";
        console.log("test", this.src);
      } else if (this.$route.name == "cross-platform-appDevelopment") {
        this.src = "../assets/logo.svg";
        console.log("test", this.src);
      } else if (this.$route.name == "innovation-product-development") {
      } else if (this.$route.name == "shopify-ecommerce-development") {
      } else if (this.$route.name == "devOpps-agile-excellence") {
      }
    },
  },
};
</script>
<style >
.back1 {
  background-color: red;
}
.back2 {
  background-color: yellow;
}
.back3 {
  background-color: green;
}
.borderRadius {
  border-radius: 0px !important;
}
.logo {
  height: 30px;
  width: 80px;
}
.box {
  height: 400px;
  width: 80%;

  display: flex;
  flex-direction: column;
  justify-content: flex-end; /* vertically aligns items */
}
</style>
