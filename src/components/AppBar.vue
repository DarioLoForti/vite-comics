<script>
export default {
    name: "AppBar",
    data(){
        return{
            
        }
    }
}
</script>
<template lang="">
    <div class="bg">

        <div class="container">
            <div class="content">
                <img src="../img/buy-comics-digital-comics.png" alt="">
                <h2>Digital Comics</h2>
                <img src="../img/buy-comics-merchandise.png" alt="">
                <h2>Dc merchandise</h2>
                <img src="../img/buy-comics-subscriptions.png" alt="">
                <h2>Subscription</h2>
                <img src="../img/buy-comics-shop-locator.png" alt="">
                <h2>Comic shop locator</h2>
                <img src="../img/buy-dc-power-visa.svg" alt="">
                <h2>Dc power visa</h2>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.bg{
    width: 100%;
    background-color: $my_color;
}
    .container{
        display: flex;
        justify-content: space-between;
        height: 150px;
        

            .content{
                display: flex;
                justify-content: space-between;
                align-items: center;
                width: 100%
            }

            img{
               
                height: 70%;
                padding: 30px 20px;
                margin: 0px 20px;
            }

            h2{
                color: white;
                font-weight: 500;
                font-size: 14px;
                text-transform: uppercase;
            }
    }
</style>