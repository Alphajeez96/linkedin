<template>
  <div >
    <div class="tip__card p-3">
      <div class="d-flex">
        <div><h3>Edit public profile & URL</h3></div>

        <div class="ml-auto">
          <i
            v-b-tooltip.hover
            title="See and edit how you look to people who are not signed in, and find you through search engines (ex: Google, Bing)."
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
                d="M8 1a7 7 0 107 7 7 7 0 00-7-7zm0 11.25A1.25 1.25 0 119.25 11 1.25 1.25 0 018 12.25zM8.82 9H7v-.95l.93-.46C8.64 7.24 9 6.89 9 6.6S8.57 6 8 6a6.49 6.49 0 00-3 .91V4.84A6.35 6.35 0 018.1 4c2 0 2.9 1 2.9 2.4 0 .9-.5 1.83-2.18 2.6z"
              ></path></svg
          ></i>
        </div>
      </div>

        <div class="d-flex mt-3">
        <div><h3>Add profile in another language</h3></div>

        <div class="ml-auto">
          <i
            v-b-tooltip.hover
            title="Creating a profile in another language makes it easier for local business contacts and recruiters to find you on LinkedIn."
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
                d="M8 1a7 7 0 107 7 7 7 0 00-7-7zm0 11.25A1.25 1.25 0 119.25 11 1.25 1.25 0 018 12.25zM8.82 9H7v-.95l.93-.46C8.64 7.24 9 6.89 9 6.6S8.57 6 8 6a6.49 6.49 0 00-3 .91V4.84A6.35 6.35 0 018.1 4c2 0 2.9 1 2.9 2.4 0 .9-.5 1.83-2.18 2.6z"
              ></path></svg
          ></i>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.tip__card {
  border-radius: var(--corner-radius);
  border: 2px solid #f1f0ed;
  background: white;
}
h3 {
  color: var(--black);
  font-size: 1rem;
  font-weight: 500;
}
hr {
  border: 3px solid red;
}
</style>