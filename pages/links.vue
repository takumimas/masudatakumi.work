<template>
  <div>
    <b-navbar class="nav" type="is-danger" fixed-top="true">
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
    <div style="height:94vh;background-color:#F14668;" class="top">
      <div style="text-align:center;">
      <h1 style="color:white;font-size:2.8rem;font-weight:bolder;">
        Links
      </h1>
      <h2 class="about-contents" style="color:white;"><a href="https://www.wantedly.com/id/takumimas" style="color:white;">Wantedly</a></h2>
      <h2 class="about-contents" style="color:white;">Github:<a href="https://github.com/takumimas" style="color:white;">takumimas</a></h2>
      <h2 class="about-contents" style="color:white;">Blog:<a href="https://masublog.net" style="color:white;">MasuBlog</a></h2>
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
</style>
