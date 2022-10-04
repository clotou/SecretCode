<template>
  <div id="app">
  <router-view />
  </div>
  <!-- <CodeInput/> -->
</template>

<script>
import CodeInput from './components/CodeInput.vue';
import WinPage from './components/WinPage.vue';

// export default {
//   name: "App",
//   data() {
//     return {
//     };
//   },
//   components: { CodeInput, winPage }
// }

export default {
  name: 'App',
  components: {
    CodeInput,
    WinPage
  }
}
</script>
