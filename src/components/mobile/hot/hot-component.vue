<template>
  <div class="hot">
    <span class="ms-2">Hot Game</span>

    <div class="hot-cont">
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <!-- <div></div> -->
    </div>
  </div>
</template>

<style lang="scss">
.hot {
  margin-right: 0.3rem;
  margin-left: 0.3rem;
  border-radius: 0.8rem;
  margin-top: 0.5rem;
  background: rgb(0, 0, 0);
  padding: 0.5rem 0.2rem;
  color: gold;

  .hot-cont {
    display: flex;
    overflow-x: auto;

    // &::-webkit-scrollbar{
    //     width: 0;
    // }
    div {
      min-width: 80px;
      height: 80px;
      background: white;
      margin-right: 0.3rem;
    }
  }
}
</style>