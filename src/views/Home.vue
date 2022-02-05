<template>
  <div class="home">
    <Assignment msg="Welcome to Your Innings App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Assignment from '@/components/Assignment.vue'

export default {
  name: 'Home',
  components: {
    Assignment
  }
}
</script>

<style scoped>
.home {
  width: 100%;
  height: 100vh;
}
</style>
