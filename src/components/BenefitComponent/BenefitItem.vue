<template>
  <li class="benefit-item">
    <div>ICON</div>
    <div class="benefit-content">
      <h3>{{ benefitItem.title }}</h3>
      <p>{{ benefitItem.description }}</p>
    </div>
  </li>
</template>

<script>
export default {
  props: {
    benefitItem: {
      title: String, 
      description: String
    }
  },
}
</script>

<style scoped>
.benefit-item {
  display: flex;
  gap: 20px;
}
</style>
