<template>
  <div id="app">
    <slide-bar />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import SlideBar from '@/components/layout/SlideBar.vue';
export default defineComponent({
  name: 'App',
  components: {
    SlideBar
  }
});
</script>
