<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HeaderComponent msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeaderComponent from "@/components/HeaderComponent.vue";

@Options({
  components: {
    HeaderComponent,
  },
})
export default class TestView extends Vue {}
</script>
