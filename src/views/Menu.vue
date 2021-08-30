<template>
  <div>
    <home-plans></home-plans>
    <meal-recipes></meal-recipes>
  </div>
</template>

<script>
import HomePlans from '../components/HomePlans.vue';
import MealRecipes from '../components/MealRecipes.vue';

export default {
  name: 'Menu',
  components: {
    HomePlans,
    MealRecipes,
  },
};
</script>
