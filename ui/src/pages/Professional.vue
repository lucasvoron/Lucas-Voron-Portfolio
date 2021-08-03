<template>
  <div>
    <div class="page-header page-header-small clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image: url('img/code_image1.png')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Professional Experience</h1>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto text-left">
            <!-- <h2 class="title">Computer Science and Engineering Major at Santa Clara University</h2> -->
            <h3 class="title">INRIX - Software Development Engineer Intern</h3>
            <h4 class="subtitle">
              June - Sept. 2021
            </h4>
            <h5 class="description">
              Focused on front-end UI development of traffic data products to transform the company’s scope from solely DaaS
              to a hybrid model that includes SaaS.
              Contributed to all aspects of the end-end design experience partnering with UX, back-end developers, and
              product management to produce live-updating product web pages.
              Developed code to handle queries of API data responses through GraphQL layer to display information.
            </h5>
            <h3 class="title">Santa Clara University - Resident Assistant</h3>
            <h4 class="subtitle">
              Sept. 2020 - Present
            </h4>
            <h5 class="description">
              One of five student leaders managing a Residential Living Community of 300+ students 24/7.
              Responsible for safety, compliance, mentoring, and student engagement to promote and support an environment
              of diversity and inclusion.
            </h5>
            <h3 class="title">Santa Clara University - Career Center Assistant</h3>
            <h4 class="subtitle">
              Sept. 2019 - Aug. 2021
            </h4>
            <h5 class="description">
              Collaborate with external recruiters to facilitate on-campus interviewing, networking sessions, and career fairs as
              well as coaching students on career strategies and methods to leverage existing tools on a daily basis.
            </h5>
            <h3 class="title">Tiposi Inc. - Medical Device Design Consultation</h3>
            <h4 class="subtitle">
              Nov. 2020
            </h4>
            <h5 class="description">
              Worked directly with the lead project engineer and CEO to create the colors, materials, and finishes of a wearable medical device prototype.
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
