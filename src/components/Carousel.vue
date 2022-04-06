<template>
  <div class="carousel">
      
<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="../assets/HomeImage/image1.jpg" class="d-block w-100" style="max-height: 700px;" alt="...">
      <div class="carousel-caption">
        <h1 class="captions display-3 text-start">Only USD0.01 a day, you can protect the rainforest for 30 years from destruction.</h1>
      </div>
    </div>
    <!-- <div class="carousel-item">
      <img src="../assets/HomeImage/image2.jpg" class="d-block w-100" style="max-height: 700px;" alt="...">
      <div class="carousel-caption">
        <h1 class="captions display-3 text-start">Only USD0.01 a day, you can protect the rainforest for 30 years from destruction.</h1>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../assets/HomeImage/image1.jpg" class="d-block w-100" style="max-height: 700px;" alt="...">
      <div class="carousel-caption">
        <h1 class="captions display-3 text-start">Only USD0.01 a day, you can protect the rainforest for 30 years from destruction.</h1>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../assets/HomeImage/image2.jpg" class="d-block w-100" style="max-height: 700px;" alt="...">
      <div class="carousel-caption">
        <h1 class="captions display-3 text-start">Only USD0.01 a day, you can protect the rainforest for 30 years from destruction.</h1>
      </div>
    </div> -->
  </div>
  <!-- <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button> -->
</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.carousel-inner {
  position: relative;
}

.carousel-inner img {
  width: 100%;
  height: auto;
}

.carousel-inner .btn {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, 500%);
  -ms-transform: translate(-50%, -50%);
  background-color: rgb(255, 255, 255);
  color: rgb(0, 0, 0);
  font-size: 16px;
  padding: 12px 24px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  text-align: center;
}

.carousel-inner .btn:hover {
  background-color: rgb(163, 163, 163);
}

.carousel-caption {
  top: 200px;
  bottom: auto;
}

.captions {
  font-weight:bolder; 
  text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;
}
</style>