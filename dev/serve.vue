<script>
import Vue from 'vue';
import VueHacktivFooter from '@/vue-hacktiv-footer.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueHacktivFooter
  }
});
</script>

<template>
  <div id="app">
    <vue-hacktiv-footer />
  </div>
</template>
