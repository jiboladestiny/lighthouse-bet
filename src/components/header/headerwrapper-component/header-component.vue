<template>
    <div>
        <div class="header">
            <div class="wrapper">
                    <SocialComponent />
                <NavbarComponent/>
                </div>
        </div>
    </div>
</template>

<script>
import SocialComponent from '../socialbar/social-component.vue'
import NavbarComponent from '../navbar/navbar-component.vue'
export default {
    components:{
    SocialComponent,
    NavbarComponent
}
}
</script>


<style lang="scss">

.header {
//   height: auto;
  background-image: url('./images//header-bg.png');
  background-repeat: no-repeat;
  .wrapper{
    background: rgb(12, 12, 12,0.7);
  }
}
</style>