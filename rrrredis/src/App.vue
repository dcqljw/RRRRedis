<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style lang="stylus">
body
  background: var(--color-bg)
  color: var(--color-text)

#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color: var(--color-text)
  margin-top 60px
</style>
