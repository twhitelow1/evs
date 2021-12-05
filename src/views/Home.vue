
<template>
  <div class="home">
    <!-- Page width 'Boxed' of 'Full' -->
    <slider></slider>
    <services></services>
    <callout></callout>
	  <about></about>
    <team></team>
	  
      <!-- Parallax object -->
      <div class="parallax-object1 hidden-sm hidden-xs" data-0="opacity:1;"
         data-100="transform:translatey(40%);"
         data-center-center="transform:translatey(-180%);">
         <!-- Image -->
         <img src="img/parallaxobject1.png" alt="">
      </div>
      <activities></activities>
	  
      <!-- Parallax object -->
      <!-- <div class="parallax-object2 hidden-sm hidden-xs" data-0="opacity:1;"
         data-start="margin-top:40%"
         data-100="transform:translatey(0%);"
         data-center-center="transform:translatey(-180%);"> -->
         <!-- Image -->
         <!-- <img src="img/parallaxobject2.png" alt="">
      </div> -->
      <!-- Parallax object -->
      <div class="parallax-object3 hidden-sm hidden-xs" data-0="opacity:1;"
         data-100="transform:translatex(0%);"
         data-center-center="transform:translatex(380%);">
         <!-- Image -->
         <img src="img/parallaxobject3.png" alt="">
      </div>
	  <rates></rates>
    
      <!-- Section Call to Action -->
      <section id="call-to-action" class="small-section">
         <div class="container text-center">
            <div class="col-lg-6 col-lg-offset-6 col-sm-6">
			<div class="well">
               <!-- Section heading -->
               <h3>Get more Information</h3>
               <p>Lorem av ipsum dolor sit amet, dorem ipsuem ore consectetur adipisicing elit semprem Ratione, voluptatem, dolorem animi nisi autem blanditiis enim culpa reiciendis et em explicabo tenetur lore apsuet!</p>
               <!-- Button -->
				   <div class="page-scroll">
					  <a class="btn" href="#about">About Us</a>
				   </div>
			     <!--/page-scroll -->
			   </div>
			   <!--/well -->
            </div>
            <!--/col-lg-6 -->
         </div>
         <!-- /container-->
      </section>
      <!-- Section ends -->
	  
      <!-- Section Contact -->
      <section id="contact" class="color-section">
         <div class="container">
            <div class="col-lg-8 col-lg-offset-2">
               <!-- Section heading -->
               <div class="section-heading">
                  <h2>Contact us</h2>
               </div>
            </div>
            <!-- Contact -->
            <div class="col-lg-4 text-center">
               <h4>Information</h4>  
               <!-- contact info -->			   
               <div class="contact-info">
				   <p><i class="flaticon-back"></i><a href="mailto:cat@eaglevalleysitters.com">cat@eaglevalleysitters.com</a></p>
					<p><i class="fa fa-phone margin-icon"></i>Call us at (970) </p>
				 </div>
                  <!-- address info -->
                  <p>We are located at Imaginary Fun City, 304.</p>
                <!-- Map -->
                <!-- <div id="map-canvas"></div> -->
            </div>
            <!-- Contact Form -->
            <div class="col-lg-7 col-lg-offset-1">
               <h4>Write us</h4>
				<!-- Form Starts -->
               <div id="contact_form">
                  <div class="form-group">
                     <input type="text" name="name" class="form-control input-field" placeholder="Name" required="">                    
                     <input type="email" name="email" class="form-control input-field" placeholder="Email ID" required="">           
                     <input type="text" name="subject" class="form-control input-field" placeholder="Subject" required="">                     
                  </div>
                  <textarea name="message" id="message" class="textarea-field form-control" rows="4" placeholder="Enter your message" required=""></textarea>
                  <button type="submit" id="submit_btn" value="Submit" class="btn center-block">Send message</button>
               </div>
			   <!-- Contact results -->
               <div id="contact_results"></div>
            </div>
            <!--/Contact form -->
         </div>
         <!-- /container-->
      </section>
      <!--Section ends -->
	  
      
  </div>
</template>

<style>
</style>

<script>
import Callout from "../components/Callout.vue";
import Services from "../components/Services.vue";
import Slider from "../components/Slider.vue";
import About from "../components/About.vue";
import Team from "../components/Team.vue";
import Activities from "../components/Activities.vue";
import Rates from "../components/Rates.vue";

export default {
  data: function () {
    return {};
  },
  created: function () {},
  methods: {},
  components: {
    Slider,
    Services,
    Callout,
    About,
    Team,
    Activities,
    Rates,
  },
};
</script>

