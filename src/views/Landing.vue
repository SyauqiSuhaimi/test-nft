<template>


<Carousel/>

<!-- <AboutUs/> -->

<WhatWeDo style="margin-top: 700px;"/>

<Map style="margin-top: 1400px;"/>

<!-- <Project/> -->
  
</template>

<script>
import Carousel from '../components/Carousel.vue';
import AboutUs from '../components/AboutUs.vue';
import WhatWeDo from '../components/WhatWeDo.vue';
import Map from '../components/Map.vue';
import Project from '../components/Project.vue';

export default {
    components: {
        AboutUs,
        Carousel,
        WhatWeDo,
        Map,
        Project,
    },


}

</script>

<style>

</style>