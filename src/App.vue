<template>
  <div id="app">
    <div id="canvas-container">
      <ProgressPrideNetwork />
    </div>
    <div id="heading-container">
      <div>
        <h1>
          <!-- <Typewriter /> -->
          COMING 2021
        </h1>
        <h4>Just you wait.</h4>
      </div>
    </div>
    <div id="footer-container">
      <a href="https://www.instagram.com/thisisturnup/" target="_blank"
        ><i class="fab fa-instagram fa-2x"></i
      ></a>
      <a href="https://twitter.com/thisisturnup" target="_blank"
        ><i class="fab fa-twitter fa-2x"></i
      ></a>
    </div>
  </div>
</template>

<script>
// Import components
import ProgressPrideNetwork from "./components/ProgressPrideNetwork/ProgressPrideNetwork.vue";
// import Typewriter from "./components/Typewriter/Typewriter.vue";
import "@fortawesome/fontawesome-free/css/all.css";
import "@fortawesome/fontawesome-free/js/all.js";

// Import styles
import "./index.scss";

export default {
  name: "#ThisIsTurnUp",
  components: {
    ProgressPrideNetwork,
    // Typewriter,
  },
  title: "#ThisIsTurnUp",
};
</script>
