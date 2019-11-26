<template>
  <div class="wrap">
    <Nav />
    <router-view/>
    <Footer />
  </div>
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Footer from '@/components/Footer.vue';
import Nav from '@/components/Nav.vue';

@Component({
  components: {
    Footer,
    Nav
  }
})
export default class App extends Vue {

}
</script>
<style lang="scss">
@import './assets/css/style.scss';
@import './assets/css/animate.scss';
@import './assets/css/carousel.scss';

</style>
