---
layout: post
title: "Sass - burger with Bootstrap 4 Nav Example"
date: 2017-04-30
---
<div class="col-xl-12 col-lg-12 col-md-12 col-sm-12">

Sass - Burger with Bootstrap 4 example

<nav class="navbar navbar-toggleable-md">
  <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#burger_with_Bootstrap_4_Example" aria-controls="burger_with_Bootstrap_4_Example" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"><a href="#" class="menu-button" id="menuButton">
    <span class="burger-icon"></span>
</a></span>
  </button>
  <a class="navbar-brand" href="/">Home</a>
  <div class="collapse navbar-collapse" id="burger_with_Bootstrap_4_Example">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Menu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Menu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Menu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Menu</a>
      </li>
    </ul>
  </div>
</nav>











<script>
var menuButton = document.getElementById('menuButton');
menuButton.addEventListener('click', function (e) {
    menuButton.classList.toggle('is-active');
    e.preventDefault();
});
</script>

</div>