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
.assignment {
  width: 100%;
  height: 100%;
  background-color: #000;
  border-radius: 50px;
}
.input {
  width: 100%;
  height: 100%;
}
.input__container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
