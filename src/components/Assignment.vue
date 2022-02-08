<template>
  <div class="assignment">
    <h1 class="welcome-innings-app">{{ msg }}</h1>
    <div class="document__container">
      <h4>Identity Card:</h4>
      <b-input class="input" v-model="identityCard" type="number"></b-input>
      <h1>{{ identityCard }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Assignment",
  props: {
    msg: String,
  },
  data() {
    return {
      identityCard: ""
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.assignment {
  display: flex;
  align-items: center;
  flex-direction: column;
  width: 80%;
  height: 32rem;
  background-color: rgb(230, 230, 230);
  border-radius: 0.4rem;
  box-shadow: 6px 6px 7px 0px rgb(0 0 0 / 20%);
}
.welcome-innings-app {
  font-weight: bold;
  margin: 5rem 0rem;
}
::v-deep.input {
  border: none;
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
