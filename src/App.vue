<template>
  <div id="app">
    <header>
      <nav>
        <div class="row">
            <ul class="main-nav">
              <li><a href="#">Resume</a></li>
              <li><a href="#">Education</a></li>
              <li><a href="#">Portfolio</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
        </div>
      </nav>
      <section class="hero">
        <div class="row">
          <div class="col span-6-of-12 hero-boxes">
            <img src="../public/assets/images/2020headshotsidesquare.jpg" class="hero-pic">
          </div>
          <div class="col span-6-of-12  hero-boxes">
            <div class="hero-text-box">
              <h1>Aria Nikzad</h1>
              <br>
              <h2>Full Stack Developer</h2>
            </div>
            <div class="icon-small">
              <i class="devicon-ruby-plain"></i>
              <i class="devicon-rails-plain"></i>
              <i class="devicon-vuejs-plain"></i>
              <i class="devicon-javascript-plain"></i>
              <i class="devicon-css3-plain"></i>
              <i class="devicon-html5-plain"></i>
              <i class="devicon-bootstrap-plain"></i>
              <i class="devicon-github-plain"></i>
              <i class="ion-social-bitcoin"></i>
            </div>
          </div>
          <h1></h1>
        </div>
      </section>
    </header>
    <router-view/>
    <footer>
      <div class="row">
        <div class="col span-1-of-3">
          <ul class="footer-nav">
            <li>
              <a href="#" class="footer-icon-small"><i class="ion-email"></i></a>
              <p>a.c.nikzad@gmail.com</p>
            </li>
          </ul>
        </div>
        <div class="col span-1-of-3">
          <ul class="social-links">
            <li><a href="#" class="footer-icon-small"><i class="ion-map"></i></a></li>
            <li>Sacramento, CA</li>
          </ul>
        </div>
        <div class="col span-1-of-3">
          <ul class="social-links">
            <li><a href="#"><i class="footer-icon-iphone"></i></a></li>
            <li>(415) 328-7478</li>
          </ul>
        </div>
      </div>
      <div class="row">
        <p>"The same boiling water that softens the potato hardens the egg. <br>It's about what you're made of, not the circumstances."<br>- Mel Robbins</p>
      </div>
    </footer>
  </div>
</template>

<style>

</style>

<div class="row gtr-200">
        <div class="col-8 col-12-medium">