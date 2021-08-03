<template>
  <div>
    <div class="page-header page-header-small clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image: url('img/unity_image.png')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Personal Projects</h1>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto text-left">
            <!-- <h2 class="title">Computer Science and Engineering Major at Santa Clara University</h2> -->
            <h3 class="title">Xbox Game Development - Dungeon Escape</h3>
            <h4 class="subtitle">
              June - July. 2021
            </h4>
            <h5 class="description">
              Designed and implemented a game called Dungeon Escape using Unity Engine.
              Integrated new assets and game objects to create an interactive 3D game for Xbox console.
            </h5>
            <h3 class="title">Mobile App Development - Digits</h3>
            <h4 class="subtitle">
              Oct. - Nov. 2020
            </h4>
            <h5 class="description">
              Invented a new concept for a dating app that was implemented using JavaScript and React Native.
              Worked on using Google Firebase to develop in-app messaging.
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
