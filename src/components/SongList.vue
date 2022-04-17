<template>
    <div>
        <h2>Songs</h2>
        <button>Add</button>
        <ArtistCard 
        v-for="artist in artists"
        :key="artist.artist"
        v-bind="artist"
        />
    </div>
</template>

<script>
import ArtistCard from './ArtistCard.vue'

export default {
        components: { ArtistCard },
        name: 'SongList',
        data(){
            return {
                artists : [
                    {
                        artist: "Lord Finesse",
                        trackTitle: "Keep The Crowd Listening",
                        image: "https://i.discogs.com/57Ov4Sk-PFI7yOD41jPaqTNaXQeutFdlfx2qqWEcQbo/rs:fit/g:sm/q:90/h:594/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEyNzQx/MzEtMTMzMjE3MzUw/MS5qcGVn.jpeg",
                    },
                    {
                        artist: "KRS-ONE",
                        trackTitle: "Mc's Act Like They Don't Know",
                        image: "https://i.discogs.com/qIWbKvevdgtrYWJx4WnBj9TvnLhXGF81wpmSB0gwtjE/rs:fit/g:sm/q:90/h:582/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTIzNDQy/Ni0xNDcwNzUxMTMw/LTk2MzIuanBlZw.jpeg",
                    },
                    {
                        artist: "A Tribe Called Quest",
                        trackTitle: "Scenario",
                        image: "https://i.discogs.com/JmtsWYPPK-n9SACBvJ5AhF423r1Uqgs20k-qSfoT_kc/rs:fit/g:sm/q:90/h:483/w:500/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTMxNTc2/NzYtMTMxODQwNDEw/MS5qcGVn.jpeg",
                    },
                    {
                        artist: "Wu-Tang Clan",
                        trackTitle: "Protect Ya Neck",
                        image: "https://i.discogs.com/IM2kiXls9SQjBAigcQlOJzmiA1zuWrKLYaLxr23rpEU/rs:fit/g:sm/q:90/h:596/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTgxNTQ2/NzItMTY0NDUzMTMy/OS04NDI3LmpwZWc.jpeg",
                    },
                    {
                        artist: "GangStarr",
                        trackTitle: "Who's Gonna Take The Weight",
                        image: "https://i.discogs.com/QTQFxdv4iV64TiDIj1lzNighOqU2yfm78FT5gFoMczA/rs:fit/g:sm/q:40/h:300/w:300/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTMxNDY4/Ni0xNDY3MTE4MzQy/LTcyOTcuanBlZw.jpeg",
                    },
                    {
                        artist: "Diamond D",
                        trackTitle: "Best Kept Secret",
                        image: "https://i.discogs.com/GPdx-wuGgrRlE9KJiTlt0waNW5R_-1byhvtU5Uzgxzs/rs:fit/g:sm/q:40/h:300/w:300/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTY5MTA1/NS0xMTQ4MjE2MzIz/LmpwZWc.jpeg",
                    },
                    {
                        artist: "BlackMoon",
                        trackTitle: "How Many Mc's...",
                        image: "https://i.discogs.com/N-Q7j67BLsrRyGw1vI3WDI1m-NrAz82CCSuzRxgvK6w/rs:fit/g:sm/q:90/h:585/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEyNjEw/NjUtMTM0NTc1MjAy/MC0zNDAxLmpwZWc.jpeg",
                    },
                    {
                        artist: "The Legion",
                        trackTitle: "Jingle Jangle",
                        image: "https://i.discogs.com/Nj5I7_74M6-q_R_2auzKgDa1KnBXnUzQnlrwS3NArCM/rs:fit/g:sm/q:90/h:379/w:375/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTc4NDEy/MS0xMjkxOTk4Mjgy/LmpwZWc.jpeg",
                    },
                    {
                        artist: "Heather B",
                        trackTitle: "Sendin' Em Back",
                        image: "https://i.discogs.com/qEAL_X8dBhLdVfsVfPhrZlVjQnUSQMNk7Y1CKKKasK0/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQxODU3/MC0xNDU4NTI0ODEy/LTU0NzkuanBlZw.jpeg",
                    },
                    {
                        artist: "Ed O.G. & Da Bulldogs",
                        trackTitle: "Skinny Dip (Got It Goin' Down)",
                        image: "https://i.discogs.com/AXq7W48tJ8jdvudcYc2YuldGeldZIqpfK0_XwsTG6xg/rs:fit/g:sm/q:90/h:591/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTUxMzA3/OS0xNDc2MTk0NjE4/LTQ5MTYuanBlZw.jpeg",
                    },
                ]
            }
            
        }
        
}        
        
    
</script>

<style scoped>
    div{
        box-sizing: border-box;
        height: 200px;
        width: 400px;
    }
</style>