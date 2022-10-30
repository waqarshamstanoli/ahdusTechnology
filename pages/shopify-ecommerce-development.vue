<template>
    <v-container fluid class="pa-0">
        <v-img :src="require('../assets/4.jpg')" height="400"  lazy-load></v-img> 
        <v-container>
        <v-row>
            <v-col cols="12" lg="6" md="12" sm="12">
                <v-card class="elevation-0 mt-10" color="transparent" >
                    <v-card-text>
                        <h4 class="body-2">Whether you are an individual or a firm, we will help you create a beautiful online store! Especially during a global pandemic, online buying and selling have increased drastically.

We have a dedicated expert team of e-commerce developers who have extensive knowledge of Shopify, Open-Cart, Magento, Woocommerce, and custom platform development.

We are able to handle large amounts of business data from GB to TB in databases, so in case you have complex problems in your e-commerce pipeline, we could save your work, we write code that is easy to read and easy to change.</h4>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col cols="12" lg="6" md="12" sm="12">
                <v-img :src="require('../assets/cloud.webp')" class="mt-10" lazy-load></v-img>
            </v-col>

            <v-col cols="12" lg="6" md="12" sm="12">
                <v-img :src="require('../assets/comerce.jpg')" class="mt-14" lazy-load></v-img>
            </v-col>

            <v-col cols="12" lg="6" md="12" sm="12">
                <v-card class="elevation-0 mt-10" color="transparent">
                    <v-card-title>We have mainly managed e-commerce web-portals of several Clients, considering,</v-card-title>
                    <v-card-text>
                        <h4 class="body-2">
                        Security – This goes enabling backend data-layers architecture to secure payment gateways and secure database server management
Service-Oriented Architecture – We use multi-layer, independent modules development which is loosely coupled and high cohesion, the reason is creating independent modules to roll back any crashes in minutes.
Holistic regression and integration testing of all features is part of our regular teamwork
A cross-platform mobile app using react-native on both iOS and Android platforms could be also built from our app developers
Do you want to run your store on Amazon? we will configure your FBM or FBA business model on Amazon and run a holistic amazon account handling including all the Virtual Assistant (VA) support you will be requiring from Product listing to product marketing.
We believe in the MVP mindset, therefore, our customer journey has a shorter release cycle hence enabling us with shorter customer feedback loops against any requirements. We develop small and then scale it on a further level. Our main focus is to convert complex business domains into a simple application architecture (TDD, SOLID, and CQRS methodology)
</h4>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col cols="12" lg="12" md="12" sm="12">
                <h1 class="text-center">Our favorite tool-set and languages include,</h1>
                <h4 class="body-2">Custom-PHP, Laravel, MSSQL, MYSQL, Oracle, Linux, CURL, Core Javascript, React-native, MS Azure, Bitbucket, SonarQube, Selenium Headless driver, Visual Studio SDK</h4>
            </v-col>

        </v-row>
        </v-container>
    </v-container>
</template>
<script>
import lazyLoad from 'vue-lazyload'
export default {
components:{
    lazyLoad
},
    target: 'static',
    data() {
        return {

        }
        
    },
}
</script>