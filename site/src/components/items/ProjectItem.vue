<script setup>
defineProps({
  nome: {
    type: String,
    required: true
  },
  desc: {
    type: String,
    required: true
  },
  link: {
    type: String,
    required: true
  }
})
</script>

<template>
    <a href="{link}">
        <h1>{nome}</h1>
    </a>
    <p>{desc}</p>

</template>