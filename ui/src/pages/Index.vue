<template>
  <div>
    <div class="page-header clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image:url('img/linkedin_bg.png')"
      >
      </parallax>
      <div class="container mt-5">
        <div class="container">
          <div class="content-center brand">
            <img src="img/linkedin_profile.png" alt="" 
              class = "rounded-circle img-raised"
              contain
              style="max-width: 300px;"
            />
            <!-- height="300px"
            width="300px" -->
            <div>
              <h1 class="h1 mt-5">LUCAS VORON</h1>
              <h3>Driven to use creative thinking to promote innovation.</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container" style="margin-top: 100px;">
      <h1 class="title">
        Languages
      </h1>
      <h3 class="subtitle">
        C | C++ | JavaScript | CSS | Node.js | Vue.js | React Native | PHP | HTML | VHDL | MATLAB | English | French
      </h3>
      <h1 class="title">
        Tools
      </h1>
      <h3 class="subtitle">
        Figma | Photoshop | Illustrator | Unity | Command Line | Multisim | Oscilloscope
      </h3>
      <h1 class="title">
        Databases
      </h1>
      <h3 class="subtitle">
        Azure | Google Firebase
      </h3>
    </div>
    <!-- <div class="main">
      <div class="section section-images">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="hero-images-container">
                <img src="img/hero-image-1.png" alt="" />
              </div>
              <div class="hero-images-container-1">
                <img src="img/hero-image-2.png" alt="" />
              </div>
              <div class="hero-images-container-2">
                <img src="img/hero-image-3.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div> -->
    <!-- <basic-elements></basic-elements>
    <navigation></navigation>
    <tabs-section></tabs-section>
    <progress-pagination></progress-pagination>
    <notifications></notifications>
    <typography></typography>
    <javascript-components></javascript-components>
    <carousel-section></carousel-section>
    <nucleo-icons-section></nucleo-icons-section>
    <div class="section">
      <div class="container text-center">
        <div class="row justify-content-md-center">
          <div class="col-md-12 col-lg-8">
            <h2 class="title">Completed with examples</h2>
            <h5 class="description">
              The kit comes with three pre-built pages to help you get started
              faster. You can change the text and images and you're good to go.
              More importantly, looking at them will give you a picture of what
              you can built with this powerful Bootstrap 4 ui kit.
            </h5>
          </div>
        </div>
      </div>
    </div> -->
    <!-- <signup-form></signup-form> -->
    <examples-section></examples-section>
    <!-- <download-section></download-section> -->
  </div>
</template>
<script>
import { Parallax } from '@/components';
import BasicElements from './components/BasicElementsSection';
import Navigation from './components/Navigation';
import TabsSection from './components/Tabs';
import ProgressPagination from './components/ProgressPagination';
import Notifications from './components/Notifications';
import Typography from './components/Typography';
import JavascriptComponents from './components/JavascriptComponents';
import CarouselSection from './components/CarouselSection';
import NucleoIconsSection from './components/NucleoIconsSection';
// import SignupForm from './components/SignupForm';
import ExamplesSection from './components/ExamplesSection';
// import DownloadSection from './components/DownloadSection';

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
    // BasicElements,
    // Navigation,
    // TabsSection,
    // ProgressPagination,
    // Notifications,
    // Typography,
    // JavascriptComponents,
    // CarouselSection,
    // NucleoIconsSection,
    // SignupForm,
    ExamplesSection
    // DownloadSection
  }
};
</script>
<style></style>
