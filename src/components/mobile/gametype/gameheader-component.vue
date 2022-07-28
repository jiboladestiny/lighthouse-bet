<template>
  <div class="game-head">
    <div class="lefts">
      <img
        class="me-2 mb-2"
        :src="require('./images/ho_my1@2x.png')"
        width="27"
        alt=""
      />

      <div class="left-cont">
        <p>Welcome</p>
        <p href=""><a href="">Please login !</a></p>
      </div>
    </div>
    <div class="rights">
      <img
        width="18"
        height="18"
        :src="require('./images/speaker.png')"
        alt=""
      />
      <div class="right-cont">
        <div>IMPORTANT NOTICE</div>
        <div>Attention</div>
        <div>Anouncement</div>
        <div>test</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.game-head {
  display: flex;
  border-bottom: 1px solid rgb(60, 60, 60);
  height: 60px;
  width: 100%;
  align-items: center;
  // background:white;
  // padding: 0.4rem 0;
  // height: 50px;
  // background: blue;

  .rights {
    display: flex;
    align-items: flex-start;
    .right-cont {
      height: 36px;
      overflow-y: scroll;
      margin-top: -4px;
      margin-left: 0.5rem;
      color: gray;
      width: 100px;
      font-size: 12px;
      line-height: 1rem;

      &::-webkit-scrollbar {
        width: 0 !important;
      }
      div {
        height: 38px;
      }
    }
  }
  .lefts {
    display: flex;
    align-items: center;

    .left-cont {
      a {
        color: gold;
        font-size: 14px;
      }
      p:first-child {
        color: gray;
        font-size: 14px;
      }
      p {
        line-height: 4px;
      }
    }
  }
  .lefts,
  .rights {
    width: 50%;
  }
}
</style>