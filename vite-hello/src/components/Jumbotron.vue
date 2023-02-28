<template>
    <div class="jumbotron">
    <img src="https://picsum.photos/1920/1080" alt="" >
    <div class="jumbotron-txt">
        <h2>Questo è il mio Jumbotron</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Necessitatibus voluptate magni atque temporibus tempore minus cumque architecto error corrupti mollitia.</p>
    </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
        }
    },
}
</script>

<style>
    .jumbotron{
        margin: 0 auto;
        position: relative;
    }
    .jumbotron-txt{
        border-radius: 50px;
        opacity: 0.5;
        background-color: blue;
        border:1px solid red;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
        color: white;
    }

</style>