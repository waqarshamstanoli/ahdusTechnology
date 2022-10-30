<template>
  <div>
  
     <v-img :src="require('../assets/3.webp')"  lazy-load>
     <v-container>
      <v-row>
        <v-col cols="12" lg="6">
          <div class="box" color="transparent">
<h1 class="white--text">We Enable Computer Vision to you ML Pipeline</h1>
<h4 class="white--text">
Cognitive science and machine-learning algorithms improve the next
generation of innovation, together with data science and AI solutions, 
we build around Computer Vision, analyze and process terabytes of data on GPUs” 
</h4>
</div>
<v-btn tile class="accent text-capitalize white--text mt-5">Get in Touch</v-btn>
        </v-col>
      </v-row>
      </v-container></v-img>
<v-container>
    <v-row>
      <v-col cols="12" lg="6" md="6" sm="6">
        <v-img :src="require('../assets/CV.jpg')" class="mt-16" width="500" lazy-load></v-img>
      </v-col>
      <v-col cols="12" lg="6" md="6" sm="6">
        <h1 class="mt-16">Computer Vision & AI</h1>
        <h4 class="body-1">In our Computer Vision Department, We are working with digital
           images and large datasets and build algorithms to process this 
           data which could be further used by our Customers for their Industrial 
           Projects. We annotate digital images and run holistic algorithms on GPUs 
           and AWS Cloud environments.
           We participate in Proof of concept (PoC) of different research problems. 
           Recently, we are working with machine learning and deep learning models 
           for the LG eye-detection research project, which includes data extraction,
            data annotation, and data modeling of gigabytes of data objects. Moreover, 
            LG is going to use research 
           results in their advanced eye-movement technology.</h4>
      </v-col>
       <v-col cols="12" lg="6" md="6" sm="6">
        <h1 class="mt-16">Enterprise Product Development</h1>
        <h4 class="body-1 mr-12">We design, program, and optimize software product technology and deliver holistic product development. We believe the ideology that every new software product must deliver a unique, cool, and great user experience(UX), and it must be faster time to market to stay ahead of competitors.
          Ähdus Software Engineers work in a 2-weeks sprint, user stories level, and produce MVP product increment faster and with the highest quality than any other market competitors. Since our operations in just 8 months, we have produced ~7 Enterprise level app and web products for our Swiss, Austrian and German Partners.</h4>
      </v-col>
      <v-col cols="12" lg="6" md="6" sm="6">
        <v-img :src="require('../assets/PD.webp')" class="mt-16" lazy-load width="500"></v-img>
      </v-col>
      <v-col cols="12" lg="12" md="12" sm="12">
        <h1 class="text-center">Our Clients</h1>
         <VueSlickCarousel
            
          
            :slidesToShow="5"
            :focusOnSelect="true"
            :arrows="true"
            :dots="true"
          >
         
<v-img :src="require('../assets/slider/ancient-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/appiculture-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/bee-supplies-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/bellimer-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/denkmenn-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/krist-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/livom-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/napo-min.jpg')" alt=""></v-img>
<v-img :src="require('../assets/slider/v-quiz-min.jpg')" alt=""></v-img>








            <!-- <div v-for="item in UrlsOfVideos" :key="item">
           
            </div> -->
          </VueSlickCarousel> 
      </v-col>
     
 <v-col cols="12" lg="4" md="12" sm="12">
   <v-card class="borderRadius mt-16" height="600">
        <v-img :src="require('../assets/cyber-monday-shopping-sales.jpg')" width="100%" height="230" lazy-load></v-img>
         <div class="text-center mt-10">
        <span ><v-icon >mdi-calendar </v-icon>13 may, 2018</span>
</div>
        
        <v-card-text>
          <h3 class="text-center black--text">HEADLESS E-COMMERCE- Is It the future of e-commerce????</h3>
          <h4 class="body-2 mt-5">As a Customer, Do you want to shop online with ease?
             Are you a fan of eye-catching smart gadgets such as smart-watches 
             and want the freedom, flexibility, and convenience of shopping with 
             just one click? As a Seller, Sell faster. Sell better. Sell more.”Sell 
             anything in seconds 
            – in person, online, on any screen. Sell</h4>
        </v-card-text>
     </v-card>
      </v-col>
       <v-col cols="12" lg="4" md="12" sm="12">
   <v-card class="borderRadius mt-16" height="600">
        <v-img :src="require('../assets/ibnr-.jpg')" width="100%" height="230" lazy-load></v-img>
         <div class="text-center mt-10">
        <span ><v-icon >mdi-calendar </v-icon>13 may, 2018</span>
</div>
        
        <v-card-text>
          <h3 class="text-center black--text">Ähdus ERP App for Shopify businesses for Inventory management</h3>
          <h4 class="body-2 mt-5">With every small business going online, there is a strong need to manage products inventory from ERP system to the online store a business is running. Since our Shopify experts design, develop and maintain beautiful Shopify e-commerce stores for several clients worldwide, we also develop Shopify apps to 
            facilitate the individual needs of our customers. […]</h4>
        </v-card-text>
     </v-card>
      </v-col>
       <v-col cols="12" lg="4" md="12" sm="12">
   <v-card class="borderRadius mt-16" height="600">
        <v-img :src="require('../assets/IOT.webp')" width="100%" height="240" lazy-load></v-img>
        <div class="text-center mt-10">
        <span ><v-icon >mdi-calendar </v-icon>13 may, 2018</span>
</div>
        
        <v-card-text>
          <h3 class="text-center black--text">How Ähdus Technology is building an IoT based Security Intelligent system</h3>
          <h4 class="body-2 mt-5">ÄHDUS TECHNOLOGY Joins Hands with Connect Security Solutions as their IT partner for an “Intelligent IoT based Security Solutions” About Connect Security Solutions Connect Security solutions, founded in 2004 have for many years been at the leading edge of patrol andworkforce management solutions. They are proud trusted suppliers of the world’s leading security andFacilities</h4>
        </v-card-text>
     </v-card>
      </v-col>
    </v-row>
    </v-container>

  </div>
</template>

<script>
import lazyLoad from 'vue-lazyload'
// import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
export default {
  target: 'static',
  components: { lazyLoad },
  name: 'IndexPage',
  data (){
    return {
imgage:'../assets/1.jpg'
    }
  }
}
</script>
<style scoped>
.box {
  height: 450px;
  width: 75%;

  display: flex;
  flex-direction: column;
  justify-content: flex-end; /* vertically aligns items */
  
}
</style>
