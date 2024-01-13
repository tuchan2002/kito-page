<template>
  <section class="container">
    <div class="left">
      <label>ABOUT US</label>
      <p>bring exciting moments of fun while playing & learning for children.</p>
      <button>CONTACT US</button>
    </div>
    <div class="right">
      <img alt="" src="../assets/bird-background.png" class="right-image"/>
      <div class="right-icon">
        <span></span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
}
.left {
  width: 50%;
  background-color: #E5F8FD;
}
.right {
  width: 50%;
  position: relative;
}
.right-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.right-icon {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 90px;
  height: 90px;
  transform: translate(-50%, -50%);
  background-color: #FFFFFF;
  border-radius: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.right-icon > span {
  font-size: 42px;
  color: #EC80A0;
}
</style>
