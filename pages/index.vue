<template>
  <div>
    <header class="content">
      <VuesaxLogo />
    </header>
    <H1 class="textContent">
      Vuesax
    </H1>
    <H2 class="textContent">
      TypeScript
    </H2>
    <div class="content">
      <defaultBtn>
        Sample
      </defaultBtn>
    </div>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "nuxt-property-decorator";

@Component({
  components: {
    VuesaxLogo: () => import("~/components/VuesaxLogo.vue"),
    H1: () => import("~/components/atoms/H1.vue"),
    H2: () => import("~/components/atoms/H2.vue"),
    defaultBtn: () => import("~/components/atoms/defaultBtn.vue")
  }
})
export default class Index extends Vue {}
</script>

<style>
.content {
  display: flex;
  align-items: center;
  justify-content: center;
}
.textContent {
  text-align: center;
}
</style>
