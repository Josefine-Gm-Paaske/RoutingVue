<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/contact">Contact</router-link>
  </div>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #b19b73;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #b19b73;
}

#nav a.router-link-exact-active {
  color: #665d4c;
}
</style>
