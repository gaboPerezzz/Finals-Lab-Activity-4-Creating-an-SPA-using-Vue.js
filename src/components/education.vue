<template>
    <div id="educations">
        <div id="todo-card">
            <div class="education">
                  <h1>{{ educ }}</h1>
                  <p>{{ educ1 }}</p>
                  <p>{{ educ2 }}</p>
                  <p>{{ educ3 }}</p>
             </div>
        </div>
    </div>
    </template>
    
    <script>
    
    
    export default {
    name: 'educations',
    
    data () {
    return {
    educ: 'Education',
    educ1: 'Elementary: Achievers Special Education Center',
    educ2: 'High School: Claro M. Recto Information Technology High School',
    educ3: 'College: Holy Angel University'
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
    .education {
        margin: 3%;
        margin-left: 10%;
    }

    .education h1 {
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