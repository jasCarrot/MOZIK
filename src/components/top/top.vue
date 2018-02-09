<template>
    <div class="nav-wrapper">
        <div class="icon-1">
            <div class="icon-smile"></div>
        </div>

    </div>
</template>

<script>
    export default{
        name:'top',

    }
</script>

<style>
    .nav-wrapper {
        position: absolute;
        display: flex;
        right: 0;
        top: 0;
        height: 50%;
        width: 17%;
        /*background-color: black;*/
    }
    .icon-1{
        position: relative;
        width: 40px;
        height: 40px;
        margin: 7px;
        clear: both;
        font-size: 40px;
    }
    .icon-smile:before {
        content: "\e9e1";
    }
</style>