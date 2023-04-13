<template>
    <div class="d-flex justify-content-between bg-footer p-3 ">
        <button type="button" 
            class="btn btn-outline text-white text-uppercase rounded-0 border border-3 border-primary">
            sign-up now!
        </button>
        <ul class="d-flex gap-3">
            <li><a class="text-primary" href="">follows us</a></li>
            <li><a href=""><i class="fa-brands fa-facebook"></i></a></li>
            <li><a href=""><i class="fa-brands fa-twitter"></i></a></li>
            <li><a href=""><i class="fa-brands fa-youtube"></i></a></li>
            <li><a href=""><i class="fa-brands fa-pinterest"></i></a></li>
            <li><a href=""><i class="fa-solid fa-location-dot"></i></a></li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'Appfooter',
        data() {
            return {

            }
        }
    }
</script>

<style lang="scss" scoped>
    ul {
        li a{
            font-size: 0.8rem;
            text-transform: uppercase;
            text-decoration: none;
            font-weight: 500;
        }
    }
    .bg-footer{
        background-color: rgb(78, 77, 77);
    }
</style>