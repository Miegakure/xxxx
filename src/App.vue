<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
body {
  transition-duration: .5s;
}
.link {
  font-family: "pixel";
}
@font-face {
  font-family: "space";
  src: url("../public/space.ttf"); 
}
@font-face {
  font-family: "tech";
  src: url("../public/tech.ttf"); 
}
@font-face {
  font-family: "pixel";
  src: url("../public/pixel.ttf"); 
}
@font-face {
  font-family: "vcc";
  src: url("../public/vcc.ttf");
}
#app {
  background: none;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  transition-duration: .5s;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
