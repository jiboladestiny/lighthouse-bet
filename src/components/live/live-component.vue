<template>
  <div class="live">
    <div class="live-bg">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 d-lg-flex indi d-md-none">
            <img style="cursor:pointer;" src="http://skbet101.com/img/rw.4f1c2852.png" alt="" />
          </div>
          <div class="col-lg-9 col-md-12" style="z-index:auto !important">
            <div class="row g-0 inner-live-cont">
              <div class="col-lg-4 col-md-6">
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
                      src="data:image/png;base64,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"
                      alt=""
                      class="mb-1"
                    />

                    <h1 class="mb-1">AE LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6">
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
                      src="data:image/png;base64,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"
                      class="mb-2"
                      alt=""
                    />

                    <h1 class="mb-1">PP LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-6">
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
              <div class="col-lg-4 col-md-6">
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
              <div class="col-lg-4 col-md-6">
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
                      src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAAATCAMAAABRG1gfAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAKaUExURUdwTP///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////50XL7YAAADddFJOUwADMgrYAeQCqP3UC+6a8PJzHyhZYRxo2ZcU0vYNqwwdsREOYm4lEBuGzje5a6ZgxoVD+3gvw6xH9evXe6RU98Qe3M3TOE5Nwifmv0v44XDRGYKOtTv6jRKU6hV0s2mgx54mMeDfGNBeNFEWaiHsnON8BVLBh7BsF37Ju1dk5/HWOVA6Vjyq/vRmLE+j1ZEwi4/PwK8InSp5vTPpREw2CSO23kHKuBqnrpjtkOVdvED8BLqfW1NxSowPby3iyyQid+iB776TPYlIlVit3UlFm/OyRkJflsyE22cpNT+IBNSkQQAAA4xJREFUOMu1lfVb1EEQxuc4ATlO8U5EkRYJARUQCUFKERBQUewCuwUFbLGxu7u7u7u7+/1fnN393hcOj+fxF+eHu513d+dzszO7RxbP7pN9BkY23Uz/0dKgLHa88u8uctKsKMDhBvdLUVmO9IBxTqH1QebAZv2k76f7WONwQ/oyNK8jue5wJ2oLnK4P4pqhB90m/KU1kMcONzRzQwN7ZXT7nfwZD3jWe16d9aBu+9htCMz82FSYV9y/QfYmydSCK/wi6q/KFp1yVEG6/p2uM39cD3IM8fVAp9q+0buW43/EmezL4GKQkAXagiEuZ8T6kFlJn6ksvCewep2/BvlQUHCZp1aOujVube45JI6poOCC1UtYGjo8FSNXlfAoJTel/wA3TJ2rok1rrFGKJCSLwsIsE4j6ATd4tgewmHLVArNFQb4Dg3mqNZC3UE40pnBgGtEjLdJColfIyJbjdorinN45um3khbQlEiJtOJEVaM+TbfCN+gDdV1gDgTYUJCCeQGue8hLFfpCKUxNf0HqgG60DRsYE9AaqjdSco3SIiwQy9YPdHV18cZhTDWQWi7MRG0Y5QGGYiM62EYgge0gTcn+ILjxuIeb6Yv4MHkcDX6kTUEo0wQcDJcGySYt8VUIKE8aOjcpjvRuQTHMB309AD60TwzmQPaSVB0wK8qMX8F6sWwFspA2Ahcct4SGkKFvhJxvtu6uVGWmcjonWAK+FUASsonyGBAOV7C+3h4SsBXprHZhJX2DmO0pjuF5Eg/UWPqxaeJHegOG4nzAPhVQOeAl/JfBbZrJcpdZBg2jHZU0Hlop1XM1szsRslJkwZE/NFd9V957cBHqKpN9w3YXP9f8la5IFpLB/SEBCq22Z/CRgngh8T2RUpTKRkI46YxgpSOC1RsKOJavJ6ax2AeIjFrxkJoUKyCTWy2P4uWKI0YzERpWiu/LoLfdSQtxJIDWUu0uHPNEZ2fLHx9ckxg21mL+CWc3xUdI7KwXIB1I2oY+Jm5SIOxuj6Ckwngy3tb1ziDIw35e3mrjwfWwhp5DrIH4CjsNFM+wnGnQAJn/BnjElH0h8Ppqo11SRm/MAccu4/YayEniCL1Qy8IzofGkSTwwZQeIUqsTRbedHJ8YvltX84hAKmjjzID9TtYyka/sfCbljlBfXoKT+W715bHDVNF5pkM9U2aQc9cgZlKAi+FtHlIjt3u2unP0/f4x/ALyIFejemnXJAAAAAElFTkSuQmCC"
                      class="mb-2"
                      alt=""
                    />

                    <h1 class="mb-1">EVO LIVE</h1>
                    <h4>Live casino</h4>
                  </div>
                </div>
              </div>
              <div class="col-lg-4  col-md-6">
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
                      src="data:image/png;base64,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"
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
  .indi{
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
        background-image: url("data:image/png;base64,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");
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

        background-image: url("data:image/png;base64,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");
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