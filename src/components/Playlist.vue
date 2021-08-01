<template>
    <div>
        <header>
            Playlist
        </header>
        <nav>
            <img src="../assets/arrow1.svg">
        </nav>
        <ul>
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

</style>