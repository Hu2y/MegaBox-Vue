<template>
  <body id="app">
    <web-header></web-header>
    <web-nav></web-nav>
    <web-content></web-content>
    <web-footer></web-footer>
  </body>
</template>

<script>
import WebHeader from './components/WebHeader'
import WebNav from './components/WebNav'
import WebContent from './components/WebContent'
import WebFooter from './components/WebFooter'

export default {
  components: {
    WebHeader,
    WebNav,
    WebContent,
    WebFooter
  }
}
</script>

<style>

</style>