<script setup>
import About from './components/About.vue';
import Contributing from './components/Contributing.vue';
import Projects from './components/Projects.vue';
import Home from './components/Home.vue';
import Timeline from './components/Timeline.vue';
import Bar from './components/Bar.vue';
</script>

<template>
  <header>
    <Bar />
  </header>
  <body>
    <div class="single-page">
      <Home />
      <About />
      <Contributing />
      <Projects />
      <Timeline />
    </div>
  </body>
</template>

<style>
header {
  position: fixed;
}

body {
  margin: 0;
}
</style>
