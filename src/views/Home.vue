<template>
  <div class="wrapper">
    <Songs />
    <Navigation style="background-color: transparent;"/>
  </div>
</template>

<script>
import Songs from '@/components/Songs.vue'
import Navigation from '@/components/Navigation.vue'


  export default {
    components: {
      Songs,
      Navigation,
    }
  }
</script>

<style scoped>
.wrapper{
  height: 100%
}
</style>
