<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <hr>
  <SimpleCounter/>
  <hr>

</template>

<script>
import SimpleCounter from './components/SimpleCounter.vue'
export default {
  name: 'App',
  components: {
    SimpleCounter,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

button {
  height: 30px;
  width: 70px;
  background-color: rgb(97, 182, 104);
  border: solid rgb(161, 219, 150);
  border-radius: 10px;
  margin: 20px;
  color: aliceblue;
  font-size: larger;
  font-weight: bold;
}

button:hover {
  background-color: rgb(50, 75, 87);
  border: solid rgb(93, 98, 114);
  color:rgb(161, 219, 150)
}
</style>
