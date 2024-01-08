<script>
export default {
    name: "AppFooter",
    data(){
        return{
            
        }
    }
}
</script>
<template lang="">
    <footer>
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
<style lang="scss">
    footer{
        position: relative;
        height: 400px;
        background-image: url(../img/footer-bg.jpg);
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
                    padding: 10px 40px;
                    margin-left: 100px ;
                }

               ul{
                list-style: none;
                display: flex;

                    li{
                        padding: 10px;
                    }
               }
        }
    }
</style>