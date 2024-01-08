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
    <img src="../img/dc-logo.png" alt="Logo">
    <nav>
        <ul>
            <li v-for="(menu, index) in menus" :key="index">
                {{menu.voce}}
            </li>
        </ul>
    </nav>

   </header>
</template>
<style lang="scss">
    header {
        height: 75px;
        display: flex;
        
        img{
            height: 75%;
            margin-left: 100px;
            margin-top: 10px;
        }

        ul{
            list-style: none;
            display: flex;
            margin-left: 300px;
            margin-top: 10px;

                li{
                    font-weight: 600;
                    padding: 10px;
                }   
        }

    }
</style>