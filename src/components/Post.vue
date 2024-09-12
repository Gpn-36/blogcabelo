<script>
    export default {
        name: 'MeuComponente',
  props: {
    titulo: {
      type: String,
      required: true
    },
    descricao: {
      type: String,
      default: 'Esta é uma descrição padrão.'
    }
  }
    }
</script>

<template>
    <div id="cabecalho">
        <div class="cabecalho-col1">
            <h1>Etec</h1>
        </div>
        <div>
            <a href="">Login</a>
            <span>{{ nome }}</span>
        </div>
    </div>
<style>
    h1 {
  color: blue;
}

p {
  font-size: 14px;
}
</style>

</template>