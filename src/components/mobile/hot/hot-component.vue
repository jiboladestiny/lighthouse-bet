<template>
  <div class="hot">
    <div class="ms-2">Hot Game</div>

    <div class="hot-cont">
      <i @click="right()" class="right bx bx-chevrons-right"></i>
      <i @click="left()" class="left bx bx-chevrons-left"></i>

      <div>
        <img
          class="img-fluid"
          :src="require('./images/sbobet.png')"
          alt=""
        />
      </div>
      <div>
        <img
          class="img-fluid"
          :src="require('./images/evolution.png')"
          alt=""
        />
      </div>
      <div>
        <img class="img-fluid" :src="require('./images/skinechange.png')" alt="" />
      </div>
      <div>
        <img
          class="img-fluid"
          :src="require('./images/pragmatic.png')"
          alt=""
        />
      </div>
      <div>
        <img
          class="img-fluid"
          :src="require('./images/zugi.png')"
          alt=""
        />
      </div>
      <div>
        <img
          class="img-fluid"
          :src="require('./images/playtech.png')"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    right() {
      var right = document.querySelector(".hot-cont");
      right.scrollBy(100, 0);
    },
    left() {
      var right = document.querySelector(".hot-cont");
      right.scrollBy(-100, 0);
    },
  },
};
</script>

<style lang="scss">
.hot {
  
  position: relative;
  width: 96%;
  margin: 0 auto;
  border-radius: 0.8rem;
  margin-top: 0.5rem;
  background:	rgb(56,56,56);
  padding: 0.4rem 0.3rem;
  color: gold;

  div {
    font-size: 14px;
    margin-bottom: 0.3rem;
  }

  .hot-cont {
    i {
      cursor: pointer;
        background:rgb(64,64,64);
      border-radius: 1rem;
      font-size: 1.4rem;
      position: absolute;
      top: 60%;
      transform: translate(-50%, -50%);
    }
    .right {
      right: 0;
    }
    .left {
      left: 1rem;
    }
    display: flex;
    overflow-x: auto;

    &::-webkit-scrollbar {
      width: 0 !important;
    }
    div {
      img {
        min-width: 80px;
        height: 80px;
        background: white;
        margin-right: 0.4rem;
        border-radius: 0.5rem;
        transition: all ease-in 1s;
      }
    }
  }
}
</style>