<template>
    
     <FooterComponent/>
     <div class="bg-footer p-3">
       <div class=" container d-flex justify-content-between align-items-center">
        <button type="button" 
            class="btn btn-outline text-white text-uppercase rounded-0 border border-3 border-primary">
            sign-up now!
        </button>
    
    
        <ul class="d-flex align-items-center gap-3">
            <li><a class="text-primary" href="">follows us</a></li>
            <li><a href=""><img src="../assets/img/footer-facebook.png" alt=""></a></li>
            <li><a href=""><img src="../assets/img/footer-twitter.png" alt=""></a></li>
            <li><a href=""><img src="../assets/img/footer-youtube.png" alt=""></a></li>
            <li><a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
            <li><a href=""><img src="../assets/img/footer-periscope.png" alt=""></a></li>
        </ul>
    </div>
     </div>
    
</template>

<script>
import FooterComponent from './FooterComponent.vue';
    export default {
        name: 'Appfooter',
        components: { FooterComponent }
      
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
    footer{
        height: 80px;
    }
</style>