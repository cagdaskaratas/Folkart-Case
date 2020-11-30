<template>
  <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
      <img class="d-block w-100 img-height" src="../img/slider.jpg" alt="First slide">
      <div class="carousel-form">
        <div class="col form-title">
          <div>SİZE ÖZEL AVANTAJLAR İÇİN</div>
          <h3>BİZE ULAŞIN</h3>
        </div>
        <form>
          <div class="col input-area">
            <input type="text" class="form-control" placeholder="İSİM SOYİSİM">
          </div>
          <div class="col input-area">
            <input type="number" class="form-control" placeholder="+90">
          </div>
          <div class="col input-area">
            <input type="email"
                   class="form-control"
                   id="exampleFormControlInput1"
                   placeholder="name@example.com"
            >
          </div>
          <div class="col input-area">
              <textarea
                class="form-control"
                id="exampleFormControlTextarea1"
                rows="3"
                placeholder="MESAJINIZ"
              >
              </textarea>
          </div>
            <div class="form-check form-checkbox d-flex">
              <input class="form-check-input position-static"
                     type="checkbox"
                     id="blankCheckbox"
                     value="option1"
                     aria-label="..."
              >
              <label for="">Email, sms, telefon yolu
                ile bilgilendirilmek istiyorum.</label>
              <button class="form-button" href="">GÖNDER</button>
            </div>
        </form>
      </div>
      <div class="carousel-text-area">
        <div>FOLKART VEGA'DA</div>
        <div>KAÇIRILMAYACAK</div>
        <div>FIRSATLAR</div>
      </div>
      <div class="icon-scroll"></div>
    </div>
  </div>
</template>
<script></script>
<style lang="scss" src="./Carousel.scss">
</style>
