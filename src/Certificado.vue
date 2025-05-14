<script setup></script>

<template>
    <section class="formacao">
    <h2>🎓 Formação Acadêmica</h2>
    <div class="curso">
        <div class="curso-item">
            <i class="fas fa-graduation-cap"></i>
            <h3>Análise e Desenvolvimento de Sistemas</h3>
            <p>SENAI MÁRIO HENRIQUE SIMONSEN</p>
            <p class="data">2024 - 2025</p>
        </div>
    </div>
</section>
</template>

<style>
    
    .certificacoes {
        padding: 4rem 2rem;
        background: #fff;
    }

    .grid-certificados {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 2rem;
        max-width: 1200px;
        margin: 0 auto;
    }

    .certificado {
        text-align: center;
        padding: 2rem;
        border: 1px solid #eee;
        border-radius: 10px;
        transition: transform 0.3s;
    }

    .certificado:hover {
        transform: translateY(-5px);
    }

    .certificado i {
        font-size: 2.5rem;
        color: #2ecc71;
        margin-bottom: 1rem;
    }

    .tags {
        margin-top: 1rem;
    }

    .tags span {
        display: inline-block;
        background: #f0f0f0;
        padding: 0.3rem 0.8rem;
        border-radius: 20px;
        margin: 0.2rem;
        font-size: 0.9em;
    }
</style>