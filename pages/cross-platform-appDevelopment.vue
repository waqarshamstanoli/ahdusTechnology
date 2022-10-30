<template>
<v-container fluid class="pa-0">
      <v-img :src="require('../assets/5.webp')" height="400" v-if="this.$route.name=='cross-platform-appDevelopment'" lazy-load></v-img>
      <v-container>
     <v-row>
      
 <v-col cols="12" lg="3" md="6" sm="6">
        <v-card height="400 " class="borderRadius mt-16">
          <v-img :src="require('../assets/question-mark-icon-thinking-solution_53876-123009.webp')" lazy-load></v-img>
          <v-card-text>
          <h3 class="text-center black--text">Identify the problems</h3>

            <h4 class="body-2">It makes no sense to have an app developed for your company if the problem has not yet been correctly identified. We sit down with you, go through intensive brainstorming discussions, and analyze your wishes and requirements.</h4>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" lg="3" md="6" sm="6">
        <v-card height="450" class="overflow-hidden borderRadius mt-16">
          <v-toolbar-title class="text-center ">
          <img :src="require('../assets/make-app.jpg')" width="100%" height="190">
          </v-toolbar-title>

          <v-card-text>
          <h3 class="text-center black--text">Plan the MVP roadmap for your app</h3>

            <h4 class="body-2">After the initial requirements or in some cases detailed requirement has been discussed, we set an MVP- roadmap for your app project, which describes the cost of the app development, the shorter release cycles, and other important things so that you know what to expect.

If you agree with the submitted plan, then we don’t hesitate for long and we start implementing it. When programming, we stick to your specifications and make sure that the plan is adhered to. After all, you should use the app for your company if possible hold it in your hands quickly.</h4>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" lg="3" md="6" sm="6">
        <v-card height="450" class="overflow-hidden borderRadius mt-16">
          <v-img :src="require('../assets/thoughtful-android-robot-3d-illustration-contains-clipping-path.webp')" lazy-load></v-img>
          
          <v-card-text>
            <h3 class="text-center black--text">App programming for Android, iOS, or Cross-platform</h3>
            <h4 class="body-2">It doesn’t matter whether you want to develop an app for Android or iOS, or need a cross-platform solution, or have other unusual requirements, We have the optimal solution for you. Because one thing is certain: Every business has individual challenges and special needs for app development that go hand in hand with it.

We normally develop small business owners to have their favorite app developed in cross-platform i.e. React-native because it is cost-saving, and single code can be used for multiple platforms which saves development time and costs. We develop in React-native, xamarin, flutter, and pure Javascript languages so that our customers could enjoy a fresh and cool look in the UX/UI of their app.

However, we also offer independent iOS and android app development. Recently we started using the modern app programming language Kotlin for app development.</h4>
          </v-card-text>
        </v-card>
      </v-col>
       <v-col cols="12" lg="3" md="6" sm="6">
        <v-card height="450" class="borderRadius overflow-hidden mt-16">
          <v-img :src="require('../assets/customer-care-webpage-interface-word.webp')" lazy-load></v-img>
          
          <v-card-text>
            <h3 class="text-center black--text">Delivery – shorter release cycles for MVP of your app</h3>
            <h4 class="body-2">Our customers enjoy fast delivery with a shorter release cycle of two weeks which gives enough visibility and a shorter feature set in order to get customer feedback. This two-week release cycle makes sure that we are well-aligned with your requirements and you can see the results, test your real app in your hands and give instant feedback for any further change.

We use CI/CD tool-set Microsoft Azure, GIT, and Jenkins for the delivery mode.</h4>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" lg="12" md="12" sm="12">
        <v-card color="transparent" class="elevation-0 mt-16">
          <h1 class="text-center">Free support after the implementation</h1>
          <v-card-text>
            <h4 class=" text-center body-1">
              You can rely on our post-implementation 2 months support in case of any bugs found in the agreed requirements. We don’t charge you for bug-fixing and this is the main reason we offer 2 months of support.
Unlimited bug-fixing in implemented requirements is fully covered in the support package.
            </h4>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
    </v-container>
</v-container>
    
</template>
<script>
import lazyLoad from 'vue-lazyload'
export default{
  target: 'static',
  components:{lazyLoad},
  data(){
    return {
      
    }
  }
}

</script>
