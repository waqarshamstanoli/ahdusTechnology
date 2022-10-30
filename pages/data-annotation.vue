<template>
    <v-container fluid class="pa-0">
        <v-img :src="require('../assets/4.jpg')" height="400"  lazy-load></v-img>
        <v-container>
        <v-row>
            <v-col cols="12" lg="6" md="12" sm="12">
                <v-card class="elevation-0 mt-10" color="transparent">
                    <v-card-text>
                        <h4 class="body-2">
                            There are 7.8 billion people on our lovely earth and an estimated 1.4 billion cars on the road. By now, almost every 3rd person is well aware of what the automotive industry is going through!! Automotive industry racing towards fully Autonomous driving of their fleet. This job cannot be possible without Data annotation or, Data Labeling.

The term Autonomous driving is usually used to describe self-driving vehicles or transport systems that move in a targeted manner without intervention by the human driver. In 2014, SAE International (Society of Automotive Engineers) defined the development stages for such a fully autonomous vehicle. The independent driving levels range from level 0 (no automation) to level 5 (driverless driving).


                        </h4>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col cols="12" lg="6" md="12" sm="12">
                <v-img :src="require('../assets/auto.webp')" class="mt-10" lazy-load ></v-img>
            </v-col>

            <v-col cols="12" lg="6" md="12" sm="12">
                <v-img :src="require('../assets/delivery.webp')" class="mt-10" lazy-load></v-img>
            </v-col>

            <v-col cols="12" lg="6" md="12" sm="12">
                <v-card class="mt-10 elevation-0" color="transparent">
                    <v-card-title>
                        How we help you with Data Annotation/Data Labeling:
                    </v-card-title>
                    <v-card-text>
                        <h4 class="body-2">Annotation is the process of labeling all objects in an image. The primary application of data labeling is the preparation of ground-truth data, which can be used to train machine-learning algorithms. We have a team of manual data annotators who are well-versed in converting your simple to complex data images to the highest possible quality-labeled. The final verification is done by our Data-Engineers who make sure that every labeled image goes 100% as per required by your R&D teams.

Our Data-Annotators help you, creating acceptable annotation of images for your machine learning and deep learning models for ground truth data such as object detection, image classification, and image segmentation.

We are capable of manually labeling several below types,</h4>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col cols="12" lg="4" md="12" sm="12">
                <v-card class="mt-10 borderRadius">
                     <v-img :src="require('../assets/truck-transport-metaverse-city-metaverse-concepts-3d-render.webp')" lazy-load  ></v-img>
                     <v-card-title>Bounding box labeling</v-card-title>
                     <v-card-text>Label with accuracy, just put two objects through any bounding box tool and draw rectangular boxes around them. We could create 2d-bounding box annotated images with our industry-standard annotation tool or with your selected/provided tool.</v-card-text>
                </v-card>
            </v-col>
            <v-col cols="12" lg="4" md="12" sm="12">
                <v-card class="mt-10 overflow-hidden borderRadius" height="400">
                     <v-img :src="require('../assets/polygon.jpg')" height="210" lazy-load ></v-img>
                     <v-card-title>Semantic segmentation using Polygon</v-card-title>
                     <v-card-text>This is the higher category of labeling, and every image is assigned to a class. For example, the levels could be a car, bus, pedestrian, road, tree, bird, etc. This is done on pixel-level, where every pixel is annotated.</v-card-text>
                </v-card>
            </v-col>
            <v-col cols="12" lg="4" md="12" sm="12">
                <v-card class="mt-10 overflow-hidden borderRadius" height="400">
                     <v-img :src="require('../assets/3d.jpg')" height="210" lazy-load ></v-img>
                     <v-card-title>3D Point Cloud Labeling</v-card-title>
                     <v-card-text>Point cloud annotation is the most needed labeling because Data Engineers or Machine Learning experts can then train their models based on this labeling. The ground-truth data is mainly gathered through the Lidar or Radar sensors, which are widely used sensor in the automotive industry.

In this labeling, data is visualized with 3D objects and labeled accordingly. A 3D box is used for better object detection. High precision is required here.

In our Data Annotation Factory at Ahdus Technology, we precisely annotate above all types and cover more scenarios like lane annotation, tags, and descriptions, key points, etc. The final quality control is run by our Data Engineers, considering the same methods of how a Machine Learning/Deep Learning Engineer will require the last prepared labeling image data.

Ahdus Technology is the first Data Science Company in Pakistan that has started Data-annotation for Automotive Industry, intending to provide precise and highest quality annotation services to its clients.

We could happily take your annotation work into our annotation factory and convert it to actionable annotation labeled images that your Data-Scientists could further use to make Level 5 automation in autonomous driving.

Apart from Data Annotation services, we are developing around Data Science, mainly machine learning, deep learning, and complex software development, while working under an agile and MVP mindset!</v-card-text>
                </v-card>
            </v-col>

        </v-row>
        </v-container>
    </v-container>
</template>
<script>
import lazyLoad from 'vue-lazyload'
export default {
     target: 'static',
    data() {
        return {
            
        }
        
    },
}
</script>