<template>
  <div>
    <div class="about__card">
      <div class="px-4 pt-4 pb-3">
        <h4>Featured</h4>

        <div class="mt-3 p-3 featured__div" @click="redirect">
          <div class="d-flex">
            <div>
              <img
                src="~/assets/img/article.png"
                class="article__img"
                alt="article"
              />
            </div>

            <div class="mx-3">
              <p>
                Something I wrote from a while ago on Reverse geocoding in
                NuxtJs. Building a Reverse Geocoding app in Nuxtjs.
              </p>

              <p class="pt-1 article__text">
                Building a Reverse Geocoding app in Nuxtjs using Mapbox
                <span class="link">codesource.io • 10 min read </span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      location:
        "https://codesource.io/reverse-geocoding-in-nuxtjs-using-mapbox/",
    };
  },
  methods: {
    redirect() {
        window.open(this.location, '_blank')
    },
  },
};
</script>

<style scoped>
.about__card {
  border-radius: var(--corner-radius);
  border: 1px solid var(--border-color);
  background: white;
  cursor: pointer;
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
.link {
  font-size: 0.75rem;
  color: var(--black);
}
.article__img {
  height: 40vh;
  border-radius: 1rem;
}
.article__text {
  font-weight: 500;
}
.featured__div {
  border: 1px solid var(--border-color);
  border-radius: var(--corner-radius);
}
</style>