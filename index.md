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
             <p>Hi 👋🏻 I am a PhD student working with Dr. <a class="link" href="Laval"><span class="wavy" data-content="Jorge Laval">Jorge Laval</span></a> at the <a href="GT">Georgia Institute of Technology</a> 🐝. </p>
              <p>My research focuses on <a href="#"><code>Traffic Flow</code></a>, <a href="#"><code>Self-driving</code></a>, <a href="#"><code>Car-following</code></a>, and <a href="#"><code>MFD</code></a>. A complete CV is available <a class="link" href="#"><span class= "dashed" data-content="here">here</span></a>. </p>
              <p> WIP with my website 🚧. </p>
          </div> 
    </div>
  </body>
</html>

<br>
<br>
<br>
<br> 


<html>
<h2> Education </h2>
<ul class="ul-edu fa-ul"> 
    <li>
      <i class="fa-li fas fa-carrot" style="color: #919191;"></i>
      <div class="description">
        <p class="course">Ph.D. in Civil and Environmental Engineering, (2021 ~ )</p>
        <p class="institution">Georgia Institute of Technology</p>
      </div>
    </li>

   <li>
      <i class="fa-li fa fa-graduation-cap" style="color: #919191;"></i>
      <div class="description">
        <p class="course">M.S. in Civil and Environmental Engineering, (2019 ~ 2021) </p>
        <p class="institution">Seoul National University, South Korea</p>
      </div>
    </li>
    <li>
      <i class="fa-li fa fa-graduation-cap" style="color: #919191;"></i>
      <div class="description">
        <p class="course">B.S. in Civil and Environmental Engineering, (2015 ~ 2019) </p>
        <p class="institution">Seoul National University, South Korea</p>
      </div>
    </li>
</ul>


</html>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-Q76TKS2GKN"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-Q76TKS2GKN');
</script>

