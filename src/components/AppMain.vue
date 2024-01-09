<script>
export default {
    name: "AppMain",
    data(){
        return{
            
        }
    }
}
</script>
<template lang="">
    <main>
        <div class="container">
            <h2> --> Content goes here <-- </h2>
        </div>
    </main>
</template>
<style lang="scss" scoped>
@use '../styles/generals.scss' as *;
    main{
        background-color:#1C1C1C ;
        height: 100px;

        h2{
            color: white;
            padding: 30px;
            
        }
    }
</style>