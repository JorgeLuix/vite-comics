<template>
    <div class="jc-card">
        <img :src="thumb" alt="Card image cap">
        <div class="card-body">
              <h3 class="card-title">{{ series }}</h3>
              <h6 class="card-subtitle mb-2 text-muted">{{ type }}</h6>
           <div class="price-play">
              <p class="price">{{ price }}</p>
            </div>
        </div>
    </div>
</template>
  
  <script>
  export default {
    name: 'Card',
    props: {
      thumb: String,
      price: String,
      series: String,
      type: String,
    },
  };
  </script>
  
  <style lang="scss">

.jc-card {
  width: 100%;
  transition: all ease 0.4s;
  border-radius: 5px;
 
  .card-body {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 1rem;
    color: white;
  }
  .card-title {
    font-size: 1rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
    white-space: wrap;
    overflow: hidden;
    text-overflow: ellipsis;
    text-align: center;
  }

  .card-subtitle {
    font-size: 1rem;
    margin-bottom: 0.5rem;
    text-align: center;
  }

  .price {
    font-size: 1.2rem;
    font-weight: bold;
    text-align: center;
  }

}
.jc-card:hover{
    cursor: pointer;
    background-color:  #252525;
  }
  .jc-card img{
    width: 100%;
    border-radius: 8px;
    padding-top: 8px;
  }
  .price-play {
    position: relative;
  }
  .price{
    position: absolute;
    right: 10px;
    bottom: 10px;
    padding: 18px;
    background-color: #99E32D;
    border-radius: 100%;
    opacity: 0;
    transition: all ease 0.4s;
  }
  .jc-card:hover .price-play .price{
    opacity: 1;
    transform: translateY(-20px);
  }
</style>