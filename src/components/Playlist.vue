<template>
    <div class="playlist">
        <header class="playlist__header">
            <nav class="playlist__nav">
            <img class="playlist__arrow" src="../assets/arrow1.svg">
            </nav>
            <h2 class="playlist__title">Playlist</h2>
        </header>
        <ul class="list">
            <PlaylistItem/>
            <PlaylistItem/>
            <PlaylistItem/>
            <PlaylistItem/>
            <PlaylistItem/>
        </ul>
    </div>
</template>

<script>
import PlaylistItem from './PlaylistItem.vue'
export default {
    name: 'Playlist',
  components: {
    PlaylistItem
  }
}
</script>

<style lang="scss" scoped>
@import "../styles/modules/playlist.scss"
</style>