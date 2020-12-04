<template>
  <div>
    <b-navbar class="nav_bar" toggleable="lg" variant="info">
      <div class="contain">
        <div class="d-flex align-items-center">

          <!-- Logo here -->
          <div class="">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="34"
              height="34"
              viewBox="0 0 34 34"
              class="global-nav__logo"
            >
              <title>LinkedIn</title>
              <g>
                <path
                  d="M34,2.5v29A2.5,2.5,0,0,1,31.5,34H2.5A2.5,2.5,0,0,1,0,31.5V2.5A2.5,2.5,0,0,1,2.5,0h29A2.5,2.5,0,0,1,34,2.5ZM10,13H5V29h5Zm.45-5.5A2.88,2.88,0,0,0,7.59,4.6H7.5a2.9,2.9,0,0,0,0,5.8h0a2.88,2.88,0,0,0,2.95-2.81ZM29,19.28c0-4.81-3.06-6.68-6.1-6.68a5.7,5.7,0,0,0-5.06,2.58H17.7V13H13V29h5V20.49a3.32,3.32,0,0,1,3-3.58h.19c1.59,0,2.77,1,2.77,3.52V29h5Z"
                ></path>
              </g>
            </svg>
          </div>

          <!-- Search bar here -->
          <div class="mx-2 mt-3">
            <form action="" method="POST">
              <div class="form-group position-relative">
                <input
                  type="search"
                  class="search__input"
                  placeholder="Search"
                />
                <!-- Search Icon here -->
                <div class="position-absolute search__icon">
                  <i
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
                      <path
                        d="M14.56 12.44L11.3 9.18a5.51 5.51 0 10-2.12 2.12l3.26 3.26a1.5 1.5 0 102.12-2.12zM3 6.5A3.5 3.5 0 116.5 10 3.5 3.5 0 013 6.5z"
                      ></path></svg
                  ></i>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto contain">
        <div class="d-flex flex-column">        
       <i></i>
          <p >Home</p>
        </div>

        <div class="mx-4">
          <nuxt-link to="/sign-in"><span class="reg">Login</span></nuxt-link>
        </div>

          <div>
          <nuxt-link to v-b-modal.my-modal
            ><span class="reg">Register</span></nuxt-link
          >
        </div>

        <div class="mx-4">
          <nuxt-link to="/sign-in"><span class="reg">Login</span></nuxt-link>
        </div>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>
<script>
export default {};
</script>
<style  scoped>
.contain{
    padding-left: 7rem;
    padding-right: 7rem;
}
.global-nav__logo {
  fill: #0a66c2;
}
.search__input {
  display: block;
  width: 280px;
  height: 35px;
  padding: 0 .5rem 0 2.5rem;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: rgba(0, 0, 0, 0.6);
  background-color: #eef3f8;
  background-clip: padding-box;
  border: none;
  border-radius: 0.25rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
  outline: 0;
}
.search__icon {
  left: 16px;
  top: 4px;
}
::placeholder {
  color: rgba(0, 0, 0, 0.6);
}
.top_logo {
  height: 4vh;
}

.spiral_line {
  height: 150px;
}
.nav_bar {
  background-color: #fff !important;
  height: 54px;
  border-bottom: 1px solid rgba(0, 0, 0, 0.08);
}
.navbar-expand-lg .navbar-nav {
  display: -webkit-inline-box;
}
.navbar {
  padding: 0;
}
.reg {
  color: #070707;
  font-family: "Neue Helvetica";
  font-weight: 400;
}
a {
  text-decoration: none;
}

.bg-info {
  letter-spacing: 0px;
}
.navbar-light .navbar-nav .nav-link {
  color: red !important;
}
</style>