
<script setup>
  import Componete from './components/ComponeteBlog.vue';
import AreaPostagem from './components/AreaPostagem.vue';
</script>
<template>
  <div id="cabecalho">
    <div class="cabecalho-col1">
      <h1>Etec</h1>
    </div>

    <div class="sla">
      <div class="cabecalho-col1" id="cabecalho-login">
        <a class="login" href="">Login - {{ nome }}</a>

      </div>
    </div>
  </div>
    <AreaPostagem></AreaPostagem>
</template>

<style scoped>


  body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #dfad06;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

</style>
