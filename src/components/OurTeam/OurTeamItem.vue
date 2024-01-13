<template>
  <li class="our-team-item">
    <img alt="" :src="ourTeamItem.avatar" />
    <h3>{{ ourTeamItem.name }}</h3>
    <span>{{ ourTeamItem.position }}</span>
    <p>{{ ourTeamItem.description }}</p>
    <ul class="icon-list">
      <li>F</li>
      <li>F</li>
      <li>F</li>
      <li>F</li>
    </ul>
  </li>
</template>

<script>
export default {
  props: {
    ourTeamItem: {
      avatar: String, 
      name: String, 
      position: String, 
      description: String
    }
  },
}
</script>

<style scoped>
.our-team-item {
  background: #FFFFFF; 
  box-shadow: 0px 4px 30px rgba(10, 30, 35, 0.10); 
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  padding: 40px 30px;
  text-align: center;
}
.icon-list {
  display: flex;
  justify-content: center;
}
</style>
