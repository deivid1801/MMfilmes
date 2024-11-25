<script setup>

</script>

<template>

  <header>
    <img src="/src/assets/M-removebg-preview.png" alt="" class="img">
    <nav class="nav">
      <ul class="nav-link">
        <RouterLink class="link"><li class="li-link">Filmes</li></RouterLink>
        <RouterLink class="link"><li class="li-link">Lançamentos</li></RouterLink>
        <RouterLink class="link"><li class="li-link">Lista</li></RouterLink>
      </ul>
    </nav>
  </header>

  <section id="img">
    <div class="painel-home">

      

    </div>
  </section>

  <div style="height: 1000px;">
    <h1></h1>
  </div>



</template>

<style scoped>
.body{
  background-color: black;
}
header {
  background-color: #5E5E5E;
  display: flex;
  padding: 20px;
  align-items: center;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  position: fixed;
  top: 0;
  left: 0;
  min-width: 100%;
  z-index: 1000;
}
.img{
  width: 150px;
  height: 50px;
  size: 20%;
  margin-left: 600px;
}
.nav-link {
  display: flex;
  gap: 50px;
}

.link {
  color: #fff;
  list-style: none;
  text-decoration: none;
  transition: 0.3s;
}

.link:hover {
  color: black;
}


.nav {
  display: flex;
  margin-left: auto;
  margin-right: 800px;
}

#img {
  background-image: url(/src/assets/img/casa-de-luxo-7-1.jpg);
  background-size: cover;
  height: 100vh;
}

</style>