<template>
  <footer>
    <section class="nav">
      <div class="container">
        <ul>
          <div class="col">
            <li><h2>DC COMICS</h2></li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li><h2>SHOP</h2></li>
            <li>Lorem</li>
            <li>Lorem</li>
          </div>
          <div class="col">
            <li><h2>DC</h2></li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
          </div>
          <div class="col">
            <li><h2>SITES</h2></li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
          </div>
        </ul>
        <img src="..\dc-comics-assets\img\dc-logo-bg.png" alt="dc logo">
      </div>
    </section>
    <section class="info">
      <div class="container">
        <div class="button">
          SIGN-UP NOW!
        </div>
        <div class="socials">
          FOLLOW US
          <img src="..\dc-comics-assets\img\footer-facebook.png" alt="Facebook">
          <img src="..\dc-comics-assets\img\footer-twitter.png" alt="Twitter">
          <img src="..\dc-comics-assets\img\footer-youtube.png" alt="YouTube">
          <img src="..\dc-comics-assets\img\footer-pinterest.png" alt="Pinterest">
          <img src="..\dc-comics-assets\img\footer-periscope.png" alt="Periscope">
        </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss">
footer {
  .nav {
    background-image: url("../dc-comics-assets/img/footer-bg.jpg");
    color: white;
    
    height: 40vh;
    overflow: hidden;
    .container{
      display: flex;
      justify-content: space-between;
      height: 100%;
      
      img{
        height: 150%;
        transform:translate(0,-100px);
      }
      ul{
        padding: 40px 0;
        list-style: none;
        display: flex;
        .col{
          margin:0 20px;
          li{
            color :gray;
            font-size: 14px;
            h2{
              color:white;  
              margin: 10px 0;
            }
          }
        }
      }
    }
  }
  .info {
    height: 10vh;
    background: #303030;
    .container{
      height: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      .button{
        color:white;
        padding:10px;
        border:2px solid #0c7cec;
      }
      .socials{
        width: 30%;
        color: #0c7cec;
        font-size: 20px;
        font-weight:900;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
      }
    }
  }
}
</style>