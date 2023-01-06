<script>

export default {
    name: 'ListHeader', 


  data() {
    return {
      
    }
  }
}
</script>

<template>
 <nav>
    <ul>
        <li><a href="">characters</a></li>
        <li><a href="">comics</a></li>
        <li><a href="">movies</a></li>
        <li class="select"><a href="">tv</a></li>
        <li><a href="">games</a></li>
        <li><a href="">collectibles</a></li>
        <li><a href="">videos</a></li>
        <li><a href="">fans</a></li>
        <li><a href="">news</a></li>
        <li><a href="">shop</a></li>
    </ul>
 </nav>
</template>

<style scoped>
nav{
    display: flex;
    align-items: center;
}

ul {
    display: flex;
    justify-content: space-between;
    padding-inline-start: 0px;
    height: 100%;

}

li {
    padding: 10px;
    display: flex;
    height: 100%;
    list-style: none;
    justify-content: center;
    align-items: center;
}

a {
    color: inherit;
    text-decoration: none;
}

.select{
    color: #0282f9;
    border-bottom: 5px solid #0282f9;
}
</style>