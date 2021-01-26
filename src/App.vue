<template>
  <div>
    <tag-Header></tag-Header>
    <p></p>
    <tag-HelloWorld></tag-HelloWorld>
    <p></p>
    <tag-Footer></tag-Footer>
  </div>
</template>

<script>
import tagHeader from './components/Header.vue'
import tagHelloWorld from './components/HelloWorld.vue'
import tagFooter from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    'tag-Header' : tagHeader,
    'tag-HelloWorld' : tagHelloWorld,
    'tag-Footer' : tagFooter

  }
}
</script>

<style>

</style>
