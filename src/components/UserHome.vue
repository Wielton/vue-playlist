<template>
    <div>
        <img src="https://images.immediate.co.uk/production/volatile/sites/4/2018/07/iStock_000018226211_Large-6d7599f.jpg?quality=90&resize=940,400" alt="">
        <h1>My Music Playlist Creator</h1>
        <div>
            <input type="text" name="username" id="" placeholder="Enter username...">
            <BasicButton/>
        </div>
    </div>
    
</template>

<script>
import BasicButton from '@/components/BasicButton.vue';
    export default {
        name: 'UserHome',
        components: { BasicButton }
    }
</script>

<style scoped>

</style>