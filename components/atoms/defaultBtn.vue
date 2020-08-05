<template>
  <vs-button color="rgb(35, 120, 173)" border size="large">
    <slot></slot>
  </vs-button>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class defaultBtn extends Vue {}
</script>
