<template>
  <v-footer id="footer" color="toolbars" padless dark height="auto">
    <svg class="footer-svg" viewBox="0 0 120 28">
      <defs>
        <path
          id="wave"
          d="M 0,10 C 30,10 30,15 60,15 90,15 90,10 120,10 150,10 150,15 180,15 210,15 210,10 240,10 v 28 h -240 z"
        />
      </defs>
      <use id="wave3" class="wave" xlink:href="#wave" x="0" y="-2" />
      <use id="wave2" class="wave" xlink:href="#wave" x="0" y="0" />
      <use id="wave1" class="wave" xlink:href="#wave" x="0" y="1" />
    </svg>
  </v-footer>
</template>

<script>
export default {
  name: 'AppFooter',

  data() {
    return {
      showInfoReference: false,
    }
  },
  methods: {},
}
</script>

<style>
.footer-content {
  margin: calc(-5%) 0 0 0;
  background-color: #2196f3 !important;
  padding: 0;
}
.footer-svg {
  width: 100%;
}
.wave {
  animation: wave 3s linear;
  animation-iteration-count: infinite;
  fill: #2196f3;
}
#wave2 {
  animation-duration: 5s;
  animation-direction: reverse;
  opacity: 0.6;
}
#wave3 {
  animation-duration: 7s;
  opacity: 0.3;
}
@keyframes wave {
  to {
    transform: translateX(-100%);
  }
}
</style>
