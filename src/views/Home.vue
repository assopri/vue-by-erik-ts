<template>
  <div class="home">
    <Counter msg="Welcome to Your Vue.js"/>
  </div>
</template>

<script lang="ts">
import Counter from "@/components/Counter.vue"

export default {
  name: 'Home',
  components: {
    Counter,
  },
};
</script>
