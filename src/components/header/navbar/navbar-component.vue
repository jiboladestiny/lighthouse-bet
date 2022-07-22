<template>
  <div class="navbars">
    <div class="container">
      <ul class="nav-cont">
        <li>APP DOWNLOAD</li>
        <li><img :src="require('./images/home.png')" alt="" />HOME</li>
        <li class="">
          <div>
            <img
              class="icon-img"
              :src="require('./images/livecasino.png')"
              alt=""
            />
            LIVE CASINO
          </div>

          <div class="drop-cont container mx-auto">
            <div class="row">
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/qr-code.jpg')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/pragmatic.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/vivo-gaming.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/playtech.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/evolution.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/zugi.png')"
                  alt=""
                />
              </div>
            </div>
          </div>
        </li>
        <li>
          <img class="icon-img" :src="require('./images/sport.png')" alt="" />
          SPORTS

          <div class="drop-cont container mx-auto">
            <div class="row">
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/skinechange.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/highway.jpg')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/baseball.jpg')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/sbobet.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/bti.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/messi.png')"
                  alt=""
                />
              </div>
            </div>
          </div>
        </li>
        <li>
          <img class="icon-img" :src="require('./images/lottery.png')" alt="" />
          LOTTERY

          <div class="drop-cont container">
            <div class="row justify-content-center">
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/pool.png')"
                  alt=""
                />
              </div>
              <div class="col-lg-2 d-flex align-items-center py-4">
                <img
                  class="img-fluid"
                  :src="require('./images/lotterydrop.png')"
                  alt=""
                />
              </div>
            </div>
          </div>
        </li>
        <li>
          <img
            class="icon-img"
            :src="require('./images/teen.png')"
            alt=""
          />TEEN PATI
        </li>
        <li>
          <img
            class="icon-img"
            :src="require('./images/card.png')"
            alt=""
          />CARD GAME
        </li>
        <li>
          <img
            class="icon-img"
            :src="require('./images/slot.png')"
            alt=""
          />SLOT
        </li>
        <li>
          <img
            class="icon-img"
            :src="require('./images/promotion.png')"
            alt=""
          />PROMOTION
        </li>
        <li>
          <img
            class="icon-img"
            :src="require('./images/customer.png')"
            alt=""
          />CUSTOMER
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss">
.navbars {
  // height: 50px;
  // display: flex;
  // align-items: center;
  position: relative;
  .nav-cont {
    display: flex;
    justify-content: space-evenly;
    // margin-top: 5px;
    li {
      //   width: 10%;
      padding: 3px;
      font-size: 16px;
      height: 50px;
      display: flex;
      align-items: center;
      color: white;

      &:nth-child(1) {
        background: rgb(255, 255, 255, 0.3);
      }
      &:nth-child(3){
        // position: relative;

        .drop-cont {
            z-index: 500 !important;
          display: none;
          width: 100%;
          // height: 170px;
          background: rgb(0, 0, 0, 0.7);
          position: absolute;
          left: 50%;
          transform: translate(-50%, -50%);
          top: 11.9rem;
        }

        &:hover .drop-cont {
          display: block;
        }
      }


      &:nth-child(4),
      &:nth-child(5) {
        // position: relative;

        .drop-cont {
            z-index: 500 !important;

          display: none;
          width: 100%;
          // height: 170px;
          background: rgb(0, 0, 0, 0.7);
          position: absolute;
          left: 50%;
          transform: translate(-50%, -50%);
          top: 11.5rem;
        }

        &:hover .drop-cont {
          display: block;
        }
      }



      &:hover {
        background: rgb(255, 255, 255, 0.3);
      }

      &:hover .icon-img {
        visibility: visible;
      }

      .icon-img {
        visibility: hidden;
        margin-right: 5px;
      }
    }
  }
}
</style>