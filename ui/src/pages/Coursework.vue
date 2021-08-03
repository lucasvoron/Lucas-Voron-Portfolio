<template>
  <div>
    <div class="page-header page-header-small clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image: url('img/code_image2.png')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Relevant Coursework</h1>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto text-left">
            <!-- <h2 class="title">Computer Science and Engineering Major at Santa Clara University</h2> -->
            <h3 class="title">
              Classes
            </h3>
            <h4 class="subtitle">
              Object Oriented Programming <br>
              Data Structures <br>
              Algorithims <br>
              Embedded Systems <br>
              Operating Systems <br>
              Computer Networks <br>
            </h4>
            <h3 class="title">Project - Scheduling Program</h3>
            <h4 class="subtitle">
              Sept. - Dec. 2020
            </h4>
            <h5 class="description">
              Wrote scheduling programming for a small business in C language.
              Became familiar with using Terminal and Linux command line to code and test programs.
              Added multiple functionalities in scheduling systems and demonstrated proficiency in working
              extensively with various data structures.
            </h5>
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
