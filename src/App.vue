<template>
<div>
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
#app {

}
.background-image {
  margin: 0;
  background-image: url('./assets/background.jpg');
  background-size: cover;
  display: block;
  filter: blur(3px);
  -webkit-filter: blur(3px);
  height: 800px;
  left: 0;
  position: fixed;
  right: 0;
  z-index: -1;
}
</style>
