<template>
    <header class="">
        <div class="container d-flex justify-content-center justify-content-between m-3">
        <img src="../assets/img/dc-logo.png" alt="logoDc">
        <ul class="d-flex gap-4 text-uppercase align-items-center ">
            <li>
               <a href="">characters</a> 
            </li>
            <li>
               <a href="">comics</a> 
            </li>
            <li>
                <a href="">movies</a>
            </li>
            <li>
                <a href="">tv</a>
            </li>
            <li>
                <a href="">games</a>
            </li>
            <li>
                <a href="">collectibles</a>
            </li>
            <li>
                <a href="">videos</a>
            </li>
            <li>
                <a href="">fans</a>
            </li>
            <li>
                <a href="">news</a>
            </li>
            <li>
                <a href="">shop</a>
            </li>
        </ul>
    </div>
    </header>
</template>

<script>
    export default {
        name: 'DcComics',
        data(){
            return{
                
            }
        }
    }
</script>

<style lang="scss" scoped>

ul {
    li a{
        font-size: 0.8rem;
        color: grey;
        font-weight: 500;
        text-decoration: none;
        box-shadow: 0, 0, 0, 5px rgb(52, 52, 240);
    }
}
</style>