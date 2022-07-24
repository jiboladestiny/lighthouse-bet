<template>
    <div class="app">
        <HeaderComponent/>
         <carousel-component/>
       <GametypeComponent/>
        <SlotComponent/>
        <LiveComponent/>
        <SemifooterComponent/>
        <FooterComponent/>
    </div>
</template>

<script>
import CarouselComponent from './components/carousel/carousel-component.vue';
import HeaderComponent from "./components/header/headerwrapper-component/header-component.vue";
import GametypeComponent from './components/gametye/gametype-component.vue';
import SlotComponent from './components/slot/slot-component.vue';
import LiveComponent from './components/live/live-component.vue';
import SemifooterComponent from './components/semifooter/semifooter-component.vue';
import FooterComponent from './components/footer/footer-component.vue';
export default {
    components:{
    HeaderComponent,
    CarouselComponent,
    GametypeComponent,
    SlotComponent,
    LiveComponent,
    SemifooterComponent,
    FooterComponent
}
}
</script>

