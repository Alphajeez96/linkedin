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
      <div class="d-flex position-relative px-4">
        <!-- Profile Image Here -->
        <div class="position-absolute profile__img">
          <img
            src="../../assets/img/user.png"
            width="170"
            height="170"
            class="rounded-circle"
            alt="User"
          />
        </div>

        <!-- Buttons Here -->
        <div class="ml-auto mt-3">
          <button class="btn_ rounded-pill py-1 px-3 Add__btn">
            Add profile section
            <span class="mx-1"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 16 16"
                data-supported-dps="16x16"
                fill="currentColor"
                class="mercado-match"
                width="16"
                height="16"
                focusable="false"
              >
                <path d="M8 11L3 6h10z" fill-rule="evenodd"></path></svg
            ></span>
          </button>

          <button class="btn_ rounded-pill py-1 px-3 mx-2 more__btn">
            More...
          </button>

          <button class="btn_ rounded-pill py-1 px-3 edit__btn">
            <i
              ><svg
                class="pencil"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                data-supported-dps="24x24"
                fill="currentColor"
                width="24"
                height="24"
                focusable="false"
              >
                <path
                  d="M21.13 2.86a3 3 0 00-4.17 0l-13 13L2 22l6.19-2L21.13 7a3 3 0 000-4.16zM6.77 18.57l-1.35-1.34L16.64 6 18 7.35z"
                ></path></svg
            ></i>
          </button>
        </div>
      </div>

      <!--Bio Here -->
      <div class="px-4 d-flex pt-4 pb-3">
        <div>
          <h4>Prince Chukwudire</h4>
          <h5>Frontend Developer | Javascript Enthusiast</h5>
          <p class="location">
            Port Harcourt, Rivers, Nigeria <span>&#183;</span>
            <span class="connect">
              <a href="https://github.com/Alphajeez96" target="_blank"
                >276 connections</a
              >
            </span>
            <span>&#183;</span>
            <span class="connect"
              ><a href="https://github.com/Alphajeez96" target="_blank"
                >Contact info</a
              >
            </span>
          </p>
        </div>

        <div class="ml-auto text-center">
          <p class="school px-5">University of Uyo</p>
        </div>

      </div>
    </div>
  </div>
</template>

<style scoped>
.profile__card {
  border-radius: var(--corner-radius);
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
.connect {
  font-weight: 600;
}
.upload__div {
  background: white;
  border-radius: 50%;
  padding: 4px 8px;
}
.upload__svg {
  fill: #0a66c2;
}
.school {
  font-weight: 500;
}
.profile__img {
  border-radius: 50%;
  bottom: -6px;
  border: 4px solid white;
  background-color: white;
}
.more__btn {
  color: var(--black);
  font-size: 1rem;
  border: 1px solid var(--black);
  background: white;
}
.Add__btn {
  font-weight: 600;
  color: white;
  background: #0a66c2;
  border: none;
}
.Add__btn:hover {
  background: #004182;
}
.edit__btn {
  border: none;
  background: white;
}
svg.pencil {
  fill: var(--black);
}
.btn_ {
  text-align: center;
  vertical-align: middle;
  display: inline-flex;
  align-items: center;
}
.btn_:focus {
  outline: none;
}
.location {
  color: var(--black);
}
h4 {
  color: rgba(0, 0, 0, 0.9);
  font-size: 1.5rem;
  font-weight: normal;
}
h5 {
  color: rgba(0, 0, 0, 0.9);
  font-size: 1.125rem;
  font-weight: normal;
}
</style>