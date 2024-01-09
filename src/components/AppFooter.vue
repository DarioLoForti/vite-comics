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
        <div class="container">
            <div class="top-footer">
                <div class="list-footer">
                    <h3> dc comics</h3>
                    <ul>
                        <li>characters</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>tv</li>
                        <li>games</li>
                        <li>videos</li>
                        <li>news</li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li>shop dc</li>
                        <li>shop dc collectibles</li>
                    </ul>
                </div>
                <div class="list-footer">
                    <h3>dc</h3>
                    <ul>
                        <li>terms of us</li>
                        <li>privacy policy (new)</li>
                        <li>ad choise</li>
                        <li>advertising</li>
                        <li>jobs</li>
                        <li>subscription</li>
                        <li>talent workshops</li>
                        <li>cpsc certificates</li>
                        <li>ratings</li>
                        <li>shop help</li>
                        <li>contact us</li>
                    </ul>
                </div>
                <div class="list-footer">
                    <h3>sites</h3>
                    <ul>
                        <li>dc</li>
                        <li>mad magazine</li>
                        <li>dc kids</li>
                        <li>dc universe</li>
                        <li>dc power visa</li>
                    </ul>
                </div>
            </div>
            
        </div>
        <div class="bg-footer">
            <div class="container">

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
            </div>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
@use '../styles/generals.scss' as *;
    footer{
        position: relative;
        background-image: url(../img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        

        .top-footer{
            background-image: url(../img/dc-logo-bg.png);
            background-position: right;
            background-repeat: no-repeat;
            display: flex;
            height: 400px;
            padding: 50px;
            

            .list-footer{
                margin-right: 30px;
                h3{
                    text-transform: uppercase;
                    color: white;
                }
                ul{
                    list-style: none;
                    margin: 0px 0px 30px 0px;


                    li{
                        color: gray;
                        font-size: 14px;
                    }
                }
            }
        }
        
        .content{
            display: flex;
            justify-content: space-between;
            align-items: center;
            
            height: 75px;
            width: 100%;
            

                button{
                    border: 1px solid #5382F9;
                    color: white;
                    background: none;
                    font-size: 20px;
                    height: 50%;
                }

               ul{
                list-style: none;
                display: flex;

                    li{
                        max-width: 60px;
                        padding: 20px;
                    }
               }
        }
        .bg-footer{
            background-color: #1C1C1C;
        }
    }
</style>