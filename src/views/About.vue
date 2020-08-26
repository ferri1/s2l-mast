<template>
  <div class="about">
    <Pitch></Pitch>
    <h2>cette page contient des explications plus détaillées destinées aux investisseurs</h2>
   <Colaps></Colaps>
  
  </div>
</template>

<script>
// @ is an alias to /src
import Pitch from "@/components/Pitch.vue";
import Colaps from "@/components/Colaps.vue";

export default {
  name: "About",
  components: {
    Pitch, Colaps,
  }
};
</script>
