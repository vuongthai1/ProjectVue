<template>
  <span>
    <home-hero></home-hero>
    <home-details></home-details>
    <home-plans></home-plans>
    <meal-recipes></meal-recipes>
  </span>
</template>

<script>
import HomeHero from '../components/HomeHero.vue';
import HomeDetails from '../components/HomeDetails.vue';
import HomePlans from '../components/HomePlans.vue';

export default {
  name: 'home',
  components: {
    HomeHero,
    HomeDetails,
    HomePlans,
  },
};
</script>
