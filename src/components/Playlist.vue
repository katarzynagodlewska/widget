<template>
    <div class="playlist">
        <header class="playlist__header">
            <nav class="playlist__nav">
                <button class="playlist__button-back">
                    <img class="playlist__arrow" src="../assets/arrow1.svg">
                </button>
            </nav>
            <h1 class="playlist__title">Playlist</h1>
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