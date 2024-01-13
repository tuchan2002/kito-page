<template>
  <li class="proud-of-item">
    <span>{{ proudOfItem.statistics }}</span>
    <h3>{{ proudOfItem.title }}</h3>
    <p>{{ proudOfItem.description }}</p>
  </li>
</template>

<script>
export default {
  props: {
    proudOfItem: {
      statistics: String,
      title: String,
      description: String
    }
  },
}
</script>

<style scoped>
.proud-of-item {
  background: #FFFFFF; 
  box-shadow: 0px 4px 30px rgba(10, 30, 35, 0.10); 
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  padding: 40px 30px;
  text-align: center;
}
</style>
