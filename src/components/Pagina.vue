<script setup lang="ts">

</script>

<template>
 <header>   
    <nav>
        <lang for="" class="brand">
            <a href=""><img src="https://logosmarcas.net/wp-content/uploads/2020/04/BMW-Logo.png" alt=""></a>
        </lang>
        <ul class="menu">
            <li><a href="#inicio">Inicio</a></li>
            <li>
                <a href="#acerca">modelos carros</a>
                <ul class="submenu">
                    <li><a href ="#">modelo</a></li>
                    <li><a href ="#">modelo</a></li>
                    <li><a href ="#">modelo</a></li>
                </ul>
            </li>
            <li>
                <a href="#ropa">modelos motos</a>
            <ul class="submenu">
                <li><a href ="#">modelo</a></li>
                <li><a href ="#">modelo</a></li>
                <li><a href ="#">modelo</a></li>
            </ul>
            </li>
            <li>
                <a href="#accesorios para carro">accesorios para carro</a>
                <ul class="submenu">
                <li><a href ="#">carro</a></li>
                <li><a href ="#">carro</a></li>
                <li><a href ="#">carro</a></li>
            </ul>
            </li>
            <li>
                <a href="#accesorios para moto">accesorios para moto</a>
                <ul class="submenu">
                <li><a href ="#">moto</a></li>
                <li><a href ="#">moto</a></li>
                <li><a href ="#">moto</a></li>
            </ul>
            </li>
            <li>
                <a href="#más sobre bmw">más sobre bmw</a>
                <ul class="submenu">
                <li><a href ="#">bmw</a></li>
                <li><a href ="#">bmw</a></li>
                <li><a href ="#">bmw</a></li>
            </ul>
            </li>
        </ul>
    </nav>
</header>


</template>



<style>
.brand img{
    width: 75px;
    text-align: left; 
}

body{
background-image: url(https://cdn-0.totalmotorcycle.com/wp-content/uploads/2022/11/2023-BMW-S1000RR3.jpg);
background-size: cover;  
}
header {
  position: fixed;
  top: 0;
  left: 7%;
  width: 88%;
  background: white;
  color: black;
 
}

nav li {
    display: inline; 
    margin-right: 30px; 
    
}
.menu {

  margin: 20px;
  display: flex;

}


.menu > li > a {
  display: block;
  padding: 15px 15px;
  color: white;
  background-color: #0d0c0c;
}

.menu > li > a:hover {
  background-color: #0a1882;
}


.submenu {
  list-style: none;
  margin: 0;
  padding: 0;
  display: none;
  position: static;
  top: 100%;
  left: 0;
  background-color: #053a65;
}

.submenu li a {
  padding: 10px 20px;
  color: black;
  text-decoration: none;
}

.submenu li a:hover {
  background-color: #053a65;
}


.menu > li:hover .submenu {
  display: inline-flex;
}

</style>

