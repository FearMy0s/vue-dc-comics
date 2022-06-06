<template>
  <footer class="footer">
      <div class="container-footer">
        <ul>
              <h1>Dc Comics</h1>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <h1 class="trick">Shop</h1>
              <li>no</li>
              <li>no</li>
          </ul>
            <ul>
              <h1>DC</h1>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
          </ul>
            <ul>
              <h1>SITES</h1>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
          </ul>
            <ul>
              <h1>SHOP</h1>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
              <li>no</li>
          </ul>
    </div>
          
    <div class="container-bottom">
      <div class="container">
        <div  class="container-bottom-1">
          <button class="join">SING-UP NOW!</button>
        </div>
          <h2>FOLLOW US!</h2>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
name:'DCfooter',
}
</script>

<style>
 .footer{
    
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 500px;
}


 .container-footer {
    background-image: url("../assets/img/dc-logo-bg.png");
    background-repeat: no-repeat;
    background-size: 50%;
    background-position: right;
    padding-top:100px;
    display: flex;
    color: white;
    gap: 80px;
 }
 .footer li{
     padding-top: 5px;
     list-style: none;   
 }
 .join{
   margin-top: 30px;
   border: 3px solid blue;
   background-color: transparent;
   font-size: 20px;
   color: white;
   width: 170px;
   height: 50px;
 }

 .trick{
     margin-top:30px ;
 }
</style>