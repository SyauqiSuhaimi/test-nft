<template>
  <div class="project">
      
<div class="shadow-lg p-5 mb-5 bg-body rounded" style="max-width: 1500px; margin:30px auto">
<div class="container">
    <div class="row">
        <div class="col-md">
            <div class="card" style="width: 18rem; margin: 10px auto;">
            <img src="../assets/HomeImage/image1.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Project A</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="#" class="btn btn-dark">More Details</a>
            </div>
            </div>
        </div>
        <div class="col-md">
            <div class="card" style="width: 18rem; margin: 10px auto;">
            <img src="../assets/HomeImage/image2.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Project B</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="#" class="btn btn-dark">More Details</a>
            </div>
            </div>
        </div>
        <div class="col-md">
            <div class="card" style="width: 18rem; margin: 10px auto;">
            <img src="../assets/HomeImage/image1.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Project C</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="#" class="btn btn-dark">More Details</a>
            </div>
            </div>
        </div>
        <div class="col-md">
            <div class="card" style="width: 18rem; margin: 10px auto;">
            <img src="../assets/HomeImage/image2.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Project D</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="#" class="btn btn-dark">More Details</a>
            </div>
            </div>
        </div>
    </div>
</div>
<div class="row" style="margin-top:50px">
    <div class="col">
        <router-link :to="{name:'projectView'}" class="btn btn-dark">More Project</router-link>
    </div>
</div>
</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>