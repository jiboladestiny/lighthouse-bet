<template>
  <div class="live">
    <div class="live-bg">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 d-lg-flex indi d-md-none">
            <img
              style="cursor: pointer"
              :src="require('./images/alhaja.png')"
              alt=""
            />
          </div>
          <div class="col-lg-9 col-md-12" style="z-index: auto !important">
            <div class="row g-0 inner-live-cont">
              <div class="col-lg-4 col-md-6 col-sm-6">
                <div
                  class="
                    live-cont
                    d-flex
                    align-items-center
                    justify-content-center
                    text-center
                  "
                >
                  <div>
                    <img
                      :src="require('./images/aecasino.png')"
                      alt=""
                      class="mb-1"
                    />

                    <h1 class="mb-1">AE LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6 col-sm-6">
                <div
                  class="
                    live-contain
                    d-flex
                    align-items-center
                    justify-content-center
                    text-center
                  "
                >
                  <div>
                    <img
                      :src="require('./images/play.png')"
                      class="mb-2"
                      alt=""
                    />

                    <h1 class="mb-1">PP LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6 col-sm-6">
                <div
                  class="
                    live-cont
                    d-flex
                    align-items-center
                    justify-content-center
                    text-center
                  "
                >
                  <div>
                    <h1>VIVO LIVE</h1>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6 col-sm-6">
                <div
                  class="
                    live-contain
                    d-flex
                    align-items-center
                    justify-content-center
                    text-center
                  "
                >
                  <div>
                    <h1>PT LIVE</h1>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6 col-sm-6">
                <div
                  class="
                    live-cont
                    d-flex
                    align-items-center
                    justify-content-center
                    text-center
                  "
                >
                  <div>
                    <img
                      :src="require('./images/evolution.png')"
                      class="mb-2"
                      alt=""
                    />

                    <h1 class="mb-1">EVO LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6 col-sm-6">
                <div
                  class="
                    live-contain
                    d-flex
                    align-items-center
                    justify-content-center
                    text-center
                  "
                >
                  <div>
                    <img
                      :src="require('./images/ezlive.png')"
                      class="mb-2"
                      alt=""
                    />

                    <h1 class="mb-1">EZ LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@media only screen and (max-width: 992px) {
  .indi {
    display: none !important;
  }
}
.live {
  background-image: url("http://skbet101.com/img/background.cc39b8a5.png");
  // padding: 3rem;
  // background-repeat: no-repeat;
  //   background-size: cover;
  background-position: left right;

  .live-bg {
    background: rgb(0, 0, 0, 0.7);

    .inner-live-cont {
      .live-cont {
        background-image: url("./images/bg.png");
        color: whitesmoke;
        height: 300px;
        // width: 100%;
        background: rgba(255, 255, 255, 0.1);
        cursor: pointer;

        &:hover {
          border: 4px solid #ffcf51;
        }
      }

      .live-contain {
        cursor: pointer;

        background-image: url("./images/grid-bg.png");
        color: whitesmoke;
        height: 300px;
        // width: 100%;
        background: rgba(4, 4, 4, 0.1);

        &:hover {
          border: 4px solid #ffcf51;
        }
      }
    }
  }
}
</style>