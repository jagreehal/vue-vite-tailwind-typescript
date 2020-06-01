<template>
  <Counter />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Counter from "./components/Counter.vue";

export default defineComponent({
  components: {
    Counter,
  },
});
</script>
