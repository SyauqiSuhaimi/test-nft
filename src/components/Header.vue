<template>
<div class="head">
  
  <!-- <Header/> -->
  <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
  <div class="container" style="font-size: 120%;">
    <a class="navbar-brand" href="/"><img src="@/assets/logo.png" alt="..." style="max-width:70px;"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item px-3">
          <!-- <a class="nav-link" aria-current="page" href="#">Home</a> -->
          <router-link to="/" class="nav-link">Home</router-link>
        </li>
        <li class="nav-item px-3">
          <!-- <a class="nav-link" href="#">Project</a> -->
          <router-link :to="{name:'ContactUs'}" class="nav-link" @click="scrollToTop()">Save The Rainforest</router-link>
        </li>
        <li class="nav-item px-3">
          <!-- <a class="nav-link" href="#">News</a> -->
          <router-link :to="{name:'FAQ'}" class="nav-link" @click="scrollToTop()">FAQ</router-link>
        </li>
        <li class="nav-item px-3">
          <!-- <a class="nav-link" href="#">Contact Us</a> -->
          <router-link :to="{name:'about'}" class="nav-link">Contact Us</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
  <!-- <Header/> -->
</div>

</template>

<script>
export default {
  methods: { 
  scrollToTop() {
    window.scrollTo(0,0);
  }
}

}

window.addEventListener('DOMContentLoaded', event => {

    // Navbar shrink function
    var navbarShrink = function () {
        const navbarCollapsible = document.body.querySelector('#mainNav');
        if (!navbarCollapsible) {
            return;
        }
        if (window.scrollY === 0) {
            navbarCollapsible.classList.remove('navbar-shrink')
        } else {
            navbarCollapsible.classList.add('navbar-shrink')
        }

    };

    // Shrink the navbar 
    navbarShrink();

    // Shrink the navbar when page is scrolled
    document.addEventListener('scroll', navbarShrink);

    // // Activate Bootstrap scrollspy on the main nav element
    // const mainNav = document.body.querySelector('#mainNav');
    // if (mainNav) {
    //     new bootstrap.ScrollSpy(document.body, {
    //         target: '#mainNav',
    //         offset: 74,
    //     });
    // };

});
</script>

<style>

@media (min-width: 992px) {
    #mainNav {
    /* padding-top: 0;
    padding-bottom: 0; */
    border-bottom: none;
    background-color: transparent;
    transition: background-color 0.3s ease-in-out;
    font-weight: bolder;
    letter-spacing: 1px;
    
}

 #mainNav a.nav-link {
      color: #fff;
    }

    #mainNav.navbar-shrink a.nav-link {
      color: rgb(157, 157, 157);
    }
}


  #mainNav.navbar-shrink {
    background-color: #fff;
  }

  /* #mainNav.nav-link.active {
    color: black;
    outline: none;
    border-bottom: 0.25rem solid black;
} */

/* #mainNav.navbar-shrink .nav-link.active {
    color: black;
    outline: none;
    border-bottom: 0.25rem solid black;
} */

#mainNav a.router-link-exact-active {
    color: #48f398;
    outline: none;
    border-bottom: 0.25rem solid #48f398;
}

#mainNav.navbar-shrink a.router-link-exact-active {
    color: #48f398;
    outline: none;
    border-bottom: 0.25rem solid #48f398;
}

#mainNav a.nav-link:hover {
    color: #48f398;
    outline: none;
    border-bottom: 0.25rem solid #48f398;
}


/* ///////////// Mobile View /////////////////////////// */
@media (max-width: 991px) {
    #mainNav {
        min-height: 3.5rem;
    background-color: #fff;
    
    }
   
}


/* ///////////// Mobile View /////////////////////////// */

</style>