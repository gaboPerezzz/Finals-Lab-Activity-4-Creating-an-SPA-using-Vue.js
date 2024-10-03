<template>
  <div id="app">
    <div id="profile">
      <div id="profile-name">
          <h1>{{ msg }}</h1>
          <h4>{{ msg2 }}</h4>
          <h4>{{ msg3 }}</h4>
          <h4>{{ msg4 }}</h4>
      </div>
      <img src="./assets/logo.jpg">
    </div>
  <education></education>
  <Skill></Skill>
  </div>
  </template>
  
  <script>
  import education from './components/education'
  import Skill from './components/skills'
  export default {
  name: 'app',
  components: {
  education,
  Skill
  },
  data () {
  return {
  msg: 'Perez, John Gabriel T.',
  msg2: 'Web Developer',
  msg3: 'contact: 0934899739888',
  msg4: 'email: jangabperez@gmail.com',
  }
  }
  }
  </script>
  
  <style>
body {
    margin: 0;
    background-color: 	#E2DFD2;
  }
  #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  }

  #profile {
    margin-inline: auto;
    height: 10%;
    width: 80%;
    display: flex;
    justify-content: center;
    align-content: center;
    gap: 30%;
    padding: 5%;
    border-bottom: 2px solid black
  }

  #profile img {
    width: 350px;
  }
  
  #profile-name {
    margin-top: 3%;
  }

  #profile-name h4 {
    text-align: left;
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