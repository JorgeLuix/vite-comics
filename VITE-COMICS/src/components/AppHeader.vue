<template>
    <header class="d-flex justify-content-center ">
        <img src="../assets/img/dc-logo.png" alt="logoDc">
        <ul>
            <li>
                {{ lista }}
            </li>
        </ul>
    </header>
</template>

<script>
    export default {
        name: 'DcComics',
        data(){
            return{
                lista:'listaNav',
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>