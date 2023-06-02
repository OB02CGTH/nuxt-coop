<template></template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  methods: {
    to_main() {
      this.$router.push("/standard_table");
    },
  },
  mounted() {
    this.to_main();
  },
});
</script>
