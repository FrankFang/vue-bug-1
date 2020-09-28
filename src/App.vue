<template>
  <HelloWorld msg="Message from App.vue" />
  <HelloWorldUsingSetup msg="Message from App.vue" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorldUsingSetup from './components/HelloWorldUsingSetup.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, HelloWorldUsingSetup
  }
}
</script>
