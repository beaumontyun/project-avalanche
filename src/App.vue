<template>
  <img alt="Vue logo" src="./assets/ProjectAvalanche.a5f522e2.svg">
  <HelloWorld msg="Welcome to Project Avalanche"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
img {
  width: 25%;
}
@media screen and (max-width: 1064px) {
	img {
		width: 35%;
	}
}
@media screen and (max-width: 768px) {
	img {
		width: 70%;
	}
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
