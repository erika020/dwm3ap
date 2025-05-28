<script setup>
import Titulo from '../components/Titulo.vue'
import Template from '../components/Template.vue'
</script>
<template>
  <Titulo texto="hola soy un titulo" />
  <Template>
    <template #parrafo>
      <p>Esto se muestra solo en párrafo</p>
    </template>
    <p>Todo lo que esté dentro va a slot</p>
  </Template>
</template>
