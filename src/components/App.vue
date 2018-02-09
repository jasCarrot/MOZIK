<template>
    <div id="box">
        <top></top>
    </div>
</template>

<script>
    import top from './top/top.vue'

    export default{
        name: '',
        data(){
            return{

            }
        },
        components: {
            top,
        }
    }
</script>

<style>
    *{
        margin: 0;
        padding: 0;
    }
    html,body,div{
        height: 100%;
    }
</style>
