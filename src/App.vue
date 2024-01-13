<template>
  <div class="wrapper">
    <div>
      <TopHeader />
      <NavbarMenu />
    </div>
    <PageTitle />
    <CTAComponent />
    <ProudOf />
    <AboutComponent />
    <OurTeam />
    <BenefitComponent />
  </div>
</template>

<script>
import TopHeader from './components/Header/TopHeader.vue'
import NavbarMenu from './components/Header/NavbarMenu.vue'
import PageTitle from './components/PageTitle.vue'
import CTAComponent from './components/CTAComponent.vue'
import ProudOf from './components/ProudOf/ProudOf.vue'
import AboutComponent from './components/AboutComponent.vue'
import OurTeam from './components/OurTeam/OurTeam.vue'
import BenefitComponent from './components/BenefitComponent/BenefitComponent.vue'

export default {
  name: 'App',
  components: {
    TopHeader,
    NavbarMenu,
    PageTitle,
    CTAComponent,
    ProudOf,
    AboutComponent,
    OurTeam,
    BenefitComponent
  }
}
</script>

<style>
html {
  box-sizing: border-box;
}
* {
  margin: 0;
  padding: 0;
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
}
</style>
