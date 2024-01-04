<template>
  <v-app light>
    <v-app-bar :clipped-left="clipped" fixed color="white">
      <v-app-bar-nav-icon
        @click="drawer = true"
        class="hidden-md-and-up"
      ></v-app-bar-nav-icon>
      <nuxt-link to="/">
        <v-toolbar-title link @click="changeRoute()">
          <img
            :src="require('../assets/BimmerTech logo.svg')"
            class="mt-2 ml-5"
            lazy-load
          />
        </v-toolbar-title>
      </nuxt-link>

      <v-toolbar class="hidden-sm-and-down elevation-0" color="">
        
<v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down ">
          
         <v-text-field
    
    dense
    outlined
    rounded
    label="Search products of enter your VIN"
    append-icon="mdi-magnify"
    class="mb-0"
    
    @click:append-inner="onClick"
  ></v-text-field>
        </v-toolbar-items>
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down ">
          <img
            :src="require('../assets/log in.svg')"
            class="mt-2 ml-5"
            width="30"
            lazy-load
          />
         <img
            :src="require('../assets/VIN.svg')"
            class="mt-2 ml-5"
            width="50"
            lazy-load
          />
          <img
            :src="require('../assets/cart.svg')"
            class="mt-2 ml-5"
            width="30"
            lazy-load
          />
          <img
            :src="require('../assets/burger.svg')"
            class="mt-2 ml-5"
            width="30"
            lazy-load
          />
        </v-toolbar-items>
      </v-toolbar>
    </v-app-bar>

    <v-navigation-drawer class="back1" v-model="drawer" absolute temporary>
      <v-list-group>
        <template v-slot:activator>
          <v-list-item-title class="text-left align-self-center"
            >test</v-list-item-title
          >
        </template>
        <v-list-item link to="/cross-platform-appDevelopment">
          <v-list-item-content>
            <v-list-item-title class="text-left align-self-center"
              >test</v-list-item-title
            >
          </v-list-item-content>
        </v-list-item>
        <v-list-item link to="/innovation-product-development">
          <v-list-item-content>
            <v-list-item-title class="text-left align-self-center"
              >test</v-list-item-title
            >
          </v-list-item-content>
        </v-list-item>
        <v-list-item link to="/shopify-ecommerce-development">
          <v-list-item-content>
            <v-list-item-title class="text-left align-self-center"
              >test</v-list-item-title
            >
          </v-list-item-content>
        </v-list-item>
      </v-list-group>
    </v-navigation-drawer>

    <v-main>
      <v-container fluid class="pa-0">
        <Nuxt />
      </v-container>
    </v-main>
    <v-section class="grey lighten-3">
      <v-container>
        <v-row>
          <v-col cols="12" lg="4" md="12" sm="12">
            <v-toolbar-title class="pl-0 ml-0">
              <v-img
                :src="require('../assets/BimmerTech logo.svg')"
                width="160"
                class="mt-4"
                lazy-load
              ></v-img>
            </v-toolbar-title>
            <h4 class="body-2 mt-2">
             Tst text
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
              <v-list-item  link>
                <v-list-item-title>List</v-list-item-title>
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
                  Email
                </v-list-item-title></v-list-item
              >
              <v-list-item class="">
                <v-list-item-icon class="accent--text font-weight-bold mr-2"
                  >Location:</v-list-item-icon
                >

                <v-list-item-title>
                  Adress
                  
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
  target: "static",
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

      
    };
  },
  methods: {
    changeRoute() {
      
      this.$router.push({ path: "" });
    },
  },
  
};
</script>
<style >


</style>
