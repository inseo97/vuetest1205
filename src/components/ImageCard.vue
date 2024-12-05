<template>
  <div class="imgcard-item">
    <img src="../assets/img1.jpg" alt="" class="card-img-01">
    <div class="card-textbox">
        <h3 class="card-title">Lorem Ipsum</h3>
        <p class="card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p class="card-date">
          2024-12-05 19:00
        </p>
    </div>
  </div>
  <div class="imgcard-item">
    <img src="../assets/img2.jpg" alt="" class="card-img-02">
    <div class="card-textbox">
        <h3 class="card-title">Lorem Ipsum</h3>
        <p class="card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p class="card-date">
          2024-12-05 19:00
        </p>
    </div>
  </div>
  <div class="imgcard-item">
    <img src="../assets/img3.jpg" alt="" class="card-img-03">
    <div class="card-textbox">
        <h3 class="card-title">Lorem Ipsum</h3>
        <p class="card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p class="card-date">
          2024-12-05 19:00
        </p>
    </div>
  </div>
  <div class="imgcard-item">
    <img src="../assets/img4.jpg" alt="" class="card-img-04">
    <div class="card-textbox">
        <h3 class="card-title">Lorem Ipsum</h3>
        <p class="card-sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p class="card-date">
          2024-12-05 19:00
        </p>
    </div>
  </div>
  
</template>
<style scoped>
.imgcard-item {
    width: 240px;
    height: 350px;
    border-radius: 6px;
    overflow: hidden;
    box-sizing: border-box;
    position: relative;
    box-shadow: 2px 2px 5px #00000057;
}
.imgcard-item img {
  height: 160px;
}
.card-textbox {
    color: #000000;
    padding: 10px;
}
.card-title {
    font-size: 1.2rem;
    margin-bottom: 4px;
}
.card-sub {
    font-size: 0.8rem;
}
.card-date {
  font-size: 0.8rem;
  color: #949494;
  position: absolute;
  bottom: 10px;
  left: 10px;
}
</style>