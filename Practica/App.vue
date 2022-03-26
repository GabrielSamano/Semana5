<template>
  <div id="app">
    <div class="navbar-container a">
      <div class="navbar-container a">
       
      </div>

    </div>
   
    <router-view/>
  </div>
  
</template>


<style>
.navbar-container{
  width: 90%;
  position: fixed;
  bottom: 0;
  padding: 20px;
  display: flex;
  justify-content: space-between;

}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: justify;
  color: #2c3e50;

}
*{
  margin: 0px;
  padding: 0px;
  background-size: cover;
  background-position: center;
  background-blend-mode: darken;
  
}

</style>
