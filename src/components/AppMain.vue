<template>
    <div class="here">
       <div class="height-jumbo">
            <AppJumbotron/>
       </div>    
        <section class="m-5">
            <seriesComponent/>
        </section>
      
      <div class="bg-primary">
        <div class="container d-flex gap-3 p-3 justify-content-around align-items-cente">
            <span><a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt=""> digital comics</a></span>
            <span><a href="#"><img src="../assets/img/buy-comics-merchandise.png" alt=""> dc merchandise</a></span>
            <span><a href="#"><img src="../assets/img/buy-comics-subscriptions.png" alt=""> subscription</a></span>
            <span><a href="#"><img src="../assets/img/buy-comics-shop-locator.png" alt=""> comic shop locator</a></span>
            <span><a href="#">
                <img class="" src="../assets/img/buy-dc-power-visa.svg" alt=""> dc power visa
                </a></span>
       </div>
     </div>
   </div>
</template>

<script>
import AppJumbotron from './AppJumbotron.vue';
import seriesComponent from './seriesComponent.vue'; 

    export default {
    name: "AppMain",
    components: { AppJumbotron, seriesComponent },
  }

</script>

<style lang="scss" scoped>
.here {
    background-color: black;
    color: white;
}

div{
    span {
        text-transform: uppercase;
        font-size: 0.8rem;
        color: white;
    }
    span a {
        color: white;
        text-decoration: none;
    }
    span a img {
        width: 20%;
        padding-right: 10px;
        
    }
}
</style>