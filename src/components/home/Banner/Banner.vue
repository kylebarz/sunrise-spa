<script src="./Banner.js"></script>

<template>
  <div class="slider-area">
    <carousel
      animateIn="fadeIn"
      animateOut="fadeOut"
      :autoplayHoverPause="false"
      :nav="false"
      :autoplay="true"
      :items="1"
      class="slider-active-1 nav-style-2"
    >
      <div
        class="single-slider bg-img slider-height-2 align-items-center custom-d-flex"
        style="background-image:url(assets/img/banner3.jpg);"
      >
        <div class="container">
          <div class="row height-100-percent align-items-center">
            <div class="col-lg-12 col-md-12 col-sm-12 col-12">
              <div class="slider-content-8 slider-animated-1 text-center">
                <h3 class="animated">MID-SEASON SALE</h3>
                <h1 class="animated">UP TO 50%</h1>
                <div class="slider-btn-1">
                  <router-link
                    :to="{ name: 'products', params: { categorySlug: 'sale' } }"
                    class="animated"
                    >SHOP NOW</router-link
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="single-slider bg-img slider-height-2 align-items-center custom-d-flex"
        style="background-image:url(assets/img/banner8.jpg);"
      >
        <div class="container">
          <div class="row height-100-percent align-items-center">
            <div class="col-lg-12 col-md-12 col-sm-12 col-12">
              <div class="slider-content-9 slider-animated-1">
                <h1 class="animated"><span>CHECK OUT </span> NEW COLLECTION</h1>
                <div class="slider-btn-1 text-center">
                  <router-link
                    :to="{ name: 'products', params: { categorySlug: 'new' } }"
                    class="animated"
                    >SHOP NOW</router-link
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </carousel>
  </div>
</template>
