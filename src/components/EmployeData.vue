<template>
  <div style=" background: linear-gradient(114.29deg, #0B1926 -15.11%, #020606 106.05%);
;" class="mb-5">
    <header>
      <nav class="navbar navbar-expand-lg  mb-5">
        <div class="collapse navbar-collapse e float-end mt-3 " id="navbarNav">
          <label class="sample_class" for=""><img src="https://download.logo.wine/logo/GoDaddy/GoDaddy-Logo.wine.png" style="width:51px;height: 42px; color: #02FF95;"  alt="">Sample</label>

          <ul class="navbar-nav gap-3 ">
            <li class="nav-item active ">
              <a class="nav-link text-white hoverClass" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Case Studies</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">About us</a>
            </li>
            <li class="nav-item">
              <button type="button" class="btn btn-success btn-class">Book a call</button>
            </li>
          </ul>
        </div>
      </nav>
      <section>
        <h1 class="text-white text-center">We make great digital products <br> for <span
            class="innovative">innovative</span> brands.</h1>
        <p>Get your desired design services from our talented designers,<br>around the world at a reasonable cost</p>

        <div class="text-center">
          <span>
            <i class="fa fa-envelope" style="font-size:20px;color" id="img_style"></i>
            <input  type="email" placeholder="      Your work email">
          </span>
          <span>
            <b-button type="button" class="btn btn-success btn-class">Book a call</b-button>
          </span>
          <p>4.5/5.0 <span class="fa fa-star checked m-1" style="color:orange"></span>
            <span class="fa fa-star checked  " style="color:orange"></span>
            <span class="fa fa-star checked m-1 " style="color:orange"></span>
            <span class="fa fa-star checked " style="color:orange"></span>
            <span class="fa fa-star-half m-1" style="color:orange"></span>
            15+ Businesses, 35+ Happy clients.
          </p>
        </div>
      </section>
    </header>
    <footer>
      
   
    <div class="container text-center" style="margin-top: 150px;">
  <div class="row align-items-start">
    <div class="col">
      <div class="i-con center_style ">
        <i class="fa fa-desktop" style="font-size:32px;color:#02FF95"></i>

      </div>
      <h5 class="">Web Design</h5><p>Crafting websites that convert and <br> grow your business</p>

    </div>
  
    <div class="col">
      <div class="i-con center_style">
        <i class="fa fa-mobile" style="font-size:32px;color:#02FF95"></i>

      </div>
      <h5 class="">Web Design</h5><p>Crafting websites that convert and <br> grow your business</p>
      
    </div>
    <div class="col"> 
      <div class="i-con center_style" >
        <i  class="fa fa-bars" aria-hidden="true" style="font-size:32px;color:#02FF95"></i>
      </div>
    
      <h5 class="">UX Audit</h5><p>Get a detailed UX report on your<br>marketing website</p>
     
    </div>
  </div>

</div>
 
    </footer>
  </div>
</template>

<script>
export default {

}
</script>

<style>
#img_style{
  position: absolute;
  margin-left: 20px;
  margin-top: 20px;
}
h5{
color: #02FF95;
}
.center_style{
  margin-left: 143px;
  
}
.i-con{
  background: rgb(17, 43, 17);
    border-radius: 76%;
    width: 59px;
    padding: 10px
}
p {
  font-size: 13px;
  font-weight: 400;

  letter-spacing: 0em;
  text-align: center;
  color: #D1FFEB;

}

.innovative {
  font-weight: 500;
  color: #02FF95;
}

.btn-class {
  border-radius: 20px;
  padding-right: 20px;
  padding-left: 20px;
}

span ul {
  margin: 0;
  padding: 0;
}

a:hover {
  color: #02FF95;
  border-bottom: 1px solid #02FF95;
}

.navbar-expand-lg .navbar-collapse {
  display: flex !important;
  flex-basis: auto;
  justify-content: space-around;
}

.sample_class {
  font-family: Darker Grotesque;
  font-size: 30px;
  font-weight: 900;
  line-height: 37px;
  letter-spacing: 0em;
  text-align: left;
  color: #02FF95;
}

input {
  margin: 10px;
  outline: none;
  border-radius: 20px;
  padding: 6px 12px;
  padding-right: 34px;
}</style>