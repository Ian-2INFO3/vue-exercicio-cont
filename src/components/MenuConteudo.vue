<script>
import NewBlock from "@/components/NewBlock.vue";
export default {
  components: { NewBlock },
};
</script>
<template>
  <main id="content">
    <NewBlock
      titulo="BLOCO-1"
      :nomes="['Meu mano Mateus Rafael', 'Meu mano Daniel']"
    />
    <NewBlock />
    <NewBlock />
    <NewBlock />
    <NewBlock
      titulo="URGENTE"
      :nomes="['Meu mano michas', 'Meu mano Wesley']"
      class="alerta"
    />
    <NewBlock />
    <NewBlock />
    <NewBlock class="alerta" />
  </main>
</template>
<style></style>
