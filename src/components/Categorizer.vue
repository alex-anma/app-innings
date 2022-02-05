<template>
  <div class="assignment">
    <div class="input">
      <div class="input__container">
        <h1>{{ msg }}</h1>
        <input type="text" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Assignment",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
