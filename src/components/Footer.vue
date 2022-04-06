<template>
  <div class="footer">

    <div class="footer1 d-flex justify-content-between align-items-center p-3">
  </div>
      <!-- <Footer/> -->
  <footer class="d-flex justify-content-between align-items-center p-5">
    <div class="d-flex align-items-center">
      <a class="navbar-brand" href="#"><img src="@/assets/logo.png" alt="..." style="max-width:40px;"></a>
    </div>

    <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
      <h4 style="color:white">Follow Us : </h4>
      <li class="ms-3"><a class="text-muted" href="#"><i class="fa fa-facebook-official fa-2x" aria-hidden="true" style="color:white"></i></a></li>
      <li class="ms-3"><a class="text-muted" href="#"><i class="fa fa-twitter fa-2x" aria-hidden="true" style="color:white"></i></a></li>
      <li class="ms-3"><a class="text-muted" href="#"><i class="fa fa-instagram fa-2x" aria-hidden="true" style="color:white"></i></a></li>
      <li class="ms-3"><a class="text-muted" href="#"><i class="fa fa-discord-alt fa-2x" aria-hidden="true" style="color:white"></i></a></li>
      <li class="ms-3"><a class="text-muted" href="#"><i class="fa fa-youtube-play fa-2x" aria-hidden="true" style="color:white"></i></a></li>
    </ul>
  </footer>
<div class="footer2">
  <div style="margin:10px; color:white;">
      <a href="#">Privacy Policy</a> | 
      <a href="#">Term Of Use</a>
    </div>

    <div style="margin:10px; color:white;">
      <span>&copy; 2022 Need For Tree. Official licensed product, all rights reserved.</span>
    </div>
</div>
    <!-- <Footer/> -->
  </div>
</template>

<script>
export default {

}
</script>

<style>
footer {
  /* background-image: url(../assets/footer.jpg);
  background-size: contain; */
  background: black;
}

.footer1 {
  background-image: url(../assets/footer.jpg);
  background-size: contain;
  height: 200px;
}

.footer2 {
  background: black;
  padding: 10px;
}

a:link {
  color: white;

}
</style>