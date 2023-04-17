<template>
    <div class="card-container">
      <div class="row">
        <cardComponent v-for="card in comics" :key="card.series" 
        class="col-12 col-md-6 col-lg-2 mb-4"
         :thumb="card.thumb" :price="card.price" :series="card.series" :type="card.type">
        </cardComponent>
      </div>
    </div>
  </template>

<script>
import dcComics from './dcComics.json'
import cardComponent from './cardComponent.vue';

export default {
  name: 'App',
  components: {
    cardComponent,
  },
  data() {
    return {
        comics: dcComics,
    };
  },
 
};
</script>

<style lang="scss">
  .card-container {
  display: flex;
  justify-content: center;
  
}
</style>