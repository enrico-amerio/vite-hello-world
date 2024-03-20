<script>
export default {
  data(){
    return{
      title: 'Onion Rings',
      paragraph: 'One ring to rule them all, one ring to find them, One ring to bring them all and in the darkness bind them.',
    }
  }
}
</script>
<template>
  <div>
    <img src="./assets/food-onion-rings.svg" alt="onion" class="onion">
    <h1>{{ title }}</h1>
    <p>{{ paragraph }}</p>
  </div>
</template>

<style scoped>
  .onion{
    width:350px;
  }
</style>