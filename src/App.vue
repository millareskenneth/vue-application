<template>
  <h1 v-text="greeting"></h1>
  <h2>{{ name }}</h2>
  <h3 v-html="text"></h3>
  <h4 v-bind:id="id">Header</h4>
</template>

<script>
  export default {
    data(){
      return{
        greeting : 'Hello World',
        name : 'Kenneth',
        text : '<i>Italic</i>',
        id : 'header'
      }
    }
  }
</script>