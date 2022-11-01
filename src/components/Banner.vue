<template>
    <div id="main-banner">
        <h1>Você está com fome?</h1>
    </div>
</template>

<script>
export default {
    
    name: "Banner"
}
</script>

<style scoped>

    #main-banner {
        background-image: url('/Users/andreluis/Documents/Bleu/ProjetoVUE/projeto_vue_lanchonete/public/img/burger.jpeg');
        background-position: 0 0px;
        background-size: cover;
        height: 900px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #FFF;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }

</style>