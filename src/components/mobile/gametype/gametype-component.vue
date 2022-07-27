<template>
  <div class="game">
    <HeaderComponent/>
  </div>
</template>
<script>
import HeaderComponent from '@/components/mobile/gametype/gameheader-component.vue'
export default {
    components:{
        HeaderComponent

    }
}
</script>
<style lang="scss">
.game {
  margin-right: 0.55rem;
  margin-left: 0.55rem;
  border-radius: 0.8rem;
  margin-top: 0.5rem;
  background:	rgb(72,72,72);
  padding: 0.8rem 0.7rem;
}
</style>