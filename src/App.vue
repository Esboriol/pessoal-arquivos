<script setup>

import Header from './Header.vue';
import Redes from './Redes.vue';
import Projetos from './Projetos.vue';
import Footer from './Footer.vue';
import Habilidades from './Habilidades.vue';
import Certificados from './Formação.vue';
import Formação from './Certificado.vue';

</script>

<template>
    <!-- Cabeçalho -->
     <Header />

    <!-- Seção de Redes Sociais -->
     <Redes />

    <!-- Seção de Projetos -->
    <Projetos />

    <!-- Seção Habilidades -->
    <Habilidades />

    <!-- Seção Certificados -->
    <Certificados />

    <!-- Seção Formação -->
    <Formação />

    <!-- Rodapé -->
    <Footer />

</template>

<style scoped>

/* Responsividade */
@media (max-width: 768px) {
    .grid-projetos {
        grid-template-columns: 1fr;
    }
}

@media screen and (max-width: 768px) {
    .timeline::after {
        left: 31px;
    }
    
    .container {
        width: 100%;
        padding-left: 70px;
        padding-right: 25px;
    }
    
    .right {
        left: 0%;
    }
}

</style>
