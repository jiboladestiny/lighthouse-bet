<template>
  <div class="tab-cont d-flex">
    <div
      class="nav nav-pills"
      id="v-pills-tab"
      role="tablist"
      aria-orientation="vertical"
    >
      <div
        class="nav-link active"
        id="v-pills-live-tab"
        data-bs-toggle="pill"
        data-bs-target="#v-pills-live"
        type="div"
        role="tab"
        aria-controls="v-pills-live"
        aria-selected="true"
      >
        <img class="active" :src="require('./images/liveactive.png')" alt="" />

        <img class="not-active" :src="require('./images/live.png')" alt="" />
      </div>
      <div
        class="nav-link"
        id="v-pills-sport-tab"
        data-bs-toggle="pill"
        data-bs-target="#v-pills-sport"
        type="div"
        role="tab"
        aria-controls="v-pills-sport"
        aria-selected="false"
      >
        <img class="active" :src="require('./images/sportactive.png')" alt="" />

        <img class="not-active" :src="require('./images/sport.png')" alt="" />
      </div>
      <div
        class="nav-link"
        id="v-pills-lottery-tab"
        data-bs-toggle="pill"
        data-bs-target="#v-pills-lottery"
        type="div"
        role="tab"
        aria-controls="v-pills-lottery"
        aria-selected="false"
      >
        <img
          class="active"
          :src="require('./images/lotteryactive.png')"
          alt=""
        />

        <img class="not-active" :src="require('./images/lottery.png')" alt="" />
      </div>
      <div
        class="nav-link"
        id="v-pills-tempati-tab"
        data-bs-toggle="pill"
        data-bs-target="#v-pills-tempati"
        type="div"
        role="tab"
        aria-controls="v-pills-tempati"
        aria-selected="false"
      >
        <img
          class="active"
          :src="require('./images/tempatiactive.png')"
          alt=""
        />

        <img class="not-active" :src="require('./images/tempati.png')" alt="" />
      </div>
      <div
        class="nav-link"
        id="v-pills-poker-tab"
        data-bs-toggle="pill"
        data-bs-target="#v-pills-poker"
        type="div"
        role="tab"
        aria-controls="v-pills-poker"
        aria-selected="false"
      >
        <img class="active" :src="require('./images/pokeractive.png')" alt="" />

        <img class="not-active" :src="require('./images/poker.png')" alt="" />
      </div>
      <div
        class="nav-link"
        id="v-pills-slot-tab"
        data-bs-toggle="pill"
        data-bs-target="#v-pills-slot"
        type="div"
        role="tab"
        aria-controls="v-pills-slot"
        aria-selected="false"
      >
        <img class="active" :src="require('./images/slotactive.png')" alt="" />

        <img class="not-active" :src="require('./images/slot.png')" alt="" />
      </div>
    </div>

    <div class="tab-content" id="v-pills-tabContent">
      <!-- first tab -->
      <div
        class="tab-pane fade show active"
        id="v-pills-live"
        role="tabpanel"
        aria-labelledby="v-pills-live-tab"
      >
        <img
          :src="require('./images/1.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/2.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/3.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/4.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/1.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/2.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
      </div>
      <!-- first tab -->

      <!-- second tab -->
      <div
        class="tab-pane fade"
        id="v-pills-sport"
        role="tabpanel"
        aria-labelledby="v-pills-sport-tab"
      >
        <img
          :src="require('./images/4.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/3.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/2.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/1.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/1.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/2.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
      </div>
      <!-- second tab -->

      <!-- third tab -->
      <div
        class="tab-pane fade"
        id="v-pills-lottery"
        role="tabpanel"
        aria-labelledby="v-pills-lottery-tab"
      >
        <img
          :src="require('./images/4.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/4.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
      </div>
      <!-- third tab -->

      <!-- fourth tab -->
      <div
        class="tab-pane fade"
        id="v-pills-tempati"
        role="tabpanel"
        aria-labelledby="v-pills-tempati-tab"
      >
        <img
          :src="require('./images/3.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <img
          :src="require('./images/3.jpg')"
          class="img-fluid"
          alt=""
          srcset=""
        />
      </div>
      <!-- fourth tab -->
    </div>
  </div>
</template>

<div>

</div>

<style lang="scss">
.tab-cont {
  width: 100%;
  height: calc(100% - 60px);
  background: red;
  // float: left;
  // background: red;
  .nav-pills {
    width: 20%;
    height: 100%;
    overflow: scroll;
    background: yellow;

    &::-webkit-scrollbar {
      width: 0 !important;
    }

    .nav-link {
      padding: 0 !important;
      background: transparent !important;
      box-shadow: none !important;
      margin-bottom: 0rem !important;

      img {
        width: 100%;
      }

      .active {
        display: none;
      }

      .not-active {
        display: block;
      }
    }

    .nav-link.active {
      .not-active {
        display: none;
      }

      .active {
        display: block;
      }
    }
  }

  .tab-content {
    background: blue;
    padding-top: 0.5rem;
    height: 100%;
    overflow: scroll;
    width: 80%;

    &::-webkit-scrollbar {
      width: 0 !important;
    }

    .tab-pane {
      img {
        margin-bottom: 5px;
        border-radius: 8px;
      }
    }
  }
}
</style>