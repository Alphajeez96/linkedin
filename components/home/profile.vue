<template>
  <div class="">
    <div class="profile__card mt-5">
      <!-- Background Here -->
      <div class="bg__img">
        <div class="d-flex p-4 justify-content-end">
          <div class="upload__div">
            <i
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="upload__svg"
                viewBox="0 0 16 16"
                data-supported-dps="16x16"
                fill="currentColor"
                width="16"
                height="16"
                focusable="false"
              >
                <path
                  d="M14 4h-1.75l-1-2h-6.5l-1 2H2a1 1 0 00-1 1v7a1 1 0 001 1h12a1 1 0 001-1V5a1 1 0 00-1-1zm-1 7H3V8h2a3 3 0 006 0h2v3zm-2.87-3A2.13 2.13 0 118 5.88 2.13 2.13 0 0110.13 8zM13 7h-2.18a3 3 0 00-5.64 0H3V6h2l1-2h4l1 2h2v1z"
                ></path></svg
            ></i>
          </div>
        </div>
      </div>

        <!-- Profile section Here -->
        <div class="d-flex position-relative px-4 mb-5 pb-5">
  
       <!-- Profile Image Here -->
        <div class="position-absolute profile__img">
  <img src="../../assets/img/user.png" width="170" height="170" class='rounded-circle' alt="User">
        </div>

<div class="ml-auto">
kk
</div>
        </div>
    </div>
  </div>
</template>

<style scoped>
.profile__card {
  border-top-left-radius: var(--corner-radius);
  border-top-right-radius: var(--corner-radius);
  border: 1px solid var(--border-color);
  background: white;
}
.bg__img {
  background-image: url("../../assets/img/bg-img.svg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  border-top-left-radius: var(--corner-radius);
  border-top-right-radius: var(--corner-radius);
  border: 1px solid var(--border-color);
  height: 198px;
}
.upload__div {
  background: white;
  border-radius: 50%;
  padding: 4px 8px;
}
.upload__svg {
  fill: #0a66c2;
}
.profile__img{
border-radius: 50%;
    bottom: -2px;
    border: 4px solid white;
    background-color: white;
}
</style>