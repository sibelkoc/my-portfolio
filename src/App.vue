<template>
  <Web v-if="isWeb"></Web>
  <Mobile v-else></Mobile>
</template>

<script>
import Mobile from './components/Mobile.vue'
import Web from './components/Web.vue'
import { onMounted, ref } from 'vue'


export default {
  name: 'App',
  components: {
    Mobile,
    Web
  },
   setup () {
    const isWeb = ref(false);
    onMounted(() => {
      window.addEventListener('resize', onresize);
      onresize();

    })
 function onresize() {
     if(document.body.clientWidth > 800) isWeb.value=true;
     else isWeb.value = false;
    }

    return {
   isWeb
    }
  }
}
</script>

<style>
html{
  background-color: #c7ad9e3f;
}
#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #94745B;
  margin-top: 20px;
  display: flex;
  flex-direction: row;
  /* overflow: hidden; */
    scroll-behavior: smooth;

}

@font-face {
  font-family: "made_tommy";
  src: local("made_tommy"),
   url(./font/made_tommy/MADE_TOMMY_Regular_PERSONAL_USE.otf) format("truetype");
}
</style>
