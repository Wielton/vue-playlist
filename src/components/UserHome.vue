<template>
    <div>
        <img src="https://images.immediate.co.uk/production/volatile/sites/4/2018/07/iStock_000018226211_Large-6d7599f.jpg?quality=90&resize=940,400" alt="">
        <h1>My Music Playlist Creator</h1>
        <div id="gridContainer">
            <SongList/>
            <PlayList/>
        </div>
    </div>
</template>

<script>
import PlayList from './PlayList.vue'

import SongList from './SongList.vue'



    export default {
  components: { SongList, PlayList },
        name: 'UserHome',
        
    }
</script>

<style scoped>
#gridContainer{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
img {
    height: 200px;
    width: auto;
}
</style>