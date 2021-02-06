<template lang="pug">
  .container
    .home
      Logo
      h1.title auth-front
      .links
        a.button--green(href="https://nuxtjs.org/" target="_blank" rel="noopener noreferrer") Documentation
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component({
  name: 'HomePage',
})
export default class HomePage extends Vue {}
</script>

<style lang="scss">
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system,
      BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial,
      sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }
  .links {
    padding-top: 15px;
  }
}
</style>
