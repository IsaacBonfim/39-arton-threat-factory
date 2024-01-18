<template>
  <div class="home">
    <HomeMessage/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeMessage from '@/components/HomeMessage.vue'

export default {
  name: 'HomeView',
  components: {
    HomeMessage
  }
}
</script>

<style>

.home {
  align-items: center;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  height: 86vh;
  justify-content: flex-start;
}

</style>
