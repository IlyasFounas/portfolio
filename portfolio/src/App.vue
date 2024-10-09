<script setup>
import { ref } from 'vue';
import Infos from './components/Infos.vue';

const cursorBg = ref(null);

document.addEventListener('pointermove', (e) => {
  if (cursorBg.value) {
    cursorBg.value.style.display = 'block';

    const cursorSize = 120;
    cursorBg.value.animate({
      top: e.pageY - cursorSize / 2 + 'px',
      left: e.pageX - cursorSize / 2 + 'px',
    }, {
      duration: 1,
      fill: 'forwards'
    });
  }
});

</script>

<template>
    <div id="cursor-bg" ref="cursorBg" class="cursor-bg"></div>
    <Infos />
</template>

<style scoped>

#cursor-bg {
	display: none;
	position: absolute;
	width: 120px;
	height: 120px;
	background: #45B0DF;
	border-radius: 50%;
	filter: blur(100px);
  pointer-events: none;
  z-index: 9999;
}

</style>
