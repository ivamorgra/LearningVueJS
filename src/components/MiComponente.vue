<template>
<div id="mi-componente">
    <h1> Este es MICOMPONENTE </h1>
    <h2> {{subtitulo}}</h2>
</div>
</template>

<script>

export default {
    name: 'MiCOmponente',
    data(){
        return{
            subtitulo: 'SOy un subtitulo'
        }
    }

}

</script>
