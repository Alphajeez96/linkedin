<template>
  <div>
    <div class="about__card">
      <div class="px-4 pt-4 pb-2">
        <h4>About</h4>

        <p class="pt-3">
          Frontend Developer keen on the pixel-perfect implementation of
          user-centric UI designs and writing unit tests to improve code
          predictability and documentation.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.about__card {
  border-radius: var(--corner-radius);
  border: 1px solid var(--border-color);
  background: white;
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
</style>