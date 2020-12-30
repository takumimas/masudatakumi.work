<template>
  <div>
    <b-navbar class="nav" type="is-success" fixed-top="true">
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
             Masuda Takumi
            </b-navbar-item>
        </template>
                <template slot="end">
            <b-navbar-item tag="router-link" :to="{ path: '/about' }" class="nav-link">
                <i class="fas fa-user-alt header-i"></i>About
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/skills' }" class="nav-link">
                <i class="fas fa-book header-i"></i>Skills
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/works' }" class="nav-link">
                <i class="fas fa-briefcase header-i"></i>Works
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/links' }" class="nav-link">
                <i class="fas fa-link header-i"></i>Links
            </b-navbar-item>
        </template>
    </b-navbar>
    <div style="height:120vh;background-color:#48C774;" class="top">
      <div style="text-align:center;">
      <h1 style="color:white;font-size:2.8rem;font-weight:bolder;">
        Skills
      </h1>
        <div class="card" style="width:350px;height:70px;">
            <div>
            <i class="fab fa-html5 fa-3x" style="color:#EE6118;"></i>
            <i class="fab fa-css3-alt fa-3x" style="color:#3595CF;"></i>
            </div>
            <span>HTML CSS</span>
            <div class="score">70</div>
        </div>
        <div class="card" style="width:350px;height:70px;">
            <i class="fab fa-js fa-3x" style="color:#E9D44D;"></i>
            <span>JavaScript</span>
            <div class="score" >60</div>
        </div>
        <div class="card" style="width:350px;height:70px;">
            <i class="fab fa-python fa-3x" style="color:#275378;"></i>
            <span>Python</span>
            <div class="score" >85</div>
        </div>
        <div class="card" style="width:350px;height:70px;">
            <i class="fab fa-vuejs fa-3x" style="color:#41B883;"></i>
            <span>Vue.js Nuxt.js</span>
            <div class="score" >50</div>
        </div>
        <div class="card" style="width:350px;height:70px;">
            <i class="fab fa-node fa-3x" style="color:#333333;"></i>
            <span>Express</span>
            <div class="score" >30</div>
        </div>
        <div class="card" style="width:350px;height:70px;">
            <i class="fas fa-flask fa-3x" style="color:black;"></i>
            <span>Flask</span>
            <div class="score" >85</div>
        </div>
                <div class="card" style="width:350px;height:70px;">
            <i class="fab fa-python fa-3x" style="color:#0C4B33;"></i>
            <span>Django</span>
            <div class="score" >50</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>
<style>
.header-i{
  margin-right: 10px;
}
.nav-link{
  margin-right: 20px;
}
.top{
  display: flex;
  justify-content: center;
  align-items: center;
}
h1{
    margin-bottom: 20px;
}
h2{
    margin-bottom: 20px;
}
.about-contents{
    color:white;
    font-size:1.4rem;
}
.card{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 20px;
    
}
.card span{
    font-size: 1.5rem;
}

.score{
    width: 40px;
    height: 40px;
    background-color: #48C774;
    color:white;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
}
</style>
