<template>
  <div class="whatWedo">
      <div class="p-5 bg-body rounded" style="max-width: 1200px; margin:30px auto">
      <div>
        <ul class="nav nav-tabs justify-content-center" id="myTab" role="tablist">
            <li class="nav-item" role="presentation">
                <button class="nav-link active" id="deforest-tab" data-bs-toggle="tab" data-bs-target="#deforest" type="button" role="tab" aria-controls="home" aria-selected="true">Effects of Deforestation</button>
            </li>
            <li class="nav-item" role="presentation">
                <button class="nav-link" id="whatwedo-tab" data-bs-toggle="tab" data-bs-target="#whatwedo" type="button" role="tab" aria-controls="profile" aria-selected="false">What We Do</button>
            </li>
        </ul>
            <div class="tab-content" id="myTabContent">

                
                <!-- ////////////////////// Deforestation //////////////////////////////////////-->
            <div class="tab-pane fade show active py-3" id="deforest" role="tabpanel" aria-labelledby="deforest-tab">
                <div class="deforestParent">
                    <div class="deforestImg1">
                    <img class="w-100" src="../assets/Deforestation/img1.jpg" alt="..." />
                    </div>

                    <div class="deforestDetail1 p-3 rounded">
                        <h4 class="text-light">Increase in Global Warming</h4>
                        <p class="mb-0 text-white">Trees help regulate the climate by absorbing CO2 from the atmosphere. With constant deforestation, the ratio of greenhouse gases in the atmosphere has increased, adding to our global warming woes.</p>
                    </div>

                    <div class="deforestDetail2 p-3 rounded">
                        <h4 class="text-light">Soil Erosion & Floods</h4>
                        <p class="mb-0 text-white">With the clearance of tree cover, the land is directly exposed to the sun, making it dry.  
When it rains, the flow of water is disrupted, and the soil loses its ability to retain water. It leads to floods in some areas and droughts in others.</p>
                    </div>

                    <div class="deforestImg2">
                    <img class="w-100" src="../assets/Deforestation/img2.jpg" alt="..." />
                    </div>

                    <div class="deforestImg3">
                    <img class="w-100" src="../assets/Deforestation/img3.jpg" alt="..." />
                    </div>

                    <div class="deforestImg4">
                    <img class="w-100" src="../assets/Deforestation/img4.jpg" alt="..." />
                    </div>

                    <div class="deforestDetail3 p-3 rounded">
                        <h4 class="text-light">Wildlife Extinction & Habitat Loss</h4>
                        <p class="mb-0 text-white">Due to the massive felling down of trees, various animal species are lost. They lose their habitat and also forced to move to a new location. Many of them are even pushed to extinction.</p>
                    </div>
                </div>

            </div>
            <!-- ////////////////////// Deforestation //////////////////////////////////////-->

            <!-- ////////////////////// What WE Do //////////////////////////////////////-->
            <div class="tab-pane fade" id="whatwedo" role="tabpanel" aria-labelledby="whatwedo-tab">
                <div class="whatwedoParent">
                    <div class="whatwedoImg1">
                    <img class="w-100" src="../assets/Whatwedo/img1.jpg" alt="..." />
                    </div>

                    <div class="whatwedoDetail1 p-3 rounded">
                        <h4 class="text-light">Tree Planting</h4>
                        <p class="mb-0 text-white">Once land is under conservation management by Need For Trees, options are investigated to restore deforested land and degraded habitat, reconnecting previously fragmented forest patches. This can be achieved using two techniques; tree planting and removing a threat to allow forest to regenerate naturally.</p>
                    </div>

                    <div class="whatwedoDetail2 p-3 rounded">
                        <h4 class="text-light">Land Acquisition</h4>
                        <p class="mb-0 text-white">We preserve rainforest from threatened habitats through land purchase. Partnership with government body and local community, Need For Trees funds the purchase or lease of threatened land to create nature reserves, protecting both habitats and their wildlife.</p>
                    </div>

                    <div class="whatwedoImg2">
                    <img class="w-100" src="../assets/Whatwedo/img2.jpg" alt="..." />
                    </div>

                    <div class="whatwedoImg3">
                    <img class="w-100" src="../assets/Whatwedo/img3.jpg" alt="..." />
                    </div>

                    <div class="whatwedoDetail3 p-3 rounded">
                        <h4 class="text-light">Forest Patrol</h4>
                        <p class="mb-0 text-white">Dedicated Patrol Team who supports the protection of the rainforest from illegal logging, hunting of endangered species and forest fires.</p>
                    </div>

                    <div class="whatwedoDetail4 p-3 rounded">
                        <h4 class="text-light">Maintenance</h4>
                        <p class="mb-0 text-white">With regular maintenance such as assessment of trees safety conditions, the saplings have a growth and survival rate of up to 85% compared to saplings without maintenance.</p>
                    </div>

                    <div class="whatwedoImg4">
                    <img class="w-100" src="../assets/Whatwedo/img4.jpg" alt="..." />
                    </div>
                </div>

            </div>
            <!-- ////////////////////// What WE Do //////////////////////////////////////-->


            </div>
      </div>
      </div>
  </div>
</template>

<script>


import {ref, reactive} from 'vue'
export default {
    setup(){

        const HideWeDo = ref(true)

        return{HideWeDo}
    }
}
</script>

<style>

.project-text{
    background-color: #00B050;
}

.nav-tabs .nav-link{
    color: black;
    font-weight: bold;
    font-size: larger;

}

.nav-tabs .nav-link.active,
.nav-tabs .nav-item.show .nav-link {
    color: #00B050;
    background-color: #fff;
    border-color: #00B050 #00B050 #fff;
}

.nav-tabs .nav-link:hover, .nav-link:focus {
    color: #00B050;
}

/* .spacer{
    background-color: black;
    height: 1200px;
} */

/*/////////////////////// Deforest Tab Style ///////////////// */

/* .deforestParent{
    position: relative;
} */

.deforestImg1{
    position: absolute;
    max-width: 600px;
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.deforestDetail1{
    position: absolute;
    max-width: 500px;
    background-color: #00B050;
    transform: translate(100%,50%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.deforestImg2{
    position: absolute;
    max-width: 600px;
    position: absolute;
    background-color: #00B050;
    transform: translate(80%,90%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.deforestDetail2{
    position: absolute;
    max-width: 300px;
    background-color: #00B050;
    transform: translate(20%,200%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.deforestImg3{
    position: absolute;
    max-width: 500px;
    position: absolute;
    background-color: #00B050;
    transform: translate(110%,150%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.deforestDetail3{
    position: absolute;
    max-width: 300px;
    background-color: #00B050;
    transform: translate(180%, 370%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.deforestImg4{
    position: absolute;
    max-width: 500px;
    position: absolute;
    background-color: #00B050;
    transform: translate(0%, 220%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

/*/////////////////////// Deforest Tab Style ///////////////// */


/*/////////////////////// WhatWeDo Tab Style ///////////////// */

.whatwedoImg1{
    position: absolute;
    width: 600px;
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoDetail1{
    position: absolute;
    max-width: 500px;
    background-color: #00B050;
    transform: translate(100%,50%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoImg2{
    position: absolute;
    width: 500px;
    position: absolute;
    transform: translate(100%, 90%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoDetail2{
    position: absolute;
    max-width: 500px;
    background-color: #00B050;
    transform: translate(10%,250%);
    z-index: 1;
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoImg3{
    position: absolute;
    width: 600px;
    position: absolute;
    transform: translate(0,190%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoDetail3{
    position: absolute;
    max-width: 400px;
    background-color: #00B050;
    transform: translate(100%, 720%);
    z-index: 1;
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoImg4{
    position: absolute;
    width: 400px;
    position: absolute;
    background-color: #00B050;
    transform: translate(150%, 230%);
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

.whatwedoDetail4{
    position: absolute;
    max-width: 500px;
    position: absolute;
    background-color: #00B050;
    transform: translate(30%, 900%);
    z-index: 1;
    box-shadow: 5px 10px 10px 5px rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);
}

/*/////////////////////// WhatWeDo Tab Style ///////////////// */
</style>