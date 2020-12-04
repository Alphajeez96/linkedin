<template>
  <div>
    <linkNav />

    <div class="main">
      <div class="container">
        <div class="row">

          <div class="col-lg-8">
            <!-- Profile card here -->
            <div>
              <profileCard />
            </div>

          </div>

          <div class="col-lg-4">hhghggwjhd</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import linkNav from "~/components/partials/navbar";
import profileCard from "~/components/home/profile";
export default {
  components: {
    linkNav,
    profileCard,
  },
};
</script>

<style>
.main {
  background: #f3f2ef;
}
</style>
