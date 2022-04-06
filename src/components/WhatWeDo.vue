<template>
  <div class="whatWedo">
      <div class="shadow-lg p-5 mb-5 bg-body rounded" style="max-width: 1200px; margin:30px auto">
          <div>
              <ul class="nav nav-tabs justify-content-center">
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" v-on:click="HideWeDo = true" id="navlink">Effects of Deforestation</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" v-on:click="HideWeDo = false">What We Do</a>
                </li>
                </ul>
          </div>
          <div v-if="HideWeDo">
              <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6"><img class="img-fluid w-100" src="../assets/Deforestation/img1.jpg" alt="..." /></div>
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Increase in Global Warming</h4>
                                    <p class="mb-0 text-black">Trees help regulate the climate by absorbing CO2 from the atmosphere. With constant deforestation, the ratio of greenhouse gases in the atmosphere has increased, adding to our global warming woes.</p>
                                </div>
                            </div>
                    </div>
                </div>
                <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Soil Erosion & Floods</h4>
                                    <p class="mb-0 text-black">With the clearance of tree cover, the land is directly exposed to the sun, making it dry.  
When it rains, the flow of water is disrupted, and the soil loses its ability to retain water. It leads to floods in some areas and droughts in others.
</p>
                                </div>
                            </div>
                    </div>
                    <div class="col-lg-6">
                        <img class="img-fluid w-100" src="../assets/Deforestation/img2.jpg" alt="..." />
                    <img class="img-fluid w-50" src="../assets/Deforestation/img3.jpg" alt="..." />
                    </div>
                </div>
                <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6"><img class="img-fluid w-100" src="../assets/Deforestation/img4.jpg" alt="..." /></div>
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Wildlife Extinction & Habitat Loss</h4>
                                    <p class="mb-0 text-black">Due to the massive felling down of trees, various animal species are lost. They lose their habitat and also forced to move to a new location. Many of them are even pushed to extinction.</p>
                                </div>
                            </div>
                    </div>
                </div>
          </div>
                    <div v-else>
              <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6"><img class="img-fluid w-100" src="../assets/Whatwedo/img1.jpg" alt="..." /></div>
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Tree Planting</h4>
                                    <p class="mb-0 text-black">Once land is under conservation management by Need For Trees, options are investigated to restore deforested land and degraded habitat, reconnecting previously fragmented forest patches. This can be achieved using two techniques; tree planting and removing a threat to allow forest to regenerate naturally.</p>
                                </div>
                            </div>
                    </div>
                </div>
                <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Land Acquisition</h4>
                                    <p class="mb-0 text-black">We preserve rainforest from threatened habitats through land purchase. Partnership with government body and local community, Need For Trees funds the purchase or lease of threatened land to create nature reserves, protecting both habitats and their wildlife.</p>
                                </div>
                            </div>
                    </div>
                    <div class="col-lg-6">
                        <img class="img-fluid w-100" src="../assets/Whatwedo/img2.jpg" alt="..." />
                    </div>
                </div>
                <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6"><img class="img-fluid w-100" src="../assets/Whatwedo/img3.jpg" alt="..." /></div>
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Forest Patrols</h4>
                                    <p class="mb-0 text-black">Dedicated Patrol Team who supports the protection of the rainforest from illegal logging, hunting of endangered species and forest fires.</p>
                                </div>
                            </div>
                    </div>
                </div>
                <div class="row gx-0 justify-content-center">
                    <div class="col-lg-6">
                            <div class="d-flex h-100 text-center">
                                <div class="project-text w-100 my-auto text-center p-5">
                                    <h4 class="text-dark">Maintenance</h4>
                                    <p class="mb-0 text-black">With regular maintenance such as assessment of trees safety conditions, the saplings have a growth and survival rate of up to 85% compared to saplings without maintenance.</p>
                                </div>
                            </div>
                    </div>
                    <div class="col-lg-6">
                        <img class="img-fluid w-100" src="../assets/Whatwedo/img4.jpg" alt="..." />
                    </div>
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
.nav-link:hover{
    cursor: pointer;

}
</style>