<template>
  <main class="container">
    <h1>Hi from home Page</h1>
    <AppHeader />
    <AppRestaurantInfo />
  </main>
</template>

<script>
import AppHeader from "@/components/AppHeader";
import AppRestaurantInfo from "@/components/AppRestaurantInfo";

export default {
  components: {
    AppHeader,
    AppRestaurantInfo
}
};
</script>

<style scoped>

</style>
