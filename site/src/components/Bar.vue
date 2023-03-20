
<script>
import Contributing from './Contributing.vue';
import Home from './Home.vue';
import Projects from './Projects.vue';
import Timeline from './Timeline.vue';

export default {
    name: "App",
    components: {
        Contributing,
        Home,
        Projects,
        Timeline,
    },
}
</script>

<template>
    <div class="bar">
          <a v-bind:href="Home">home</a>
          <a v-bind:href="Contributing">contribuições</a>
          <a v-bind:href="Projects">projetos</a>
          <a v-bind:href="Timeline">linha do tempo</a>
      </div>
</template>

<style scoped>
.bar {
    display: flex;
    background-color: #D6B0D6;
    width: 100vw;
}

.bar a {
    color: #FAECBE;
    
    font-size: 1.15em;
    font-style: italic;
    text-decoration: none;
    
    padding: 1em;
}

.bar a:hover {
    text-decoration: underline;
}

</style>