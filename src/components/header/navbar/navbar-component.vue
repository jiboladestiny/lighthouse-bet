<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <div>
        <i class='bx bxs-bell'></i>
      </div>
      <a href="" class="navbar-brand"
        ><img :src="require('./images/logo.png')" width="100" alt=""
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarTogglerDemo01"
        aria-controls="navbarTogglerDemo01"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <i class="bx bx-menu"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li>APP DOWNLOAD</li>
          <li><img class="me-1" :src="require('./images/home.png')" alt="" />HOME</li>
          <li class="">
            <div>
              <img
                class="icon-img"
                :src="require('./images/livecasino.png')"
                alt=""
              />
              LIVE CASINO
            </div>

            <div class="drop-cont container">
              <div class="row gy-2 d-flex justify-content-center">
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
            <img
              class="icon-img"
              :src="require('./images/lottery.png')"
              alt=""
            />
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
          <li class="d-lg-none d-xl-flex d-xxl-flex">
            <img
              class="icon-img"
              :src="require('./images/card.png')"
              alt=""
            />CARD GAME
          </li>
          <li class="d-lg-none d-xl-flex d-xxl-flex">
            <img
              class="icon-img"
              :src="require('./images/slot.png')"
              alt=""
            />SLOT
          </li>
          <li class="d-lg-none d-xl-none d-xxl-flex">
            <img
              class="icon-img"
              :src="require('./images/promotion.png')"
              alt=""
            />PROMOTION
          </li>
          <li class="d-lg-none d-xl-none d-xxl-none">
            <img
              class="icon-img"
              :src="require('./images/customer.png')"
              alt=""
            />CUSTOMER
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss">
@media only screen and (min-width:576px) {
  .navbar{
    i{
      display: none !important;
    }
  }
}
@media only screen and (max-width:576px) {
   .navbar{
 
    .navbar-brand{
      margin: 0 auto !important;
    }

    .bxs-bell{
      font-size:23px;
    }
   }
}

@media only screen and (max-width: 992px) {
 .drop-cont{
  display: none !important;
 }
     .navbar-brand {
      display: block;
    }


      .navbar-collapse {
        z-index: 50 !important;
        position: absolute;
        top: 3rem;
        background: black;
        width: 80%;
    }
}





// Example
// Apply styles starting from medium devices and up to extra large devices
@media (min-width: 992px) and (max-width: 1199.98px) { 
    .navbar {
    // background: red !important;

    li{
        &:nth-child(3),&:nth-child(4),&:nth-child(5) {
        // position: relative;

        .drop-cont {

          top: 9.7rem !important;
        }

      }

      &:nth-child(4),&:nth-child(5) {
        // position: relative;

        .drop-cont {

          top: 9.4rem !important;
        }

      }

    }

  }

  //  body{
  //   background: red;
  //  }
 }
@media (min-width: 1200px) and (max-width: 1399.98px) { 
    .navbar {
    // background: red !important;

    li{
        &:nth-child(3),&:nth-child(4),&:nth-child(5) {
        // position: relative;

        .drop-cont {

          top: 10.8rem !important;
        }

      }

&:nth-child(4),&:nth-child(5) {
        // position: relative;

        .drop-cont {

          top: 10.4rem !important;
        }

      }

    }

  }
 }

.navbar {
  background:black !important;
  // height: 100% !important;
  padding: 0 !important;

  i {
    color: gold !important;
    font-size: 2.5rem;
  }

  .navbar-nav {
    li {
      cursor: pointer;
      color: white;
      display: flex;
      align-items: center;
      margin-top: 0 !important;
      height: 50px;
      padding: 0 0.5rem !important;

      i {
        font-size: 16px;
        color: white;
      }

      &:hover {
        background: rgb(255, 255, 255, 0.3);
      }

      &:hover .icon-img {
        visibility: visible;
      }

      .icon-img {
        visibility: hidden;
        margin-right: 3px;
      }





          &:nth-child(1) {
        background: rgb(255, 255, 255, 0.3);
      }
      &:nth-child(3) {
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









    }
  }
}


</style>