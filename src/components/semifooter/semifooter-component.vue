<template>
  <div class="semi-footer">
    <div class="semi">
      <div class="container">
        <div class="row semi-all align-items-end justify-content-between">
          <div class="track">
            <img
            class="img-fluid"
            src="https://www.wallpaperuse.com/wallp/73-735466_m.png"
          />
          </div>
          <div class="col-md-4">
            <div>
              <img
                class="img-fluid"
                src="http://skbet101.com/games/6f23b61f-8125-4f6a-91ed-bcbb55c3cd86.png"
                alt=""
              />
            </div>
            <div>
              <img
                class="mb-3"
                width="400"
                height="300"
                src="http://skbet101.com/games/0ae8908b-4df6-4eff-bacc-367d8a2a71c4.jpg"
                alt=""
              />
            </div>
          </div>

          <div class="col-md-4">
            <div>
              <img
                class="img-fluid d-block ms-auto"
                src="https://sikwin-game.s3.ap-south-1.amazonaws.com/games/4c7d3248179c0080ad4567ca8007317d1654616585"
                alt=""
              />
            </div>
            <div>
              <img
                class="img-fluid"
                style="width:100%"
                src="http://skbet101.com/games/d0213f57-c483-4bb8-9789-c142b28604b5.jpg"
                alt=""
              />
            </div>
            <div>
              <img
                class="img-fluid d-block mx-auto"
                src="http://skbet101.com/games/012ea68f-f8e4-407c-a5c3-dbd21b3b32d3.png"
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
        width: 510px;
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