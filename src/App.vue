<script>
import MenuLateral from "@/components/MenuLateral.vue";
import ComponenteCabecalho from "@/components/ComponenteCabecalho.vue";
import ComponenteRodape from "@/components/ComponenteRodape.vue";
import ComponentPrincipal from "@/components/ComponentPrincipal.vue";
export default {
  components: { MenuLateral, ComponenteCabecalho, ComponenteRodape, ComponentPrincipal, },
};
</script>
<template>
  <MenuLateral />
  <ComponenteCabecalho />
  <ComponenteRodape/>
  <ComponentPrincipal/>
</template>
<style></style>