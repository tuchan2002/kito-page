<template>
  <section class="about-section">
    <div class="about-item">
      <img alt="" src="../assets/about-image-1.png"/>
    </div>
    <div class="about-item">
      <img alt="" src="../assets/about-image-2.png" />
    </div>
    <div class="about-item">
      <h3>Big love for our lovely kids.</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Ut enim ad minim veniam, quis nostrud exercitation.</p>
      <button>About Us</button>
    </div>
  </section>
</template>

<script>

export default {
}
</script>

<style scoped>
.about-section {
  display: grid;
  grid-template-columns: repeat(3, 1fr); 
  gap: 30px;
  align-items: center;

}
.about-item > img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
