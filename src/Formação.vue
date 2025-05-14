<script setup>

</script>

<template>
    <section class="certificacoes">
    <h2>📜 Certificações Relevantes</h2>
    <div class="grid-certificados">
        <div class="certificado">
            <i class="fas fa-award"></i>
            <h3>Programação backend</h3>
            <p class="emissor">SENAI - 2024</p>
            <div class="tags">
                <span>JavaScript</span>
                <span>Node.js</span>
            </div>
        </div>

        <div class="certificado">
            <i class="fas fa-certificate"></i>
            <h3>Arduino</h3>
            <p class="emissor">SENAI - 2024</p>
            <div class="tags">
                <span>C++</span>
            </div>
        </div>
    </div>
</section>
</template>

<style scoped>
        /* Formação Acadêmica */
    .formacao {
        padding: 4rem 2rem;
    }

    .curso {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2rem;
        max-width: 1200px;
        margin: 0 auto;
    }

    .curso-item {
        text-align: center;
        padding: 2rem;
        background: white;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .curso-item i {
        font-size: 2.5rem;
        color: #333;
        margin-bottom: 1rem;
    }
</style>