<template>
  <div class="wrapper">
    <HeaderComponent />
    <PageTitle />
    <CTAComponent />
    <ProudOf />
    <AboutComponent />
    <OurTeam />
    <BenefitComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/Header/HeaderComponent.vue'
import PageTitle from './components/PageTitle.vue'
import CTAComponent from './components/CTAComponent.vue'
import ProudOf from './components/ProudOf/ProudOf.vue'
import AboutComponent from './components/AboutComponent.vue'
import OurTeam from './components/OurTeam/OurTeam.vue'
import BenefitComponent from './components/BenefitComponent/BenefitComponent.vue'
import FooterComponent from './components/Footer/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    PageTitle,
    CTAComponent,
    ProudOf,
    AboutComponent,
    OurTeam,
    BenefitComponent,
    FooterComponent
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');

html {
  box-sizing: border-box;
}
* {
  margin: 0;
  padding: 0;
  font-family: 'Open Sans', sans-serif;
  font-size: 15px;
  line-height: 26px;
}
*,
*:before,
*:after {
  box-sizing: border-box;
}
input,
textarea,
select,
button {
  outline: none;
}
input {
  line-height: normal;
}
label,
button {
  cursor: pointer;
}
a {
  text-decoration: none;
}
ul {
  list-style: none;
}
img {
  display: block;
  max-width: 100%;
}
.wrapper {
  max-width: 1410px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 100px;
  padding-bottom: 27px;
}
</style>
