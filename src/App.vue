<style>
.container {
  width: 800px;
  margin: auto;
  padding: 1rem;
}
.carousel {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-column-gap: 1rem;
}
.carousel > img {
  width: 100%;
}
</style>

<template>
<div class="container">
  <Header />
  <h1>Great Dogs Deserve Great Homes</h1>
  <p>We are an adoption agency committed to putting wonderful adoptable dogs
  into great permanent homes...</p>

  <h1>Adoptable Dogs</h1>
  <div class="carousel">
    <img src="https://placedog.net/500/280?id=5" alt="Dog 5">
    <img src="https://placedog.net/500/280?id=6" alt="Dog 6">
    <img src="https://placedog.net/500/280?id=7" alt="Dog 7">
  </div>
</div>
</template>

<script>
import Header from './Header.vue'

export default {
  components: {
    Header,
  }
}
</script>