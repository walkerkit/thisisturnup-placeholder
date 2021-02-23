<template>
  <div id="app">
    <div id="canvas-container">
      <ProgressPrideNetwork />
    </div>
    <div id="heading-container">
      <div>
        <h1>
          <Typewriter />
        </h1>
      </div>
    </div>
  </div>
</template>

<script>
// Import components
import ProgressPrideNetwork from "./components/ProgressPrideNetwork/ProgressPrideNetwork.vue";
import Typewriter from "./components/Typewriter/Typewriter.vue";
// Import styles
import "./index.scss";

export default {
  name: "App",
  components: {
    ProgressPrideNetwork,
    Typewriter,
  },
};
</script>
