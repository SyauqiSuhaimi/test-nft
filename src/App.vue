<template>

<div v-if="!hideDonate">
  <div class="notification-top-bar row m-0">
  <div class="col-4"></div><div class="col-4 d-flex justify-content-center align-items-center"><a href="#">Donate Now</a></div><div class="col-4 d-flex justify-content-end align-items-center"><button @click="hideDonate=true" type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button></div>
  </div>
  <Header style="position:absolute; z-index:1; width:100%; transform: translateY(10%)"/>
  
  <router-view/>

  <Footer/>
</div>
<div v-else>
<Header style="position:absolute; z-index:1; width:100%;"/>
  
  <router-view/>

  <Footer/>
</div>




</template>

<script>

import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
export default {
  data() {
    return {

      hideDonate: false,
    }
  },
  components: {
    Header,
    Footer
  }

}

// var numLoads = parseInt(getCookie('pageLoads'), 10);

// if (isNaN(numLoads) || numLoads <= 0) { setCookie('pageLoads', 1); }
// else { setCookie('pageLoads', numLoads + 1); }

// console.log(getCookie('pageLoads'));

// function setCookie (cookieName, cookieValue, nDays) {
//         var today  = new Date(),
//             expire = new Date();

//         if (nDays === null || nDays === 0) { 
//             nDays = 1;
//         }

//         expire.setTime(today.getTime() + 3600000 * 24 * nDays);

//         document.cookie = cookieName + "=" + escape(cookieValue) + ";expires=" + expire.toGMTString();
//     };

// function getCookie (cookieName) {
//         var theCookie = " " + document.cookie,
//             ind = theCookie.indexOf(" " + cookieName + "=");

//         if (ind === -1) { ind = theCookie.indexOf(";" + cookieName + "="); }
//         if (ind === -1 || cookieName === "") { return ""; }

//         var ind1 = theCookie.indexOf(";", ind + 1);

//         if (ind1 === -1) { ind1 = theCookie.length; }

//         return unescape(theCookie.substring(ind + cookieName.length + 2, ind1));
//     };
    
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  text-align: center;
  color: #2c3e50;
}


.notification-top-bar {
  line-height: 40px;
  width: 100%;
  background: #00B050;
  text-align: center;
  color: #FFFFFF;
  font-family: sans-serif;
  font-weight: lighter;
}

.notification-top-bar a {
  color: white;
  font-weight: bold;
}

.notification-top-bar a:hover {
  color: rgb(4, 139, 47);
  font-weight: bold;
}

</style>
