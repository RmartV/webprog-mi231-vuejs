<template>
    <div class="nav">
        <a class="current" href="index.html" style="color: black;">About me</a>
        <a href="index_edu.html">Education</a>
        <a href="index_ITex.html">IT Experience</a>
        <a href="index_hob.html">Hobbies & Interest</a>
        <a href="index_goal.html">Goals In Life</a>
        <a href="index_gall.html">Picture Gallery</a>
        
    </div>

    <div class="grid-container">
        <div class="item3">
            <div class="flex-container">
                <div>
                    <p>Hello! Welcome to my personal Website! My name is Ray Mart Villacorte but you can call me RM, from Taguig City. A second year of Asia Pacific College.</p>
 
                </div>
            </div>
        </div>
    </div>
</template>
<script> </script>
<style>
.nav {
  display: flex;
  align-items: center;
  flex-wrap: wrap; 
  background-image: linear-gradient(0.25turn, #001E39, #001F3D, #325D86);
  width: 1600px; 
  height: 55px;
  margin: 45px auto; 
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
.nav a {
  color: #f2f2f2;
  font-weight: bold;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 15px;
  transition: background-color 0.3s, color 0.3s;
}
.nav a:hover {
  background-color: #ddd;
  color: black;
}

.nav a.active {
  background-color: #04AA6D;
  color: white;
}
.current{
  background-color: #87a9c7;
}

.flex-container {
  display: flex;
  flex-wrap: nowrap;
  align-items: center;
  background-color: #102C46;
  box-shadow: 5px 10px #001424;
  width: 1000px;
  max-width: 90%; 
}

.flex-container > div {
  text-align: center;
}
.item3 {
  display: flex;
  justify-content: center;
  margin-top: 100px;
  
}

.item3 p {
  padding: 20px;
  color: aliceblue;
  font-size: 23px;
}
</style>