<template>
    <!-- Partner Logo Section Begin -->
    <div class="partner-logo">
        <div class="container">
            <Swiper 
            :modules="modules"
            :autoplay="true"  
            :slides-per-view="5"
            class="logo-carousel owl-carousel">
                <SwiperSlide>
                    <div class="logo-item">
                        <div class="tablecell-inner">
                            <img src="/img/logo-carousel/logo-1.png" alt="" />
                        </div>
                    </div>
                </SwiperSlide>
                <SwiperSlide>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="/img/logo-carousel/logo-2.png" alt="" />
                    </div>
                </div>
                </SwiperSlide>
                <SwiperSlide>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="/img/logo-carousel/logo-3.png" alt="" />
                    </div>
                </div>
                </SwiperSlide>
                <SwiperSlide>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="/img/logo-carousel/logo-4.png" alt="" />
                    </div>
                </div>
                </SwiperSlide>
                <SwiperSlide>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="/img/logo-carousel/logo-5.png" alt="" />
                    </div>
                </div>
                </SwiperSlide>
            </Swiper>
        </div>
    </div>
    <!-- Partner Logo Section End -->
</template>

<script>
    import { Swiper, SwiperSlide } from 'swiper/vue';
    import { Autoplay } from 'swiper';
    import 'swiper/css';

    export default{
        components: {
            Swiper,
            SwiperSlide,
        },
        setup(){
            return{
                modules: [Autoplay]
            }
        }
    }
</script>