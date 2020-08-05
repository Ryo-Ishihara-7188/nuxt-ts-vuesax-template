<template>
  <h2>
    <slot></slot>
  </h2>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class H2 extends Vue {}
</script>

<style scoped>
h2 {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 2.5em;
  color: #35495e;
  letter-spacing: 1px;
  text-transform: capitalize;
}
</style>
