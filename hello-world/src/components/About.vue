<template>
  <div class="textDiv1">
    Esto es un texo de prueba que aparece procedente del componente de <strong>Vue.js</strong>: About.vue.
  </div>
  <br>
  <span>Message: {{ aboutMe }}</span>
</template>

<script>
  export default {

  data() {
    return {
      aboutMe: "Mollit nostrud tempor laboris qui proident esse cillum."
    }
  },
  }
</script>

<style scoped>
  .textDiv1 {
    background-color: #34495E;
    color: #ffffff;
    text-align: center;
    padding: 2%;
    font-size: 1.3em;
  }
  strong {
    color: #41B883
  }
  span {
    font-size: 30px;
  }
</style>