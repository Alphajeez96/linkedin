<template>
  <div>
    <linkNav />

    <div class="main">
      <div class="container">
        <div class="row">

          <div class="col-lg-9">
            <!-- Profile card here -->
            <div class="mb-2">
              <profileCard />
            </div>

                 <!-- About card here -->
            <div class="mb-2">
              <about />
            </div>

                  <!-- featured card here -->
            <div class="mb-2">
              <featured />
            </div>

          </div>

          <div class="col-lg-3">hhghggwjhd</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import linkNav from "~/components/partials/navbar";
import profileCard from "~/components/home/profile";
import about from '~/components/home/about';
import featured from '~/components/home/featured'
export default {
  components: {
    linkNav,
    profileCard,
    about,
    featured
  },
};
</script>

<style>
.main {
  background: #f3f2ef;
}
</style>
