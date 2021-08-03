<template>
  <div class="section section-examples" data-background-color="white">
    <!-- data-background-color="black" -->
    <div class="space-50"></div>
      <div class="container text-center">
        <div class="row" style="display: flex; flex-wrap: flex;">

          <div class="col" style="background-color: black; margin: 15px;">
            <router-link to="/Aboutme" target="_blank">
              <!-- <img src="img/landing.jpg" alt="Image" class="img-raised" /> -->
              <i class="fas fa-user" style="font-size: 100px; margin-top: 90px; margin-bottom: 20px;"></i>
            </router-link>
            <div>
              <router-link
                to="/Aboutme"
                class="btn btn-simple btn-primary btn-round"
                style="margin-bottom: 70px;"
                >About Me
              </router-link>
            </div>
          </div>

          <div class="col" style="background-color: black; margin: 15px;">
            <router-link to="/Professional" target="_blank">
              <i class="fas fa-briefcase" style="font-size: 100px; margin-top: 90px; margin-bottom: 20px;"></i>
            </router-link>
            <div>
              <router-link
                to="/Professional"
                class="btn btn-simple btn-primary btn-round"
                style="margin-bottom: 70px;"
                >Experience</router-link
              >
            </div>
          </div>

          <div class="col" style="background-color: black; margin: 15px;">
            <router-link to="/Projects" target="_blank">
              <i class="fas fa-folder" style="font-size: 100px; margin-top: 90px; margin-bottom: 20px;"></i>
            </router-link>
            <div>
              <router-link
                to="/Projects"
                class="btn btn-simple btn-primary btn-round"
                style="margin-bottom: 70px;"
                >Projects</router-link
              >
            </div>
          </div>

        </div>

        <div class="row" style="display: flex; flex-wrap: flex;">

          <div class="col" style="background-color: black; margin: 15px;">
            <router-link to="/Coursework" target="_blank">
              <i class="fas fa-graduation-cap" style="font-size: 100px; margin-top: 90px; margin-bottom: 20px;"></i>
            </router-link>
            <div>
              <router-link
                to="/Coursework"
                class="btn btn-simple btn-primary btn-round"
                style="margin-bottom: 70px;"
                >Coursework</router-link
              >
            </div>
          </div>

          <div class="col" style="background-color: black; margin: 15px;">
            <router-link to="/Leadership" target="_blank">
              <i class="fas fa-users" style="font-size: 100px; margin-top: 90px; margin-bottom: 20px;"></i>
            </router-link>
            <div>
              <router-link
                to="/Leadership"
                class="btn btn-simple btn-primary btn-round"
                style="margin-bottom: 70px;"
                >Leadership</router-link
              >
            </div>
          </div>

          <div class="col" style="background-color: black; margin: 15px;">
            <router-link to="/Awards" target="_blank">
              <i class="fas fa-trophy" style="font-size: 100px; margin-top: 90px; margin-bottom: 20px;"></i>
            </router-link>
            <div>
              <router-link
                to="/Awards"
                class="btn btn-simple btn-primary btn-round"
                style="margin-bottom: 70px;"
                >Awards</router-link
              >
            </div>
          </div>

        </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style></style>
