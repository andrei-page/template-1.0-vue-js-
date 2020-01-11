<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="sass" >

@import "./src/assets/mixins/fonts.sass"
@import "./src/assets/mixins/media.sass"
@import "./src/assets/mixins/variables.sass"
@import "./src/assets/mixins/reset.sass"

#app
  text-align: center
  color: #2c3e50
  font-family: $regular
#nav
  padding: 50px 0 20px 0
  a
    text-decoration: none
  .router-link-exact-active
    color: blue
</style>
