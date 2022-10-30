<template>
    <v-container fluid class="pa-0">
        <v-img :src="require('../assets/digital-cyberspace-data-network-connections.webp')" height="400"  lazy-load></v-img>
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
</script