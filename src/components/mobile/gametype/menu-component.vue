<template>
  <div class="menu-tab">
    <ul
      class="nav nav-pills d-flex justify-content-around"
      id="pills-tab"
      role="tablist"
    >
      <li class="nav-item" role="presentation">
        <div
          class="nav-link active"
          id="pills-home-tab"
          data-bs-toggle="pill"
          data-bs-target="#pills-home"
          type="div"
          role="tab"
          aria-controls="pills-home"
          aria-selected="true"
        >
          <img
            width="20"
            class="active"
            :src="require('./images/homeactive.png')"
            alt=""
          />

          <img
            width="20"
            class="not-active"
            :src="require('./images/home.png')"
            alt=""
          />
        </div>
      </li>
      <li class="nav-item" role="presentation">
        <div
          class="nav-link"
          id="pills-profile-tab"
          data-bs-toggle="pill"
          data-bs-target="#pills-profile"
          type="div"
          role="tab"
          aria-controls="pills-profile"
          aria-selected="false"
        >
          <img
            width="20"
            class="active"
            :src="require('./images/giftactive.png')"
            alt=""
          />

          <img
            width="20"
            class="not-active"
            :src="require('./images/gift.png')"
            alt=""
          />
        </div>
      </li>
      <li class="nav-item" role="presentation">
        <div
          class="nav-link"
          id="pills-contact-tab"
          data-bs-toggle="pill"
          data-bs-target="#pills-contact"
          type="div"
          role="tab"
          aria-controls="pills-contact"
          aria-selected="false"
        >
          <img
            width="20"
            class="active"
            :src="require('./images/moneyactive.png')"
            alt=""
          />

          <img
            width="20"
            class="not-active"
            :src="require('./images/money.png')"
            alt=""
          />
        </div>
      </li>

      <li class="nav-item" role="presentation">
        <div
          class="nav-link"
          id="pills-chat-tab"
          data-bs-toggle="pill"
          data-bs-target="#pills-chat"
          type="div"
          role="tab"
          aria-controls="pills-chat"
          aria-selected="false"
        >
          <img
            width="20"
            class="active"
            :src="require('./images/chatactive.png')"
            alt=""
          />

          <img
            width="20"
            class="not-active"
            :src="require('./images/chat.png')"
            alt=""
          />
        </div>
      </li>

      <li class="nav-item" role="presentation">
        <div
          class="nav-link"
          id="pills-person-tab"
          data-bs-toggle="pill"
          data-bs-target="#pills-person"
          type="div"
          role="tab"
          aria-controls="pills-person"
          aria-selected="false"
        >
          <img
            width="20"
            class="active"
            :src="require('./images/personactive.png')"
            alt=""
          />

          <img
            width="20"
            class="not-active"
            :src="require('./images/person.png')"
            alt=""
          />
        </div>
      </li>
    </ul>
  </div>
</template>

<style lang="scss">
.menu-tab {
  ul {
    box-shadow: 0px 2px 35px -4px rgba(0, 0, 0, 0.81);
    -webkit-box-shadow: 0px 2px 35px -4px rgba(0, 0, 0, 0.81);
    -moz-box-shadow: 0px 2px 35px -4px rgba(0, 0, 0, 0.81);
    padding: 0.3rem 0;
    position: fixed;
    bottom: 2.3rem;
    right: 50%;
    transform: translate(50%, 50%);
    width: 96%;
    // background: red;
    background:	rgb(56,56,56);
    border-radius: 3rem;

    div {
      padding: 0 !important;
      background: transparent !important;
    }
    .nav-link {
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
}
</style>