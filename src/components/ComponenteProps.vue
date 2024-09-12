<script>
export default{
    props:{
        titulo: String,
        conteudo: String
    }
}

</script>


<template>
 <div>
    <h2>{{titulo}}</h2>
    <p>{{conteudo}}</p>
    <h2>{{autor}}</h2>

    </div>

</template>

<style>
P{
    color: green;
    width: 1000px;
}

h2{
    font-weight: bolder;
}

h1{
    font-size: 60px;
}