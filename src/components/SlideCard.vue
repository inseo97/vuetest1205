<template>
  <swiper
    :slidesPerView="3"
    :spaceBetween="30"
    :pagination="{
      clickable: true,
    }"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide>
      <img src="../assets/img1.jpg" alt="" class="slide-card-img-01">
      <div class="slide-card-textbox">
          <h3 class="slide-card-title">Lorem Ipsum</h3>
          <p class="slide-card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <p class="slide-card-date">
            2024-12-05 19:00
          </p>
      </div>
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/img2.jpg" alt="" class="slide-card-img-02">
      <div class="slide-card-textbox">
          <h3 class="slide-card-title">Lorem Ipsum</h3>
          <p class="slide-card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <p class="slide-card-date">
            2024-12-05 19:00
          </p>
      </div>
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/img3.jpg" alt="" class="slide-card-img-03">
      <div class="slide-card-textbox">
          <h3 class="slide-card-title">Lorem Ipsum</h3>
          <p class="slide-card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <p class="slide-card-date">
            2024-12-05 19:00
          </p>
      </div>
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/img4.jpg" alt="" class="slide-card-img-04">
      <div class="slide-card-textbox">
          <h3 class="slide-card-title">Lorem Ipsum</h3>
          <p class="slide-card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <p class="slide-card-date">
            2024-12-05 19:00
          </p>
      </div>
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/img1.jpg" alt="" class="slide-card-img-01">
      <div class="slide-card-textbox">
          <h3 class="slide-card-title">Lorem Ipsum</h3>
          <p class="slide-card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <p class="slide-card-date">
            2024-12-05 19:00
          </p>
      </div>
    </swiper-slide>
  </swiper>
</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';
  import 'swiper/css';
  import 'swiper/css/pagination';
  import { Pagination } from 'swiper/modules';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination],
      };
    },
  };
</script>
<style scoped>

.swiper-slide {
  background-color: #ffffff;
  height: auto;
  max-height: 450px;
}
.swiper-slide img {
  width: 100%;
}
.slide-card-textbox {
    color: #000000;
    padding: 10px;
}
.slide-card-title {
    font-size: 1.2rem;
    margin-bottom: 4px;
}
.slide-card-sub {
    font-size: 0.8rem;
    margin-bottom: 16px;
}
.slide-card-date {
  font-size: 0.8rem;
  color: #949494;
}
.swiper-slide img {
    filter: brightness(1);
}
</style>