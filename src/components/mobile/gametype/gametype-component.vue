<template>
  <div class="game">
    <HeaderComponent />
    <TabComponent />
  </div>
</template>
<script>
import HeaderComponent from "@/components/mobile/gametype/gameheader-component.vue";
import TabComponent from "./tab/tab-component.vue";
export default {
  components: {
    HeaderComponent,
    TabComponent,
  },
};
</script>
<style lang="scss">
.game {
  margin-right: 0.55rem;
  margin-left: 0.55rem;
  border-radius: 0.8rem;
  margin-top: 0.5rem;
  background: rgb(72, 72, 72);
  padding: 0.8rem 0.7rem;
  height: calc(100vh - 23.5rem);
  // overflow-y: scroll;
}
</style>