new Typewriter('#typewriter', { strings: ['Hello', 'World'], autoStart: true,
});

<template>
  <h1 ref="text_box"></h1>
</template>

<script>
import Typewriter from "typewriter-effect/dist/core";

export default {
  name: "App",
  mounted() {
    new Typewriter(this.$refs.text_box, {
      strings: ["This is Turn Up!", "Coming June 2021."],
      autoStart: true,
      pauseFor: 1000,
      loop: true,
      delay: 80,
    });
  },
};
</script>
