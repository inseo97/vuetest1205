<template>
    <footer class="">
        <LogoImage/>
        <!-- <img class="f-logo" src="../assets/logo.svg" width="120" alt="f로고"> -->
        <p>Copyright © 2024. 테스트 All Rights Reserved</p>
    </footer>
</template>
<script>
import LogoImage from './LogoImage.vue'
export default {
  components: {
    LogoImage,
  },
};
</script>
<style>
footer {
    width: 100%;
    height: 240px;
    padding: 60px 10%;
    background-color: #1a1a1a;
    color: #ffffff;
}
footer svg {
    width: 120px;
    margin-bottom: 20px;
}
footer svg .cls-1{fill:#ffffff;}
footer svg .cls-2{fill:#ffffff;}
</style>