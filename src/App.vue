<template>
  <div id="app">
    <hex-tile></hex-tile>
    <hex-tile></hex-tile>
    <hex-tile></hex-tile>
  </div>
</template>

<script>
import HexTile from './components/HexTile.vue'

export default {
  name: 'app',
  components: {
    HexTile
  }
}
</script>

<style>
</style>
