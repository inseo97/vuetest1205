<template>
  <div class="flex flex-col min-h-screen">
    <TestHeader />
    <main class="flex-grow">
      <TestMain />
    </main>
    <TestFooter />
  </div>
</template>

<script>
import TestHeader from './components/TestHeader.vue';
import TestMain from './components/TestMain.vue';
import TestFooter from './components/TestFooter.vue';

export default {
  components: {
    TestHeader,
    TestMain,
    TestFooter,
  },
};
</script>

<style>
/* Global styles */
* {
  margin: 0;
  padding: 0;
  outline: 0;
  border: 0;
  box-sizing: border-box;
}
html, body{
  width: 100%;
  overflow-x: hidden;
  background-color: #eeeeee;
  box-sizing: border-box;
}
ul, li {
  list-style: none;
}
a {
  text-decoration: none;
}
</style>
