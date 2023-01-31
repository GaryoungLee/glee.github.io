---
layout: page
full_logo: true
title: 
subtitle:
description: Garyoung's website
sitemap:
  priority: 1.0
---

<html>
  <head>
    <style>
      .container {
        display: flex;
        align-items: left;
      }
      .image {
        max-width: 40%;
        height: auto;
      }
      .text {
        margin-left: 20px;
      }

      /* Add media query */
      @media (max-width: 767px) {
        .container {
          flex-direction: column;
        }
        .text {
          margin-left: 0;
          margin-top: 20px;
        }
         .image {
          max-width: 100%;
        }
      }
    </style>
  </head>
  <body>
    <div class="container">
      <img class="image" src="assets/img/headshot_lightgreen-03.png">
      <div class="text">
             <p class="describe-text">Hi 👋🏻 I am a PhD student working with <a href="#">Dr. Jorge Laval</a> at the <a href="#">Georgia Institute of     Technology</a> 🐝. </p>
              <p> My research focuses on <a href="#"><code>Traffic Flow</code></a>, <a href="#"><code>Multimodal Freight Distribution</code></a>, <a href="#"><code>Car-following</code></a>, and <a href="#"><code>Self-driving</code></a>. A complete CV is available <a href="#">here</a>. </p>
              <p> I am still WIP with my website. </p>
          </div> 
    </div>
  </body>




<h2> Education </h2>
<ul class="ul-edu fa-ul"> 
    <li>
      <i class="fa-li fa fa-graduation-cap"></i>
      <div class="description">
        <p class="course">Ph.D. in Civil and Environmental Engineering, <em> 2021 Fall - in progress </em></p>
        <p class="institution">Georgia Institute of Technology</p>
      </div>
    </li>

   <li>
      <i class="fa-li fa fa-graduation-cap"></i>
      <div class="description">
        <p class="course">M.S. in Civil and Environmental Engineering, <em>2019 - 2021</em> </p>
        <p class="institution">Seoul National University, South Korea</p>
      </div>
    </li>
    <li>
      <i class="fa-li fa fa-graduation-cap"></i>
      <div class="description">
        <p class="course">B.S. in Civil and Environmental Engineering, <em>2015 - 2019 </em> </p>
        <p class="institution">Seoul National University, South Korea</p>
      </div>
    </li>
</ul>

</html>



