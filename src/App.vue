<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Rodape from "@/components/MenuRodape.vue";
import Conteudo from "@/components/MenuConteudo.vue";
import Cabecalho from "@/components/MenuCabecalho.vue";
export default {
  components: { MenuLateral, Rodape, Conteudo, Cabecalho },
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <Rodape />
  <Conteudo />
</template>
<style></style>
