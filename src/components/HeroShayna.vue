<template> 
    <!-- Hero Section Begin -->
    <section class="hero-section">
      <swiper
        :modules="modules"
        :slides-per-view="1"
        :pagination="{ clickable: true }"
        class="hero-items owl-carousel"
      >
        <swiper-slide>
          <div class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')" data-setbg="img/hero-1.jpg">
              <div class="container">
                  <div class="row">
                      <div class="col-lg-5">
                          <span>Bag,kids</span>
                          <h1>Black friday</h1>
                          <p>
                              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                          </p>
                          <a href="#" class="primary-btn">Shop Now</a>
                      </div>
                  </div>
              </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="single-hero-items set-bg" style="background-image: url('/img/hero-2.jpg')" data-setbg="img/hero-1.jpg">
              <div class="container">
                  <div class="row">
                      <div class="col-lg-5">
                          <span>Bag,kids</span>
                          <h1>Black friday</h1>
                          <p>
                              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                          </p>
                          <a href="#" class="primary-btn">Shop Now</a>
                      </div>
                  </div>
              </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="single-hero-items set-bg" style="background-image: url('/img/hero-3.jpg')" data-setbg="img/hero-1.jpg">
              <div class="container">
                  <div class="row">
                      <div class="col-lg-5">
                          <span>Bag,kids</span>
                          <h1>Black friday</h1>
                          <p>
                              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                          </p>
                          <a href="#" class="primary-btn">Shop Now</a>
                      </div>
                  </div>
              </div>
          </div>
        </swiper-slide>
      </swiper>
    </section>
    <!-- Hero Section End -->
</template>

<script>
    import { Swiper, SwiperSlide } from 'swiper/vue';
    import { Pagination } from 'swiper';

    // Import Swiper styles
    import 'swiper/css';
    import 'swiper/css/pagination';

    export default{
        components: {
            Swiper,
            SwiperSlide,
        },
        setup() {
            return {
            modules: [Pagination]
            };
        },
    }
</script>