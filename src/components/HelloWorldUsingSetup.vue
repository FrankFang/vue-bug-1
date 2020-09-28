<template>
  <h1>{{ msg }}</h1>
</template>

<script setup>
export default {
  name: 'HelloWorldUsingSetup',
  props: {
    msg: String
  },
}
export const msg = 'Message from HelloWorld.vue'
</script>
