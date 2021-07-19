<template>
  <div class="home" id="app">
    <main>
      
      <h2>The Weather App</h2>
       <router-link to="/" tag="button">Search</router-link>
    </main>
  </div>
</template>

<style>

router-link {
  display: inline-block;
  text-align: center;
  font-size: 60px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

h2{
  font-family: Georgia, 'Times New Roman', Times, serif;
  color:blanchedalmond;
  font-style: bold;
  font-size: 70px;
  text-align: center;
  display: block;
  margin-bottom: 20px;
}

body {
  font-family: 'Cambria, serif';
  height: 100%;
  width: 100%;
}

#app {
  background-image: url('../assets/4seasons.jpg');
  background-size: cover;
  background-position: center;
  transition: 0.4s;
  background-repeat: no-repeat;
  height: 100%;
  width: 100%;
}
main {
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75));
}
</style>
