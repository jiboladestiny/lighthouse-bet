<template>
  <div class="social">
    <div class="social-wrapper container">
      <ul class="left">
        <li>
          <img
            :src="require('./images//youtube-svgrepo-com.svg')"
            alt=""
            width="25"
          />
        </li>
        <li>
          <img :src="require('./images/facebook.png')" width="25" alt="" />
        </li>
        <li>
          <img :src="require('./images/instagram.png')" width="25" alt="" />
        </li>
        <li>
          <img :src="require('./images/telegram.png')" width="25" alt="" />
        </li>
      </ul>

      <ul class="right">
        <li><button class="btn btn-danger btn-sm">Login</button></li>
        <li><button class="btn btn-warning btn-sm">Sign-up</button></li>
        <li>
          <select
            class="form-select form-select-sm"
            aria-label=".form-select-sm example"
          >
            <option value="2">English</option>
            <option value="3">Hindi</option>
          </select>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss">
.social {
  border-bottom: 1px solid yellow;
  backdrop-filter: black;
  // background: rgb(81, 90, 110);
  .social-wrapper {
    // background: red;
    height: 70px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .left {
    margin-top: 8px;

      display: flex;
      list-style-type: none;
      align-items: center;

      li:not(:last-child) {
        margin-right: 1rem;
      }
    }

    .right {
    margin-top: 8px;

      display: flex;
      list-style-type: none;
      align-items: center;
      // color: white;

      li {
        .btn {
          color: white;
          font-size: 16px;
        }
        &:not(:first-child) {
          margin-left: 1rem;
        }

        select {
          background:transparent;
          color: white;
          border: none;
        //   padding: 0.4rem 1rem;
        //   font-size: 16px;

          option {
            background: rgb(24, 24, 24);
            color: white;
          }
        }
      }
    }
  }
}
</style>