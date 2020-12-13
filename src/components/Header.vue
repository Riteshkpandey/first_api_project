<template>
<nav id="nav" class="navbar navbar-expand-lg navbar-light bg-light ">
  
    
    
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <router-link to="/">Home</router-link> 
        </li>
        <li class="nav-item">
         <router-link to="/about">About</router-link>
        </li>
        
        
      </ul>
    </div>
  
</nav>
  
</template>

<script>
export default {
  name: "Header"
  
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
