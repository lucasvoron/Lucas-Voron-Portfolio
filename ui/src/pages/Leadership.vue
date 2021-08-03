<template>
  <div>
    <div class="page-header page-header-small clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image: url('img/lucas_leadership.jpeg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Leadership Experience</h1>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto text-left">
            <!-- <h2 class="title">Computer Science and Engineering Major at Santa Clara University</h2> -->
            <h3 class="title">Zommunity Leader</h3>
            <h4 class="subtitle">
              2020 - 2021
            </h4>
            <h5 class="description">
              Volunteer role to support and develop peer community during Covid-19.
            </h5>
            <h3 class="title">Xavier Leadership Council - Vice President</h3>
            <h4 class="subtitle">
              2019-2020
            </h4>
            <h5 class="description">
              Vice president of residential community leadership council.
            </h5>
            <h3 class="title">IEEE Member</h3>
            <h4 class="subtitle">
              2019 - Present
            </h4>
            <h5 class="description">
              Active member of IEEE to develop community among EE students.
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
