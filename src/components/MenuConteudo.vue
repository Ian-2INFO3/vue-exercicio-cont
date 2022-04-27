<script>
import NewBlock from "@/components/NewBlock.vue";
export default {
  components: { NewBlock },
};
</script>
<template>
  <main id="content">
    <NewBlock titulo="BLOCO-1" />
    <NewBlock />
    <NewBlock />
    <NewBlock />
    <NewBlock titulo="URGENTE" class="alerta" />
    <NewBlock />
    <NewBlock />
    <NewBlock class="alerta" />
  </main>
</template>
<style></style>
