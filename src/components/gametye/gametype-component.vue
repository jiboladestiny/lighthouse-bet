<template>
<!-- fofo -->
  <div class="gametype">
    <div class="containers">
      <div class="container">
        <div class="row gy-5">
          <div class="col-lg-3 col-md-6">
            <div class="gametype-cont">
              <div class="overlay">
                <div class="text">
                  <button class="btn">PLAY FOR SPORTS</button>
                </div>
              </div>
              <div class="image-cont">
                <div class="texter">Sports</div>

                <img
                :src="require('./images/below.png')"
                  alt=""
                />
              </div>
              <img
                :src="require('./images/1.png')"

                class="main-img"
                alt=""
              />
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="gametype-cont">
              <div class="overlay">
                <div class="text">
                  <button class="btn">PLAY FOR LIVE</button>
                </div>
              </div>
              <div class="image-cont">
                <div class="texter">Live Casinos</div>

                <img
                :src="require('./images/below.png')"
                  alt=""
                />
              </div>
              <img
                class="main-img"
                :src="require('./images/2.png')"
                alt=""
              />
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="gametype-cont">
              <div class="overlay">
                <div class="text">
                  <button class="btn">PLAY FOR E-GAMES</button>
                </div>
              </div>
              <div class="image-cont">
                <div class="texter">E-Games</div>

                <img
                :src="require('./images/below.png')"
                  alt=""
                />
              </div>
              <img
                class="main-img"
                :src="require('./images/3.png')"

                alt=""
              />
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="gametype-cont">
              <div class="overlay">
                <div class="text">
                  <button class="btn">PLAY FOR CHESS</button>
                </div>
              </div>
              <div class="image-cont">
                <div class="texter">Chess games</div>

                <img
                :src="require('./images/below.png')"
                  alt=""
                />
              </div>
              <img
                class="main-img"
                :src="require('./images/4.png')"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@media only screen and (max-width: 992px) {
   .gametype-cont {
    margin-left: 2rem;
    margin-right: 2rem;
   }
}
@media only screen and (max-width: 992px) {
   .gametype-cont {
    margin-left: 2rem;
    margin-right: 2rem;
   }
}
.gametype {
  background-image: url("./images/bg.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: right bottom;
  // background-attachment: fixed;

  .containers {
    background: rgb(0, 0, 0, 0.7);
    height: 100%;
    padding: 3rem 0;

    .gametype-cont {
      cursor: pointer;
      position: relative;

      .image-cont {
        position: absolute;
        bottom: -2.6rem;
        right: 0;
        // width: 1rem;

        img{
            width: 12rem;
        }

        .texter {
          color:rgb(113, 34, 19);
          position: absolute;
          font-size: 15px;
          
          top: 50%;
          left: 50%;
          -webkit-transform: translate(-50%, -50%);
          -ms-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
        }
      }

      &:hover .overlay {
        opacity: 0.5;
      }

      .main-img {
        display: block;
        width: 100%;
        height: auto;
      }
      .overlay {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        height: 100%;
        width: 100%;
        opacity: 0;
        transition: 0.5s ease;
        background-color: black;

        .text {
          color: white;
          position: absolute;
          top: 50%;
          left: 50%;
          -webkit-transform: translate(-50%, -50%);
          -ms-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);

          button {
            color: white;
            border: 3px solid gold;
            font-size: 18px;
            padding: 10px 15px;
            width: 200px;
          }
        }
      }
    }
  }
}
</style>