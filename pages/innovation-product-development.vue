<template>
<div>
<v-img :src="require('../assets/2.jpg')" height="400" v-lazy-load></v-img>
    <h1>Innovation</h1>
    </div>
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
</script