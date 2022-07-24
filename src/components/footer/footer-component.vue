<template>
  <div class="footer py-3">
    <div class="container">
      <ul class="nav justify-content-center">
        <li class="nav-item">
          <a class="nav-link" href="#">About us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Partnership</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Help with deposits and withdrawals</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Q&A</a>
        </li>
      </ul>

      <div class="sponsors mt-3 mb-3">
        <div>
            <img src="http://skbet101.com/img/foot_bg.a236272b.png" class="img-fluid d-block mx-auto" alt="">
        </div>
      </div>

      <div class="copyright">
        <p>Copyright @ Sikwin Reserved</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.footer {
  background: rgb(0, 0, 0,0.9 );

  .nav {
    .nav-item:not(:last-child) {
      border-right-color: rgb(180, 181, 183);
      border-right-style: solid;
      border-right-width: 0.8px;
    }
    .nav-item {
      .nav-link {
        color: rgb(188, 188, 188) !important;
        font-size: 16px;
      }
    }
  }

  .copyright{
    text-align: center;
    color: white;
  }
}
</style>