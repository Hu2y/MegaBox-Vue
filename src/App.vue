<template>
  <body id="app">
    <web-header></web-header>
    <web-content></web-content>
    <web-footer></web-footer>
  </body>
</template>

<script>
import WebHeader from './components/WebHeader'
import WebContent from './components/WebContent'
import WebFooter from './components/WebFooter'

export default {
  components: {
    WebHeader,
    WebContent,
    WebFooter
  }
}
</script>

<style>
  @import 'assets/css/main.css';
  @import 'assets/css/reset.css';
</style>