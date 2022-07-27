<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <SchoolName></SchoolName>
    <StudentName></StudentName>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
  import SchoolName from './components/SchoolName.vue'
  import StudentName from './components/StudentName.vue'

export default {
  name: 'App',
  components: {
    SchoolName,
    StudentName 
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
</style>
