<script setup>
import Projeto from './Projeto.vue';
</script>

<template>
    <section class="projetos">
        <h2>Meus Projetos</h2>
        <div class="grid-projetos">
           <Projeto />
        </div>
    </section>
</template>

<style scoped>
    .projetos {
        padding: 4rem 2rem;
    }

    .grid-projetos {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2rem;
        max-width: 1200px;
        margin: 0 auto;
    }
</style>