<template>
    <div class="bg-foot text-white d-flex justify-content-between">
       <div class="container d-flex pt-5">
        <ul>
            <h6 class="text-uppercase fw-bold">dc comics</h6>
            <li v-for="item in listDcComics" :key="item">
               <a href="#">{{ item }}</a> 
            </li>
        </ul>
        <ul>
            <h6 class="text-uppercase fw-bold">dc</h6>
            <li v-for="item in listDc" :key="item">
               <a href="#">{{ item }}</a> 
            </li>
        </ul>
        <ul>
            <h6 class="text-uppercase fw-bold">sites</h6>
            <li v-for="item in sitesList" :key="item">
               <a href="#">{{ item }}</a> 
            </li>
        </ul>
    </div>
        <div class="container">
            <img class="" src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
    
</template>

<script>
import { listDcComics } from '../data/data.js'
import { listDc } from '../data/data.js'
import { sitesList } from '../data/data.js'
    export default {
        name: 'listDcComics',
        name: 'listDc',
        name: 'sitesList',
        data(){
            return{
                listDcComics: listDcComics,
                listDc: listDc,
                sitesList: sitesList
            }
        }
    }
</script>

<style lang="scss" scoped>
.bg-foot{
    background-image: url(../assets/img/footer-bg.jpg);
    }
    ul{
        li a{
            text-decoration: none;
            color: grey;
        }
    }
.w-img{
      width: 50%;
  }
</style>