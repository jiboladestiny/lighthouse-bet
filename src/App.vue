<template>
  <div class="app">
    <HeaderComponent />
    <carousel-component />
    <div class="show-mobile">
      <HotComponent />
      <GameComponent />
    </div>
    <div class="mobile">
      <GametypeComponent />
      <SlotComponent />
      <LiveComponent />
      <SemifooterComponent />
      <FooterComponent />
    </div>
  </div>
</template>

<script>
import CarouselComponent from "./components/carousel/carousel-component.vue";
import HeaderComponent from "./components/header/headerwrapper-component/header-component.vue";
import GametypeComponent from "./components/gametye/gametype-component.vue";
import SlotComponent from "./components/slot/slot-component.vue";
import LiveComponent from "./components/live/live-component.vue";
import SemifooterComponent from "./components/semifooter/semifooter-component.vue";
import FooterComponent from "./components/footer/footer-component.vue";
import HotComponent from "./components/mobile/hot/hot-component.vue";
import GameComponent from "./components/mobile/gametype/gametype-component.vue";

export default {
  components: {
    HeaderComponent,
    CarouselComponent,
    GametypeComponent,
    SlotComponent,
    LiveComponent,
    SemifooterComponent,
    FooterComponent,
    HotComponent,
    GameComponent,
  },
};
</script>
<style>
@media only screen and (max-width: 576px) {
    body {
    /* min-height: 100vh; */

  }
  .mobile {
    display: none;

    
  }

  body {
    background: rgb(48, 48, 48);
    margin: 0;
    overflow: scroll;

  }
}
</style>
