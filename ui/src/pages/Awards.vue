<template>
  <div>
    <div class="page-header page-header-small clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image: url('img/linkedin_bg2.png')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Awards & Achievements</h1>
          <!-- <div class="text-center">
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-facebook-square"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-google-plus"></i>
            </a>
          </div> -->
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-12 mr-auto">
            <h2 class="title">Microsoft Best Use of Azure</h2>
            <h4 class="subtitle">
              Hack for Humanity (Feburary 2021) 
              <a
                class="link"
                href="https://devpost.com/software/quick-bites"
              >
                <i class="fas fa-newspaper"></i>
              </a>
            </h4>
            <h5 class="description">
              My team and I developed a website called Quick Bites whose foundation was the Microsoft developer tool, Azure. 
              The mission of our website was to combat food-insecurity in a number of creative ways.
              Users of our website could donate directly to the site where food insecure users could order their groceries online.
              If users did not have money to donate, they could also post recipies of affordable, healthy meals that other users could take advantage of!
              We were awarded with best use of Azure from Microsoft in this Hack for Humanity competition.
            </h5>
          </div>
        </div>
        
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-4">
              <div
                class="image-container"
                style="background-image: url('img/microsoft_logo.jpg')"
              >
              </div>
            </div>
            <div class="col-md-8">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="background-image: url('img/microsoft_group.jpg')"
              ></div>
            </div>
          </div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-md-12 mr-auto">
            <h2 class="title">Entrepreneurhsip Award</h2>
            <h4 class="subtitle">
              ENGR 1 Final Competition (December 2019) 
              <a
                class="link"
                href="https://devpost.com/software/quick-bites"
              >
                <i class="fas fa-newspaper"></i>
              </a>
            </h4>
            <h5 class="description">
              My team and I developed a website called Quick Bites whose foundation was the Microsoft developer tool, Azure. 
              The mission of our website was to combat food-insecurity in a number of creative ways.
              Users of our website could donate directly to the site where food insecure users could order their groceries online.
              If users did not have money to donate, they could also post recipies of affordable, healthy meals that other users could take advantage of!
              We were awarded with best use of Azure from Microsoft in this Hack for Humanity competition.
            </h5>
          </div>
        </div>
        
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-4">
              <div
                class="image-container"
                style="background-image: url('img/scu.png')"
              >
              </div>
            </div>
            <div class="col-md-8">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="background-image: url('img/code_image3.png')"
              ></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Button, FormGroupInput } from '@/components';
export default {
  name: 'landing',
  bodyClass: 'landing-page',
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput
  },
  data() {
    return {
      form: {
        firstName: '',
        email: '',
        message: ''
      }
    };
  }
};
</script>
<style></style>
