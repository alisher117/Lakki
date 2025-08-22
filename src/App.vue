<template>
  <div id="app">
    <div class="container">
      <Header />
      <Sector1 />
      <Sector2 />
      <Sector4 />
      <Sector3 />
      <Footer />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Sector1 from './views/sector1.vue';
import Sector2 from './views/sector2.vue';
import Sector3 from './views/sector3.vue';
import Sector4 from './views/sector4.vue';
import "@/assets/main.css";

export default {
  name: 'App',
  components: {
    Header,
    Sector1,
    Sector2,
    Sector4,
    Sector3,
    Footer
  }
};
</script>
