<template>
  <div>
    <b-navbar class="nav" type="is-primary" fixed-top="true">
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
    <div style="height:94vh;background-color:#7957D5;" class="top">
      <div style="text-align:center;">
      <h1 style="color:white;font-size:2.8rem;font-weight:bolder;">
        Masuda Takumi
      </h1>
      <h2 style="color:white;font-size:1.2rem;">Web Developer</h2>
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
</style>
