<template>
  <table-main />
  <MiBotonBasico :etiqueta = "etiqueta"></MiBotonBasico>
</template>

<script setup>
  import { ref } from 'vue';
  import TableMain from '@/components/TablaMain.vue'
  import MiBotonBasico from '@/components/MiBotonBasico.vue'
  
  const etiqueta = ref("OKAY");
</script>