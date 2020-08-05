<template>
  <h1>
    <slot></slot>
  </h1>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class H1 extends Vue {}
</script>

<style scoped>
h1 {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 500;
  font-size: 4em;
  color: #35495e;
  letter-spacing: 1px;
  text-transform: capitalize;
}
</style>
