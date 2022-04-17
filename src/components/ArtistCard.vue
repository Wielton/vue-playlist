<template>
    <div>
        <img :src="image">
        
        <h3>{{ this.artist }}</h3>
        <hr>
        <h2>{{ this.trackTitle }}</h2>
        <button>Add</button>
    </div>
</template>

<script>
    export default {
        name: 'ArtistCard',
        props: {
            artist: String,
            trackTitle: String,
            image: Image
        }
    }
</script>

<style scoped>
    div {
        box-sizing: border-box;
        border: none;
        box-shadow: 1px 2px 2px #383838;
        
    }
    img {
        height: 100px;
        width: 100px;
        display: flex;
        float: left;
    }
</style>