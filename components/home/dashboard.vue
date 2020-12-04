<template>
  <div>
    <div class="about__card">
      <div class="px-4 pt-4 pb-3">
        <h4>Your Dashboard</h4>
        <div class="d-flex">
          <div><p class="private">Private to you</p></div>

          <div class="ml-auto d-flex">
            <i
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                data-supported-dps="24x24"
                fill="currentColor"
                width="24"
                height="24"
                focusable="false"
              >
                <path
                  d="M12 5.66l1 2 2.24.34-1.62 1.57.38 2.23-2-1.05-2 1.05.38-2.23L8.76 8 11 7.67l1-2m0-3.91L9.84 6.07 5 6.77l3.5 3.41L7.67 15 12 12.73 16.33 15l-.83-4.82L19 6.77l-4.84-.7L12 1.75zM11 15h2v7h-2v-7zm4 2h2v4h-2v-4zm-8 0h2v4H7v-4z"
                ></path></svg
            ></i>
            <p class="all__star">All Star</p>
          </div>
        </div>

        <div class="my-1 px-3 d-flex pb-2 inner__card">
          <div class="col-lg-4">
            <div class="d-flex pt-1 flex-column">
              <h2>26</h2>
              <p>Who Viewed your profile</p>
            </div>
          </div>

          <div class="col-lg-4 border__left">
            <div class="d-flex pt-1 flex-column">
              <h2>53</h2>
              <p>Post Views</p>
            </div>
          </div>

          <div class="col-lg-4 border__left">
            <div class="d-flex pt-1 flex-column">
              <h2>2</h2>
              <p>Search Appearances</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.about__card {
  border-radius: var(--corner-radius);
  border: 1px solid var(--border-color);
  background: #dce6f1;
}
.border__left {
  height: 86px;
  border-left: 1px solid var(--border-color);
}
.private {
  color: var(--black);
  font-size: 1rem;
  font-style: italic;
}
.all__star {
  font-size: 0.875rem;
  font-weight: 600;
}
.inner__card {
  background: white;
  border-radius: var(--corner-radius);
  border: 1px solid var(--border-color);
  height: 86px;
}
h4 {
  color: rgba(0, 0, 0, 0.9);
  font-size: 1.25rem;
  font-weight: normal;
}
p {
  color: rgba(0, 0, 0, 0.9);
  font-size: 0.875rem;
}
h2 {
  color: #0a66c2;
  font-size: 2rem;
  font-weight: normal;
}
</style>