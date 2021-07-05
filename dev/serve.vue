<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { CalendarVueSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  CalendarVueSample,
  // }
});
</script>

<template>
  <div id="app">
    <calendar-vue-sample />
  </div>
</template>
