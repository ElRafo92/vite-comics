<script>

export default {
    name: 'MainFooter', 


  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="box">
    <div class="container">
      <nav>
        <ul>
          <li><a class="list-title" href=""><strong>DC COMICS</strong></a></li>
          <li><a href="">Characters</a></li>
          <li><a href="">Comics</a></li>
          <li><a href="">Movies</a></li>
          <li><a href="">TV</a></li>
          <li><a href="">Games</a></li>
          <li><a href="">Videos</a></li>
          <li><a href="">News</a></li>
        </ul>
        
        <ul>
          <li><a class="list-title" href=""><strong>DC</strong></a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
          <li><a href="">Terms of Use</a></li>
        </ul>
    
        <ul>
          <li><a class="list-title" href=""><strong>SITES</strong></a></li>
          <li><a href="">DC</a></li>
          <li><a href="">MAD Magazine</a></li>
          <li><a href="">DC Kids</a></li>
          <li><a href="">DC Universe</a></li>
          <li><a href="">DC Power Visa</a></li>
        </ul>

        <ul>
          <li><a class="list-title" href=""><strong>SHOP</strong></a></li>
          <li><a href="">Shop DC</a></li>
          <li><a href="">Shop DC Collectibles</a></li>
        </ul>
      </nav>
      <img src="../assets/dc-logo-bg.png" alt="">
    </div>
  </div>
</template>

<style scoped>
.container{
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.box {
  background-image: url('../assets/footer-bg.jpg');
  padding: 30px 0px;
  height: 482px;
}

li {
  list-style: none;
}

a {
  color: grey;
  text-decoration: none;
}

.list-title {
  color: white;
}
nav {
  width: 50%;
  display: flex;
  flex-wrap: wrap;
}

ul {
  width: calc(100% / 3 - 10px);
  margin-right: 10px;
  margin-top: 5px;
}

img {
  object-fit: cover;
}
</style>