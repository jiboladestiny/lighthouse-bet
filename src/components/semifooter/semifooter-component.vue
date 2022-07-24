<template>
  <div class="semi-footer">
    <div class="semi">
      <div class="container">
        <div class="row semi-all align-items-end justify-content-between">
          <div class="track">
            <img
            class="img-fluid"
              :src="require('./images/absolute.png')"
          />
          </div>
          <div class="col-md-4">
            <div>
              <img
                class="img-fluid"
              :src="require('./images/slippers.png')"
                alt=""
              />
            </div>
            <div>
              <img
                class="mb-3"
                width="400"
                height="300"
              :src="require('./images/baseball.jpg')"
                alt=""
              />
            </div>
          </div>

          <div class="col-md-4">
            <div>
              <img
                class="img-fluid d-block ms-auto"
                              :src="require('./images/sikwinechange.png')"

                alt=""
              />
            </div>
            <div>
              <img
                class="img-fluid"
                style="width:100%"
              :src="require('./images/highway.jpg')"
                alt=""
              />
            </div>
            <div>
              <img
                class="img-fluid d-block mx-auto"
              :src="require('./images/brooklin.png')"
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
@media only screen and (max-width: 1400px) {
  .track{
    img{
        width: 480px !important;
    }
  }
  
}

@media only screen and (max-width: 1200px) {
  .track{
    img{
        width: 430px !important;
    }
  }
  
}
@media only screen and (max-width: 990px) {
  .track{
    img{
        width: 390px !important;
        left: 23% !important;
    }
  }
  
}

@media only screen and (max-width: 770px) {
  .semi-footer{
    display: none;
  }
  
}
.semi-footer {
  background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAB4AAAALQAQMAAABL2v/VAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAADUExURQAAAKd6PdoAAAABdFJOU01Ii+VLAAAAv0lEQVR42u3BMQEAAADCoPVPbQ0PoAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAL4Mpe4AAc/biqoAAAAASUVORK5CYII=");
  .semi {
    height: 100%;
    width: 100%;
    background: rgba(0, 0, 0, 0.8);

    .semi-all {
      position: relative;

      .track {

        // z-index: -1;

        img{
        position: absolute;
        width: 520px;
        left: 30%;
        // -webkit-transform: translate(-50%, -50%);
        // -ms-transform: translate(-50%, -50%);
        // transform: translate(-50%, -50%);
        bottom:0;
        width: 500;
        transform: skew(-10deg);
        }
      }
    }
  }
}
</style>