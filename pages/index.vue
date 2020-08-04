<template>
  <div class="home">
    <div class="col-12 py-5 text-center">
      <img class="logo-cc mt-5" src="../assets/images/logo-cc.svg" alt="Centro capital">
    </div>
    <div class="col-12 d-flex mid-row py-5 container-line">
      <div class="line-middle"></div>
      <div class="col-6 py-5 d-flex justify-content-center"><h2 class="cities"><a href="#">Morelia</a></h2></div>
      <div class="col-6 py-5 d-flex justify-content-center"><h2 class="cities"><a href="#">Querétaro</a></h2></div>
    </div>
    <div class="col-12 d-flex justify-content-center icon-row">
      <div class="d-flex justify-content-around col-12 col-sm-10 col-md-6 col-lg-3">
        <a href="#" target="_blank">
          <img class="icon-face" src="../assets/images/facebook.svg" alt="Facebook Centro capital">
        </a>
        <a href="#" target="_blank">
          <img class="icon-instagram" src="../assets/images/instagram.svg" alt="instagram Centro capital">
        </a>
        <a href="#" target="_blank">
          <img class="icon-linkedin" src="../assets/images/linkedin.svg" alt="linkedin Centro capital">
        </a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="scss">
  .home {
    background-image: url("../assets/images/bg-cc.jpg");
    background-size: cover;
    background-position: center;
    width: 100%;
    height: 100vh;
  }
  .logo-cc{
    width: 150px;
    height: 70px;
  }

  .cities{
    a{
      color: #F9FCFC;
      &:hover{
        text-transform: none;
        text-decoration: none;
      }
    }
  }
  .container-line {
    position: relative;
    top: 50%;
    transform: translateY(-130%);
    .line-middle {
      position: absolute;
      height: 100%;
      width: 1px;
      left: 50%;
      top: 0;
      background-color: white;
    }
  }

  .icon-face{
    width: 13px;
    height: 24px;
  }
  .icon-instagram{
    width: 24px;
    height: 24px;
  }
  .icon-linkedin{
    width: 25px;
    height: 25px;
  }

  .icon-row{
    position: absolute;
    bottom: 10%;
  }
</style>
