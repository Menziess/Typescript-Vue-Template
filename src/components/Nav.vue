<!-- src/components/Navbar.vue -->

<template>
  <div>
    <nav>
      <ul>
        <li>Link 1</li>
      </ul>
    </nav>
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "vue-property-decorator";

@Component({
  name: "Navbar"
})
export default class Nav extends Vue {}
</script>

<style>

</style>
