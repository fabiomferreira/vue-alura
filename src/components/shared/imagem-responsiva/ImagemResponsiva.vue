<template>
    <img class="imagem-responsiva" :alt="titulo" :src="url">    
</template>

<script>
export default {
    props: ['url', 'titulo']
};
</script>

<style scoped>
.imagem-responsiva {
  width: 100%;
}
</style>
