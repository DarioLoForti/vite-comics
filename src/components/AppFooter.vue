<script>
import AppBar from './AppBar.vue';
export default {
    components:{
        AppBar
    },
    name: "AppFooter",
    data(){
        return{
            
        }
    }
}
</script>
<template lang="">
    <footer>
        <AppBar />
        <img src="../img/dc-logo-bg.png" alt="footer-bg">
        <div class="content">
            <button> sign-up now!</button>
            <div class="image">
                <ul>
                    <li><img src="../img/footer-facebook.png" alt=""></li>
                    <li><img src="../img/footer-twitter.png" alt=""></li>
                    <li><img src="../img/footer-youtube.png" alt=""></li>
                    <li><img src="../img/footer-pinterest.png" alt=""></li>
                    <li><img src="../img/footer-periscope.png" alt=""></li>
                </ul>
            </div>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
    footer{
        position: relative;
        background-image: url(../img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        img{
            margin-left: 900px;
            height: 100%;
        }
        .content{
            display: flex;
            background-color: #1C1C1C;
            height: 75px;
            width: 100%;
            position: absolute;
            bottom: 0px;

                button{
                    border: 1px solid #5382F9;
                    color: white;
                    background: none;
                    padding: 20px;
                    margin-left: 100px ;
                    font-size: 20px;
                }

               ul{
                list-style: none;
                display: flex;

                    li{
                        max-width: 50px;
                        padding: 20px;
                    }
               }
        }
    }
</style>