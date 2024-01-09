<script>
export default {
    name: "AppHeader",
    data(){
        return{
            menus: [
                {
                    voce: "Characters"
                },

                {
                    voce: "Comics"
                },

                {
                    voce: "Movies"
                },

                {
                    voce: "Tv"
                },

                {
                    voce: "Games"
                },

                {
                    voce: "Collectibles"
                },

                {
                    voce: "Videos"
                },

                {
                    voce: "Fans"
                },

                {
                    voce: "News"
                },

                {
                    voce: "Shop"
                }
            ]
        }
    }
}
</script>
<template lang="">
   <header>
    <div class="container">
        <div class="navbar">
            <div class="logo">
                <img src="../img/dc-logo.png" alt="Logo">
            </div>
            <div class="menu">
                <ul>
                    <li v-for="(menu, index) in menus" :key="index" :class="index == 1 ? 'active' : ''">
                        {{menu.voce}}
                    </li>
                </ul>
            </div>
        </div>
    </div>
   </header>
</template>
<style lang="scss">
@use '../styles/generals.scss' as *;

    .navbar{
        display: flex;
        justify-content: space-between;
        padding: 20px 0;
        
        img{
            width: 80px;
            vertical-align: middle;
        }

        
        ul{
            list-style: none;
            margin: 0;
            display: flex;

                li{
                    text-transform: uppercase;
                    line-height: 80px;
                    font-weight: 600;
                    padding: 0 10px;

                    &.active,
                    &:hover{
                        color: #5382F9;
                        border-bottom: 5px solid #5382F9;
                    }
                }   
        }

    }
</style>