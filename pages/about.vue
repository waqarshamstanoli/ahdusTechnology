<template>
<v-container class="mt-16 pa-0">
   <v-row>
        <v-col cols="12" lg="4" md="12" sm="12">
            <v-card color="transparent" class="elevation-0 mt-10">
                <div class="text-center">
                <v-badge
        avatar
        bordered
        overlap
      
      >
        <template v-slot:badge>
          <v-avatar size="50">
           20
          </v-avatar>
        </template>

        <v-avatar size="100" >
          <v-img :src="require('../assets/5760717-middle.png')" lazy-load></v-img>
        </v-avatar>
      </v-badge>
      </div>
      <v-card-title class="justify-center">
          Our Vision
      </v-card-title>
                <v-card-text>
                  <h4 class="body-2">
                    A vision is what could be explained in a one-sentence, our vision is

“To enable technology at it’s best fostering the innovation rate in next generation IT solutions”
                  </h4>
                </v-card-text>
            </v-card>
        </v-col>
         <v-col cols="12" lg="4" md="12" sm="12">
            <v-card color="transparent" class="elevation-0 mt-10">
                <div class="text-center">
                <v-badge
        avatar
        bordered
        overlap
      
      >
      
        <template v-slot:badge>
          <v-avatar size="100">
           20
          </v-avatar>
        </template>

        <v-avatar size="100" >
          <v-img :src="require('../assets/download.png')" lazy-load></v-img>
        </v-avatar>
      </v-badge>
      </div>
      <v-card-title class="justify-center">
          Our Goal
      </v-card-title>
                <v-card-text>
                  <h4 class="body-2">
                   “Customer satisfaction through innovation in enterprise software systems, easy to manage code, faster delivery and shorter feedback loops”
                  </h4>
                </v-card-text>
            </v-card>
        </v-col>
         <v-col cols="12" lg="4" md="12" sm="12">
            <v-card color="transparent" class="elevation-0 mt-10">
                <div class="text-center">
                <v-badge
        avatar
        bordered
        overlap
      
      >
        <template v-slot:badge>
          <v-avatar size="100">
           20
          </v-avatar>
        </template>

        <v-avatar size="100" >
          <v-img :src="require('../assets/who.png')" lazy-load></v-img>
        </v-avatar>
      </v-badge>
      </div>
      <v-card-title class="justify-center">
          Who we are
      </v-card-title>
                <v-card-text>
                  <h4 class="body-2">
                   We are a team of software developers, data engineers, data scientists, DevOps engineers, and mobile developers with a diverse skillset and multiple industry experiences. We use agile development methodologies to provide optimal outcomes for our valued clients.
                   </h4>
                </v-card-text>
            </v-card>
        </v-col>
        <v-col cols="12" lg="12" md="12" sm="12">
            <h1 class="text-center mt-5">Our Achievement
</h1>
<h4 class="text-center body-1">Dummy text is also used to demonstrate the appearance of different typefaces and layouts</h4>
        </v-col>
<v-col cols="12" lg="12" md="12" sm="12">
            <h1 class="text-center">Our Experts Team Member
</h1>
<h4 class="text-center body-1">Dummy text is also used to demonstrate the appearance of different typefaces and layouts</h4>
        </v-col>
        <v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/55.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Zahid Iqbal
</h2>
           <h5 class="text-center">Director at AHDUS TECHNOLOGY</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
  
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/44.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Toshko Ivanov
</h2>
           <h5 class="text-center">Chief Technology Innovation Officer at AHDUS TECHNOLOGY</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
  
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius "> 
        <v-img :src="require('../assets/1633076814535.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Iram Shahid Kiani</h2>
           <h5 class="text-center">Global Business Development Manager</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius "> 
        <v-img :src="require('../assets/team_member_fatima.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Fatima Aftab</h2>
           <h5 class="text-center">Digital Content Creator</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius "> 
        <v-img :src="require('../assets/team_member_faiza.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Faiza Arif</h2>
           <h5 class="text-center">Test Specialist</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
     
        <v-img :src="require('../assets/1517405836245.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
            
          >
           <h2 class="text-center">Amir Khan</h2>
           <h5 class="text-center">Software Engineer</h5>
          </v-overlay>
        </transition>


    </v-card>
    </template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/1559181867697.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Talha Mohsin
</h2>
           <h5 class="text-center">Full Stack Developer</h5>
          </v-overlay>
        </transition>
    </v-card>
    </template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/1573544236887.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Mohsin Mushtaq</h2>
           <h5 class="text-center">.Net Developer</h5>
          </v-overlay>
        </transition>
    </v-card>
    </template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/waq.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Waqar Shams</h2>
           <h5 class="text-center">Front End Developer</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/1625246818604.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Amir Khan</h2>
           <h5 class="text-center">Software Engineer</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/1630401170962.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Dawood Asjad</h2>
           <h5 class="text-center">E-Commerce Web Developer & Business Consultant</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>

<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/1644833863517.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Sheheryar Shahid</h2>
           <h5 class="text-center">Xamarin Mobile Developer</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/11.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Muhammad Shehzad</h2>
           <h5 class="text-center">Xamarin Mobile Developer</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
  
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/22.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Irtaza Hassan</h2>
           <h5 class="text-center">Software Engineer PHP</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
  
</v-col>
<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/33.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">Mohammad Kashif Randhawa
</h2>
           <h5 class="text-center">Business Developer</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
  
</v-col>


<v-col cols="12" lg="3" md="6" sm="6">
  <v-hover>
    <template v-slot:default="{ hover }">
    <v-card class="borderRadius"> 
        <v-img :src="require('../assets/66.jpg')" width="100%" height="299" lazy-load></v-img>
         <transition name="slide-fade">
          <v-overlay
            v-if="hover"
            absolute
            color="accent"
            opacity=0.9
            z-index="4"
          >
           <h2 class="text-center">
Haseeb Zia</h2>
           <h5 class="text-center">Xamarin Mobile Developer</h5>
          </v-overlay>
        </transition>
    </v-card></template>
  </v-hover>
  
</v-col>

    </v-row>
</v-container>
</template>
<script>
import lazyLoad from 'vue-lazyload'
export default {
     components: { lazyLoad },
    target: 'static',
    data() {
      return {
        
      }
        
    },
}
</script>
<style scoped>

.content {
  position: relative;
  width: 100%;
  max-width: 400px;
  margin: auto;
  overflow: hidden;
}

.content .content-overlay {
  background: rgba(3, 98, 240, 0.7);
  position: relative;
  height: 90%;
  width: 100%;
  left: 0;
  top: 0;
  bottom: 0;
  right: 0;
  opacity: 0;
  -webkit-transition: all 0.4s ease-in-out 0s;
  -moz-transition: all 0.4s ease-in-out 0s;
  transition: all 0.4s ease-in-out 0s;
}

.content:hover .content-overlay{
  opacity: 1;
}


.content-details {
  position: absolute;
  text-align: center;
  padding-left: 1em;
  padding-right: 1em;
  width: 100%;
  top: 20%;
  left: 50%;
  opacity: 0;
  -webkit-transform: translate(-50%, -50%);
  -moz-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-transition: all 0.3s ease-in-out 0s;
  -moz-transition: all 0.3s ease-in-out 0s;
  transition: all 0.3s ease-in-out 0s;
}

.content:hover .content-details{
  top: 50%;
  left: 50%;
  opacity: 1;
}

.fadeIn-bottom{
  top: 80%;
}

.fadeIn-top{
  top: 20%;
}
/*
  Enter and leave animations can use different
  durations and timing functions.
*/
.slide-fade-enter-active {
   transition: all 0.30s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.5s cubic-bezier(1, 0.5, 0.8, 1);
}

.slide-fade-enter-from  {
  transform: translateX(-200px);
  opacity: 0;
}
.slide-fade-leave-to {
  transform: translatey(20px);
  opacity: 0;
}

</style>