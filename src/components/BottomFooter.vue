<script>

export default {
    name: 'BottomFooter', 


  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="box">
    <div class="container">
      <button>
          SIGN-UP NOW!
      </button>
      <div class="follow">
        <strong>FOLLOW US</strong>
        <nav>
          <ul>
            <li><a href=""><img src="../assets/footer-facebook.png" alt=""></a></li>
            <li><a href=""><img src="../assets/footer-twitter.png" alt=""></a></li>
            <li><a href=""><img src="../assets/footer-youtube.png" alt=""></a></li>
            <li><a href=""><img src="../assets/footer-pinterest.png" alt=""></a></li>
            <li><a href=""><img src="../assets/footer-periscope.png" alt=""></a></li>
          </ul>
        </nav>
      </div>
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
  background-color: #303030;
  padding: 30px 0px;
}

button {
  height: fit-content;
  padding: 10px;
  background-color: #303030;
  color: white;
  border: 2px solid #0282f9;
  cursor: pointer;
}

.follow {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

strong {
  color: #0282f9;
  margin-right: 15px;
}

ul {
  display: flex;
  justify-content: space-between;
} 

li {
  list-style: none;
  margin: 0px 5px;
} 

a {
  text-decoration: none;
}
</style>