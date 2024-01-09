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
    margin: 10px;
    padding: 10px;

    img{
        max-width: 100%;
        height: 100%;
    }
    h4{
        color: white;
    }
}
    
</style>