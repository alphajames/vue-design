<template>
<Navbar />
<Home />
<Process />
<About />
<Projects />
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import Home from './components/Home.vue';
import Process from './components/Process.vue'
import About from './components/About.vue';
import Projects from './components/Projects.vue';
</script>

<style>
*{
  background-color: #F2F4F8;
}
a{
  text-decoration: none;
}
a:hover{
  color: #f3931c;
}
</style>
