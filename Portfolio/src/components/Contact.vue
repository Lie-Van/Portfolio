<template>
    <header class="header">
      <div class="container">
        <h1 class="logo">{{ title }}</h1>
        <nav class="nav">
          <ul>
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/about">About</router-link></li>
            <li><router-link to="/projects">Projects</router-link></li>
            <li><router-link to="/contact">Contact</router-link></li>
          </ul>
        </nav>
      </div>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header',
    data() {
      return {
        title: 'Your Portfolio'
      };
    }
  };
  </script>
  
  <style scoped>
  .header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
  }
  
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .logo {
    margin: 0;
  }
  
  .nav ul {
    list-style-type: none;
    padding: 0;
  }
  
  .nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  .nav ul li:last-child {
    margin-right: 0;
  }
  
  .nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  .nav ul li a:hover {
    text-decoration: underline;
  }
  </style>
  