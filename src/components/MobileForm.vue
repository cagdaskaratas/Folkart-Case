<template>
  <div class="mobile-form-show">
    <div class="mobile-form-title">
      <p>ŞEHRİN EN PARLAK YILDIZI</p>
    </div>
    <div class="carousel-form-mobile">
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
        <div class="form-check form-mobile-checkbox d-flex">
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
  </div>
</template>
<script></script>
<style lang="scss" src="./MobileForm.scss">
</style>
