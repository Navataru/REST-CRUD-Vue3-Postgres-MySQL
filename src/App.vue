<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/v">Vladilen</router-link>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #FFFFFF;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
