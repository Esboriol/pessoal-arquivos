<script setup>

</script>

<template>
    <section class="habilidades">
    <h2>🛠 Habilidades Técnicas</h2>
    <div class="grid-habilidades">
        <div class="skill">
            <i class="fab fa-html5"></i>
            <h3>HTML5</h3>
            <div class="barra">
                <div class="progresso html">90%</div>
            </div>
        </div>
        
        <div class="skill">
            <i class="fab fa-css3-alt"></i>
            <h3>CSS3</h3>
            <div class="barra">
                <div class="progresso css">85%</div>
            </div>
        </div>

        <div class="skill">
            <i class="fab fa-js"></i>
            <h3>JavaScript</h3>
            <div class="barra">
                <div class="progresso js">70%</div>
            </div>
        </div>
    </div>
</section>
</template>

<style scoped>
    .habilidades {
        padding: 4rem 2rem;
        background-color: white;
    }

    .grid-habilidades {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
        max-width: 1200px;
        margin: 0 auto;
    }

    .skill {
        text-align: center;
        padding: 1.5rem;
        background: #f8f9fa;
        border-radius: 10px;
    }

    .skill i {
        font-size: 3rem;
        margin-bottom: 1rem;
        color: #333;
    }

    .barra {
        background: #e9ecef;
        border-radius: 20px;
        height: 20px;
        margin: 1rem 0;
    }

    .progresso {
        height: 100%;
        border-radius: 20px;
        text-align: right;
        padding-right: 5px;
        color: white;
        font-size: 12px;
        line-height: 20px;
    }

    .html { width: 90%; background: #e34f26; }
    .css { width: 85%; background: #264de4; }
    .js { width: 70%; background: #f7df1e; color: #333; }
</style>