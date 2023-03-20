<script>
import About from './About.vue';

export default {
    name: "Home",
    components: {
        About,
    },
}
</script>

<template>
    <div class="wrapper">
        <div class="text">
            <div class="infos">
                <h2>Emilly</h2>
                <h2>Albuquerque</h2>
            </div>
            <div class="contact">
                <a v-bind:href="About" class="button">
                    conheça me
                </a>
                <div class="icons">
                    <a target="_blank" href="https://github.com/emys-alb">
                        <i class="fa fa-github"></i>
                    </a>
                    <a target="_blank" href="mailto:emilly.oliveira@ccc.ufcg.edu.br">
                        <i class="fa fa-envelope"></i>
                    </a>
                    <a target="_blank" href="https://www.linkedin.com/in/emilly-alb/">
                        <i class="fa fa-linkedin"></i>
                    </a>
                </div>
            </div>
        </div>
        <div>
            <img src="https://avatars2.githubusercontent.com/u/47047853?s=400&u=1103402da437d2da352ffa8251383de64fed6fec&v=4" alt="Emilly de Albuquerque">
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital@0;1&display=swap');
.wrapper {
    width: 100vw;
    height: 100vh;
    background-color: #D6B0D6;
    
    padding: 5em 2em;
    display: flex;
}

img {
    border: 3px solid #FAECBE;
    border-radius: 65%;

    width: 70%;
}


.text {
    width: 50%;
    padding: 3em 4em 0 0;
}

.infos,
.contact {
    color: #FAECBE;
    justify-content: space-around;
}

.infos {
    font-family: 'Libre Baskerville', serif;
    font-style: italic ;
    font-size: 200%;
    
    padding-bottom: 1em;
    line-height: 1em;
}
.contact {
    display: inline;
    
    font-size: 120%;
    line-height: 2rem;
}

.contact .button {
    border: 2px solid #FAECBE;
    border-radius: 69px;
    
    padding: 0.8em 2.5em;

    justify-content: center;
    font-style: italic;
}

.icons {
    display: flex;
}

.icons a {
    color: #FAECBE;
    padding: 1em 1em 0 0.2em;
    
    text-decoration: none;
    font-size: 1.5em;
}


@media (min-width: 1024px) {
}
</style>
