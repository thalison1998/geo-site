<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="css">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
  font-family: "Roboto", sans-serif;
  color: rgb(247, 244, 240);
}
#app {
  width: 100%;
  height: 100vh;
}
img {
  display: block;
  max-width: 100%;
}
html {
  font-size: 62.5%;
  scroll-behavior: smooth;
}
body {
  font-size: 1.4rem;
}
</style>
