<template>
  <div id="app">
    <div id="grid">
      <div class="row" v-for="i in 5" :key="i">
        <hex-tile></hex-tile>
      </div>
    </div>
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
