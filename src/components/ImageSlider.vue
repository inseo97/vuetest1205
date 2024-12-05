<template>
    <swiper
        :cssMode="true"
        :slidesPerView="1"
        :spaceBetween="0"
        :loop="true"
        :pagination="{
        clickable: true,
        }"
        :navigation="true"
        :modules="modules"
        class="mySwiper"
        >
        <swiper-slide>
            <img src="../assets/main.jpg" alt="" class="roll-img-01">
            <div class="roll-textbox">
                <h3 class="roll-title">Lorem Ipsum</h3>
                <p class="roll-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </swiper-slide>
        <swiper-slide>
            <img src="../assets/main.jpg" alt="" class="roll-img-02">
            <div class="roll-textbox">
                <h3 class="roll-title">2222222</h3>
                <p class="roll-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </swiper-slide>
        <swiper-slide>
            <img src="../assets/main.jpg" alt="" class="roll-img-03">
            <div class="roll-textbox">
                <h3 class="roll-title">33333</h3>
                <p class="roll-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </swiper-slide>
        <swiper-slide>
            <img src="../assets/main.jpg" alt="" class="roll-img-04">
            <div class="roll-textbox">
                <h3 class="roll-title">4444444</h3>
                <p class="roll-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </swiper-slide>
    </swiper>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/navigation';
import { Navigation } from 'swiper/modules';

export default {
    components: {
    Swiper,
    SwiperSlide,
    },
    setup() {
    return {
        modules: [Navigation],
    };
    },
};
</script>
<style>
.swiper-slide {
    width: 100%;
    height: 450px;
    overflow: hidden;
    box-sizing: border-box;
    position: relative;
}
.swiper-slide img {
    filter: brightness(0.6);
}
.swiper-slide .roll-textbox {
    color: #ffffff;
    position: absolute;
    top: 100px;
    left: 10%;
}
.swiper-slide .roll-title {
    font-size: 2rem;
}
.swiper-slide .roll-sub {
    font-size: 1rem;
}
.swiper-button-prev, .swiper-button-next {
    color: #ffffff;
}
.swiper-button-prev, .swiper-rtl .swiper-button-next {
    left: var(--swiper-navigation-sides-offset, 50px);
}
.swiper-button-next, .swiper-rtl .swiper-button-prev {
    right: var(--swiper-navigation-sides-offset, 50px);
}
</style>