<template>
    <nav class="navbar navbar-expand-lg navbar-style navbar-background">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="../img/logos.png" width="140" height="51" alt="">
        </a>
      <button class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon">
          <i class="fa fa-bars"></i>
        </span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">KONSEPT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">YAŞAM</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">GALERİ</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">İLETİŞİM</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">360° SANAL TUR</a>
          </li>
          <li class="nav-item" style="display: flex">
            <i style="line-height: 2.5; margin-right: 10px; color: #df952c"
               class="fa fa-video-camera">
            </i>
            <a class="nav-link" href="#">Canlı Yayın</a>
          </li>
          <ul class="language">
            <li class="language-item">TR</li>
            <li>|</li>
            <li class="language-item">EN</li>
          </ul>
        </ul>
      </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" src="./Header.scss">
</style>
