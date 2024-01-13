<template>
  <section class="container">
    <h2 class="our-team-title">Our team</h2>
    <ul class="our-team-list">
      <OurTeamItem v-for="ourTeamItem in ourTeamItems" :key="ourTeamItem.id" :ourTeamItem="ourTeamItem" />
    </ul>
  </section>
</template>

<script>
import OurTeamItem from './OurTeamItem.vue';

export default {
  components: {
    OurTeamItem
  },
  data() {
    return {
      ourTeamItems: [
        { id: 1, avatar: '../../assets/person-1.png', name: 'Name 01', position: 'CEO & Founder', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' },
        { id: 2, avatar: '', name: 'Name 01', position: 'Personnel', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' },
        { id: 3, avatar: '', name: 'Name 01', position: 'Personnel', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' },
        { id: 4, avatar: '', name: 'Name 01', position: 'Personnel', description: 'Lorem ipsum dolor sit amet, sed do consectetur adipiscing elit.' }
      ],
    }
  },
}
</script>

<style scoped>
.our-team-title {
  text-align: center;
  margin-bottom: 50px;
}
.our-team-list {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-column-gap: 30px;
}

</style>
