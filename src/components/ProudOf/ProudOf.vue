<template>
  <section class="container">
    <h2 class="proud-of-title">What we are proud of.</h2>
    <ul class="proud-of-list">
      <ProudOfItem v-for="proudOfItem in proudOfItems" :key="proudOfItem.id" :proudOfItem="proudOfItem" />
    </ul>
  </section>
</template>

<script>
import ProudOfItem from './ProudOfItem.vue';

export default {
  components: {
    ProudOfItem
  },
  data() {
    return {
      proudOfItems: [
        { id: 1, statistics: '20+', title: 'Total top services', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' },
        { id: 2, statistics: '15+', title: 'Countries', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' },
        { id: 3, statistics: '98%', title: 'Positive Feedback', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' },
        { id: 4, statistics: '2,558', title: 'Usual users', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' }
      ],
    }
  },
}
</script>

<style scoped>
.proud-of-title {
  text-align: center;
  margin-bottom: 50px;
}
.proud-of-list {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-column-gap: 30px;
}
</style>
