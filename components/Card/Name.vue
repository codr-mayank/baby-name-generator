<script setup lang="ts">
  interface NameProps {
    name: string
  }

  const props = defineProps <NameProps> ();
</script>

<template>
  <div class="card">
    <h4>
      {{ name }}
    </h4>
    <p>x</p>
  </div>
</template>

<style scoped>
  .card {
    background-color: rgb(27, 60, 138);
    width: 28%;
    color: #fff;
    border-radius: 1rem;
    padding: 0.1rem;
    margin-right: 0.5rem;
    margin-bottom: 1rem;
    position: relative;
  }
  
  .card p {
    position: absolute;
    top: -20%;
    left: 92.5%;
    color: rgba(255, 255, 255, 0.388);
    cursor: pointer;
  }
</style>