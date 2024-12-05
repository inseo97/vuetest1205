<template>
  <header>
    <div class="h-wrap">
      <h1>
        <img src="../assets/logo.svg" alt="">
      </h1>
      <nav>
        <ul class="h-nav">
          <li><a href="#" @click.prevent="showMessage('Home')" class="hover:underline">Home</a></li>
          <li><a href="#" @click.prevent="showMessage('About')" class="hover:underline">About</a></li>
          <li><a href="#" @click.prevent="showMessage('Contact')" class="hover:underline">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'TestHeader',
  methods: {
    showMessage(page) {
      console.log(`${page} 클릭`);
    },
  },
};
</script>
<style scoped>
  header {
    width: 100%;
    height: 60px;
    padding: 0 5%;
    position: fixed;
    top: 0;
    z-index: 9999;
    background-color: #ffffff;
  }
  .h-wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .h-nav li {
    float: left;
  }
  .h-nav li:not(:last-child) {
    margin-right: 10px;
  }
  .h-nav li a {
    color: black;
  }
  h1 img {
    width: 120px;
  }
</style>