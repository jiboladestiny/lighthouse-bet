<template>
  <div>
    <div class="slot">
      <div class="slot-dark-bg py-4">
        <div class="container">
          <div class="row">
            <div class="col-lg-4">
              <div class="mg-slot align-items-center d-flex">
                <div class="me-3 p-3">
                  <img
                :src="require('./images/mg.png')"
                    width="120"
                    alt=""
                  />
                </div>

                <div class="slot-text">
                  <h3>MG SLOT</h3>
                  <h3>E-Games</h3>
                </div>
              </div>
              <div class="mg-slot align-items-center d-flex">
                <div class="me-3 p-3">
                  <img
                :src="require('./images/jd.png')"
                    width="120"
                    alt=""
                  />
                </div>

                <div class="slot-text">
                  <h3>JDB SLOT</h3>
                  <h3>E-Games</h3>
                </div>
              </div>
              <div class="jd-slot"></div>
            </div>
            <div class="col-lg-8">
              <img
                :src="require('./images/coin.png')"
                class="img-fluid d-block mt-3"
                alt=""
              />

              <div class="d-grid mt-5 col-md-4 col-5 mx-auto">
                <button class="btn btn-lg betnow-btn">Bet now</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.slot {
  background-image: url("./images/bg.png");
  .slot-dark-bg {
    background: rgb(0, 0, 0, 0.8);

    .betnow-btn {
      background: red;
      font-style: italic;
      color: #ffcf51;
      border: 1px solid #ffcf51;
      background: transparent;
    }

    .mg-slot {
      color: white;
      font-style: italic;
      &:hover {
        background: rgb(255, 255, 255, 0.2);
        cursor: pointer;
        color: rgb(225, 127, 0);
      }
    }
  }
}
</style>