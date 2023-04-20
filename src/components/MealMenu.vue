<template>
  <div class="container mb-5">
    <h4 class="my-4 fw-600 d-blue">Our top Food options</h4>
      <div class="row">
        <FoodItem v-for="meal in Meals" :key="meal.Item_id" :item="meal" v-on:click="foodDetails(items)" class="col-md-4 pointer"/>
      </div>
   

  </div>
</template>

<script>
import FoodItem from "./FoodItem.vue"
import Meals from "../../public/data/data"
export default {
  data () {
    return {
        Meals: Meals
    }
  },
 
    name: 'MealMenu',

   components : {
    FoodItem
   }
};
</script>

<style scoped>

</style>