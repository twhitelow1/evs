<template>
  <div class="Navigation">
    <!-- Navbar -->
      <nav class="navbar navbar-custom navbar-fixed-top">
        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar-brand-centered">
          <i class="fa fa-bars"></i>
          </button>
          <div class="navbar-brand-centered page-scroll">
            <a v-if="window.width > 990" href="#page-top"><img src="img/EVSlogo.png"  alt=""></a>
            <a v-if="window.width < 990" href="#page-top"><img src="img/evs-logo-landscape.png"  alt=""></a>
          </div>
        </div>
        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="navbar-brand-centered">
          <div class="container">
              <ul class="nav navbar-nav page-scroll navbar-left">
                <!-- <li><a href="#page-top">Home</a></li> -->
                <li><router-link :to="{path: '/', hash:'#page-top'}"> Home</router-link></li>
                <li><router-link :to="{path: '/', hash:'#services'}"> Services</router-link></li>
                <!-- <li><a href="https://eaglevalleysitters.com/#services">Services</a></li> -->
                <li><router-link :to="{path: '/', hash:'#rates'}">Rates</router-link></li>
                <!-- <li><a href="#rates">Rates</a></li> -->
                <li><a href="https://eaglevalleysitters.enginehire.io/application-form/195/4186">Book</a></li> 
              </ul>
              <ul class="nav navbar-nav page-scroll navbar-right">               
                <li><router-link :to="{path: '/', hash:'#about'}">About</router-link></li>
                <!-- <li><a href="#about">About</a></li> -->
                <li><a href="https://eaglevalleysitters.enginehire.io/application-form/195/4175">Apply</a></li>
                <!-- <li><a href="#application">Apply</a></li>  -->
                <!-- Dropdown -->
                <!-- <li class="dropdown active">
                  <a href="#" class="dropdown-toggle" data-toggle="dropdown">Contact<b class="caret"></b></a>
                  <ul class="dropdown-menu">
                    <li><a href="/faq">FAQ</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li class="divider"></li>
                    <li class="active"><a href="#latestblog">Latest Posts</a></li>
                  </ul>
                </li> -->
                <li><router-link :to="{path: '/', hash:'#activities'}">Activities</router-link></li>
                <!-- <li><a href="#activities">Activities</a></li> -->
                <li><router-link :to="{path: '/', hash:'#contact'}">Contact</router-link></li>
                <!-- <li><a href="#contact">Contact</a></li> -->

                  <!-- Dropdown -->
                  <!-- <li class="dropdown">
                  <a href="#" class="dropdown-toggle" data-toggle="dropdown">Pages<b class="caret"></b></a>
                  <ul class="dropdown-menu">
                    <li><a href="elements.html">Elements</a></li>
                    <li><a href="index_video.html">Video Header</a></li>
                    <li><a href="sidebar-page.html">Sidebar Page</a></li>
                    <li><a href="calendar.html">Calendar</a></li>
                  </ul>
                </li> -->
              </ul>
          </div>
        </div>
          <!-- /.navbar-collapse -->
      </nav>
      <!-- /navbar ends -->
  </div>
</template>

<style>
</style>

<script>
export default {
  data: function () {
    return {};
  },
  created: function () {},
  methods: {},
};
</script>

