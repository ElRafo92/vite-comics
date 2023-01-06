<script>

export default {
    name: 'TopFooter', 


  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="box">
    <nav class="container">
        <ul>
            <li><a href=""><img src="../assets/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</a></li>
            <li><a href=""><img src="../assets/buy-comics-merchandise.png" alt="">DC MERCHANDISE</a></li>
            <li><a href=""><img src="../assets/buy-comics-subscriptions.png" alt="">SUBSCRIPTION</a></li>
            <li><a href=""><img src="../assets/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</a></li>
            <li><a href=""><img src="../assets/buy-dc-power-visa.svg" alt="">DC POWER VISA</a></li>
        </ul>
    </nav>
  </div>
</template>

<style scoped>
.box{
    background-color: #0282f9;  
    padding: 40px;  
}
.container{
    max-width: 1200px;
    margin: auto;
}

img {
    width: 50px;
    height: 50px;
    object-fit: contain; 
    margin-right: 10px;
}

ul {
    display: flex;
    justify-content: space-around;
}

li {
    list-style: none;
}

a {
    text-decoration: none;
    display: flex;
    align-items: center;
    color: white;
    font-size: 13px;
}
</style>