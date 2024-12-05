<template>
    <section>
      <ImageSlider />
      <div class="imgcard-wrap">
        <ImageCard/>
      </div>
      <div class="slidecard-wrap">
        <SlideCard/>
      </div>
    </section>
</template>
  
  <script>
  import ImageSlider from './ImageSlider.vue';
  import ImageCard from './ImageCard.vue';
  import SlideCard from './SlideCard.vue';
  
  export default {
    components: {
      ImageSlider,
      ImageCard,
      SlideCard,
    },
  };
  </script>
<style scoped>
section {
    padding-top: 60px;
}
.imgcard-wrap {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    gap: 20px;
    padding: 50px 10%;
    background-color: #ffffff;
}
.slidecard-wrap {
    width: 100%;
    padding: 50px 10%;
}
</style>
  