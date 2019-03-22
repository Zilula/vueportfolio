<template>
<div id="base">
<div class="background-image"></div>
  <div id="app">
    <Wrapper/>
  </div>
</div>
</template>

<script>
import Wrapper from './components/Wrapper.vue';

export default {
    name: 'app',
    components: {
        Wrapper
    }
};
</script>

<style>
body, html {
  height: 100%;
}
@-webkit-keyframes fadein { /* Safari and Chrome */
    from {
        opacity:0;
    }
    to {
        opacity:1;
    }
}
#app {
  margin: .5em;
  padding-top: 1em;
  padding-bottom: 1em;
  animation: fadein 2s;

}
.background-image {
  margin: 0;
  background-image: url('./assets/background.jpg');
  background-size: cover;
  display: block;
  filter: blur(3px);
  -webkit-filter: blur(3px);
  height: 105vh;
  width: 105vw;
  top: -.5em;
  left: -5px;
  position: fixed;
  right: 0;
  z-index: -1;
}
</style>
