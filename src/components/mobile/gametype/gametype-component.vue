<template>
  <div class="game">
    <div class="game-cont">
      <HeaderComponent />
      <TabComponent />
      <MenuComponent/>
    </div>
  </div>
</template>
<script>
import HeaderComponent from "@/components/mobile/gametype/gameheader-component.vue";
import TabComponent from "./tab/tab-component.vue";
import MenuComponent from "./menu-component.vue";
export default {
  components: {
    HeaderComponent,
    TabComponent,
    MenuComponent
},
};
</script>
<style lang="scss">
.game {
  // margin-right: 0.55rem;
  // margin-left: 0.55rem;
  width: 96%;
  margin: 0 auto;
  border-radius: 0.8rem;
  margin-top: 0.5rem;
  background:	rgb(56,56,56);
  padding: 0.9rem 0.7rem;
  // height: 25rem;
  margin-bottom:-1rem !important;
  height: calc(100vh - 22rem);

  // overflow-y: scroll;

  .game-cont {
    height: 100%;
    width: 100%;
  }
}
</style>