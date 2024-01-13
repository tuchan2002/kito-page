<template>
  <footer>
    <div class="footer-top">
      <h2>kito</h2>
      <div class="subscribe">
        <p>Join our list and get 20% off your first purchase!</p>
        <div>
          <input placeholder="Enter your email"/>
          <button>SUBSCRIBE</button>
        </div>
      </div>
    </div>
    <div class="footer-middle">
      <div>
        <h3>Contact info</h3>
        <ul>
          <li>
            <span>F</span>
            <span>560 King St W, Kingston, ON K7L 4V7, Canada</span>
          </li>
          <li>
            <span>F</span>
            <span>contactinfo@gmail.com</span>
          </li>
          <li>
            <span>F</span>
            <span>+1 212 736 3100</span>
          </li>
        </ul>
      </div>
      <div>
        <h3>Quick links</h3>
        <ul>
          <li>My account</li>
          <li>Cart</li>
          <li>Wishlist</li>
          <li>Product Compare</li>
        </ul>
      </div>
      <div>
        <h3>Information</h3>
        <ul>
          <li>Privacy policy</li>
          <li>Refund policy</li>
          <li>Shipping & Return</li>
          <li>Term & conditions</li>
        </ul>
      </div>
      <div>
        <h3>Follow us</h3>
        <ul>
          <li>
            <span>F</span>
            <span>Facebook</span>
          </li>
          <li>
            <span>F</span>
            <span>Tweeter</span>
          </li>
          <li>
            <span>F</span>
            <span>Instagram</span>
          </li>
          <li>
            <span>F</span>
            <span>Youtube</span>
          </li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      Beae’stemplate © 2022. All Rights Reserved.
    </div>
  </footer>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style scoped>
.footer-top {
  display: flex;
  justify-content: space-between;
  padding-bottom: 70px;
  margin-bottom: 70px;
  border-bottom: 1px solid #1A1114;
}
.subscribe {
  display: flex;
  gap: 31px;
}
.footer-middle {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  padding-bottom: 70px;
  border-bottom: 1px solid #1A1114;
  margin-bottom: 27px;
}
.footer-bottom {
  text-align: center;
}
</style>
