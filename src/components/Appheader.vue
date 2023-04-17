<template>
    <header class="">
        <div class="container d-flex justify-content-center justify-content-between m-3">
        <img src="../assets/img/dc-logo.png" alt="logoDc">
        <ul class="d-flex gap-4 text-uppercase align-items-center ">
            <li v-for="item in headerItems" :key="item">
               <a href="#">{{ item }}</a> 
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
                headerItems: [
                    "Characters",
                    "Comics",
                    "Movies",
                    "Tv",
                    "Games",
                    "Collectibles",
                    "Videos",
                    "Fans",
                    "News",
                    "Shop"
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>

ul {
    li a:hover {
       padding-bottom: 20px;
        box-shadow: rgb(21, 21, 245) 0px 1.95px 0px;
}
    li a{
        font-size: 0.8rem;
        color: grey;
        font-weight: 500;
        text-decoration: none;
    }
}
</style>