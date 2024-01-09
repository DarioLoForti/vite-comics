<script>
export default {
    name: "AppCard",
    props: {
        comic: Object
    }
}
</script>
<template lang="">
    <div class="card">
        <img :src="comic.thumb" alt="">
        <h4> {{comic.series }}</h4>

    </div>
</template>
<style lang="scss" scoped>
.card{
    width: calc(100% / 6 - 20px) ;
    height: 200px;
    margin: 10px;
    margin-bottom: 30px;
    padding: 10px;

    img{
        width: 100%;
        height: 100%;
    }
    h4{
        margin-top: 10px;
        color: white;
        text-transform: uppercase;
    }
}
    
</style>