<template>
  <div>
    <linkNav />

    <div class="main">
      <div class="container">
        <div class="row">
          <div class="col-lg-8">
            <!-- Profile card here -->
            <div class="mb-3">
              <profileCard />
            </div>

            <!-- About card here -->
            <div class="mb-3">
              <about />
            </div>

            <!-- featured card here -->
            <div class="mb-3">
              <featured />
            </div>

            <!-- Dashboard card here -->
            <div class="mb-3">
              <dashboard />
            </div>
          </div>

          <div class="col-lg-4 mt-5">
              <!-- Tooltip card here -->
            <div class="mb-3" v-for="i in 3" :key="i">
              <toolTip />
            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import linkNav from "~/components/partials/navbar";
import profileCard from "~/components/home/profile";
import about from "~/components/home/about";
import featured from "~/components/home/featured";
import dashboard from "~/components/home/dashboard";
import experience from "~/components/home/experience";
import toolTip from '~/components/home/tool-tip';
import premium from '~/components/home/premium';
export default {
  components: {
    linkNav,
    profileCard,
    about,
    featured,
    dashboard,
    toolTip,
    premium
  },
};
</script>

<style>
.main {
  background: #f3f2ef;
}
.col-lg-4 {
    flex: 0 0 30.333333%;
    max-width: 30.333333%;
}
.col-lg-8 {
    flex: 1 0 66.666667%;
    max-width: 70.666667%;
}
</style>
