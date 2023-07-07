<template>
  <div id="app">
    <Navbar />
    <Hero />
    <Work />
    <about />
    <skills />
    <sakhile />
    <wireframe />
    <VueCursor scaleElement="logo" dotColor="#185e7d" :borderColor="'#03a9f4'" />
    <Footer />



  </div>
</template>

<script>
import VueCursor from "../components/VueCursor.vue";
export default {
  components: {
    VueCursor
  }
};
</script>