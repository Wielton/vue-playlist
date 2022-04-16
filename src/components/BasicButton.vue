<template>
    <div>
        <button @click="performTask">{{ buttonFunction }}</button>
    </div>
</template>

<script>
    export default {
        name: 'BasicButton',
        props: {
            buttonFunction: {
                type: String,
                default: "Click"
            }
        },
        methods: {
            performTask(){
                this.$emit('buttonClicked');
            }
        }
    }
</script>

<style scoped>
    button {
        background-color: rgba(77, 77, 243, 0.87);
        color: #2c3e50;
        font-size: 1.5rem;
        border: none;
        border-radius: 25px;
        width: 100px;   
        height: 50px;
    }
</style>