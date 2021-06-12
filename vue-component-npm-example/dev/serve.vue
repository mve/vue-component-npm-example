<script>
import { defineComponent } from 'vue';
import VueComponentNpmExample from '@/vue-component-npm-example.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    VueComponentNpmExample
  }
});
</script>

<template>
  <div id="app">
    <vue-component-npm-example text="Example button" />
  </div>
</template>
