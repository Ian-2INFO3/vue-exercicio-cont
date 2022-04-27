<script>
import NewBlock from "@/components/NewBlock.vue";
export default {
  components: { NewBlock },
  data() {
    return {
      alunos1: ["Meu mano Mateus Rafael", "Meu mano Daniel"],
    };
  },
};
</script>
<template>
  <main id="content">
    <NewBlock titulo="BLOCO-1" :nomes="alunos1" />
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
