<template>
    <div id="skill-profile">
        <div id="todo-card">
            <div class="skills">
                  <h1>{{ skill }}</h1>
                  <p>{{ skill1 }}</p>
                  <p>{{ skill2 }}</p>
                  <p>{{ skill3 }}</p>
             </div>
        </div>
    </div>
    </template>
    
    <script>
    
    
    export default {
    name: 'skill-profile',
    data () {
    return {
        skill: 'Skills',
        skill1: 'Collaboration and Teamwork: Experience working in teams using Git, Scrum, or Agile methodologies.',
        skill2: 'Communication Skills: Ability to communicate complex technical details in a simplified manner',
        skill3: 'Adaptability: Learning new tools, frameworks, and techniques quickly.'
    }
    }
    }
    </script>
    
    <style>
    #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
    }
    
    #todo-card {
        margin-inline: auto;
        height:10%;
        border-bottom: 2px solid black;
        width: 80%;
    }
    .skills {
        margin: 3%;
        margin-left: 10%;
    }

    .skills h1 {
        text-align: left;
        
    }
    p {
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