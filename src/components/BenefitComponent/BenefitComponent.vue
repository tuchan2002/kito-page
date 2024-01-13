<template>
  <section class="container">
    <ul class="benefit-list">
      <BenefitItem v-for="benefitItem in benefitItems" :key="benefitItem.id" :benefitItem="benefitItem" />
    </ul>
  </section>
</template>

<script>
import BenefitItem from './BenefitItem.vue';

export default {
  components: {
    BenefitItem
  },
  data() {
    return {
      benefitItems: [
        { id: 1, title: 'Free shipping', description: 'Free  shipping orders  from $150' },
        { id: 2, title: 'Gift/Discount codes', description: 'Many discount codes every day' },
        { id: 3, title: 'Money return', description: 'Return it  within  30 days' },
      ],
    }
  },
}
</script>

<style scoped>
.benefit-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-column-gap: 30px;
  border: 1px #1A1114 solid;
  border-radius: 10px;
}

</style>
