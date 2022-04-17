<template>
    <div>
        <h2>Playlist</h2>
        <ArtistCard/>
    </div>
</template>

<script>
import ArtistCard from './ArtistCard.vue'
    export default {
  components: { ArtistCard },
        name: 'PlayList',
        props: {

        }
    }
</script>

<style scoped>

</style>