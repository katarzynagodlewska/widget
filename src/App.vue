<template>
  <main class="main">
      <Playlist/>
  </main>
</template>

<script>
import Playlist from './components/Playlist.vue'
export default {
  name: 'App',
  components: {
    Playlist
  }
}
</script>

<style lang="scss">
@import "styles/main.scss";
</style>
