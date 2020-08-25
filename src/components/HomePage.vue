// try finding slide in transition
<template>
  <div>
    <div class="headtop prelative">
      <carousel
        :perPage="1"
        :navigationEnabled="true"
        :paginationEnabled="true"
        navigationNextLabel=" "
        navigationPrevLabel=" "
        :loop="true"
        :autoplay=true
        :paginationPadding="1"
        :autoplayTimeout="10000"
        :speed="500"
        paginationActiveColor="#37bdae"
      >
        <slide>
          <img src="../assets/carousal/1.jpg" />
        </slide>
        <slide>
          <img src="../assets/carousal/2.jpg" />
        </slide>
        <slide>
          <img src="../assets/carousal/3.jpg" />
        </slide>
        <slide>
          <img src="../assets/carousal/4.jpg" />
        </slide>
      </carousel>
    </div>
    <br>

    <hr>


<div class="container">
    <h1 class="text-center">Products</h1>
    <!-- Grid row -->
<div class="row">

  <!-- Grid column -->
  
  <!-- Grid column -->

</div>
<!-- Grid row -->
<!-- <p class="text-center">Check out our photos</p> -->
<!-- Grid row -->
<div class="gallery" id="gallery">



  <!-- Grid column -->
  <div class="img-hover-zoom mb-3 pics animation all 2">
    <img class="img-fluid" src="../assets/grid/5.jpeg" alt="Card image cap">
  </div>
  <!-- Grid column -->

  <!-- Grid column -->
  <div class="img-hover-zoom mb-3 pics animation all 1">
    <img class="img-fluid" src="../assets/grid/1.jpeg" alt="Card image cap">
  </div>
  <!-- Grid column -->

  <!-- Grid column -->
  <div class="img-hover-zoom mb-3 pics animation all 1">
    <img class="img-fluid" src="../assets/grid/2.jpeg" alt="Card image cap">
  </div>
  <!-- Grid column -->

  <!-- Grid column -->
  <div class="img-hover-zoom mb-3 pics animation all 2">
    <img class="img-fluid" src="../assets/grid/6.jpeg" alt="Card image cap">
  </div>
  <!-- Grid column -->

  <!-- Grid column -->
  <div class="img-hover-zoom mb-3 pics animation all 2">
    <img class="img-fluid" src="../assets/grid/7.jpeg" alt="Card image cap">
  </div>
  <!-- Grid column -->

  <!-- Grid column -->
  <div class="img-hover-zoom mb-3 pics animation all 1">
    <img class="img-fluid" src="../assets/grid/3.jpeg" alt="Card image cap">
  </div>
  <!-- Grid column -->

</div>
<!-- Grid row -->


</div>

<br>
    
  </div>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";


export default {
  name: "HomePage",
  components: {
    Carousel,
    Slide,
  },
};



</script>

<style scoped>

/* [1] The container */
.img-hover-zoom {
  /* height: 300px; [1.1] Set it as per your need */
  overflow: hidden; /* [1.2] Hide the overflowing of child elements */
}

/* [2] Transition property for smooth transformation of images */
.img-hover-zoom img {
  transition: transform 1s ease;
}

/* [3] Finally, transforming the image when container gets hovered */
.img-hover-zoom:hover img {
  transform: scale(1.1);
}




h2 { 
   position: absolute; 
   top: 200px; 
   left: 30px; 
   width: 100%; 
}
h2 span { 
   color: white; 
   font: bold 24px/45px Helvetica, Sans-Serif; 
   letter-spacing: -1px;  
   background: rgb(0, 0, 0); /* fallback color */
   background: rgba(0, 0, 0, 0.7);
   padding: 10px; 
}
h2 span.spacer {
   padding:0 5px;
}


.gallery {
-webkit-column-count: 3;
-moz-column-count: 3;
column-count: 3;
-webkit-column-width: 33%;
-moz-column-width: 33%;
column-width: 33%; }
.gallery .pics {
-webkit-transition: all 350ms ease;
transition: all 350ms ease; }
.gallery .animation {
-webkit-transform: scale(1);
-ms-transform: scale(1);
transform: scale(1); }

@media (max-width: 450px) {
.gallery {
-webkit-column-count: 1;
-moz-column-count: 1;
column-count: 1;
-webkit-column-width: 100%;
-moz-column-width: 100%;
column-width: 100%;
}
}

@media (max-width: 400px) {
.btn.filter {
padding-left: 1.1rem;
padding-right: 1.1rem;
}
}




</style>
