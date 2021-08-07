<template>
  <div>
    <b-navbar class="nav" type="is-warning" fixed-top="true">
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
    <div style="height:94vh;background-color:#FFDD57;" class="top">
      <div style="text-align:center;">
      <h1 style="color:black;font-size:2.8rem;font-weight:bolder;">
        Works
      </h1>
    <b-carousel style="width:90vw;">
        <b-carousel-item>
            <section class="hero is-medium is-primary">
                <div class="hero-body has-text-centered">
                    <h1 class="title">TownWith</h1>
                    <p>地域の魅力を共有できるWebサービス</p>
                    <p>PythonのフレームワークFlaskを使用して開発しました</p>
                    <p>バックエンド:Python/Flask/MySQL/Apache</p>
                    <p>フロントエンド:jQuery/Bulma</p>
                </div>
            </section>
        </b-carousel-item>
        <b-carousel-item>
            <section class="hero is-medium is-info">
                <div class="hero-body has-text-centered">
                    <h1 class="title">ThinkShare</h1>
                    <p>自分の考え方などを共有できるWebサービス</p>
                    <p>フレームワークなどを使わずゼロから開発をしました</p>
                    <p>バックエンド:Python(CGI)/PostgresQL/Apache</p>
                    <p>フロントエンド:BootStrap</p>
                </div>
            </section>
        </b-carousel-item>
                <b-carousel-item>
            <section class="hero is-medium is-success">
                <div class="hero-body has-text-centered">
                    <h1 class="title">WPMarket</h1>
                    <p>WordPressのプラグインを販売できるWebサービス</p>
                    <p>WordPressのプラグインを組み合わせて開発しました</p>
                    <p>バックエンド:WordPress</p>
                    <p>決済:Stripe</p>
                </div>
            </section>
        </b-carousel-item>
            <b-carousel-item>
            <section class="hero is-medium is-info">
                <div class="hero-body has-text-centered">
                    <h1 class="title">複式家計簿</h1>
                    <p>複式簿記で家計簿をつけることができるWebアプリです</p>
                    <p>Nuxt.jsとFirebaseで開発しました</p>
                    <p><a href="https://fukushiki-kakeibo.com/" style="border-bottom:solid white 1px;">アクセスはこちら</a></p>
                </div>
            </section>
        </b-carousel-item>
    <b-carousel-item>
            <section class="hero is-medium is-danger">
                <div class="hero-body has-text-centered">
                    <h1 class="title">Comming Soon..</h1>
                    <p>B2Bサービスを開発しています</p>
                    <p>バックエンド:Express</p>
                    <p>フロントエンド:Nuxt.js</p>
                </div>
            </section>
        </b-carousel-item>
    </b-carousel>
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
    color:black;
    font-size:1.4rem;
}
p{
    margin-bottom: 15px;
}
</style>
