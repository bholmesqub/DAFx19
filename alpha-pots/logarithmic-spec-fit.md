---
layout: default
title: "Modelling specified logarithmic Alpha characteristics"
---

<!-- Javascript for slideshow-->
<script>
  var slideIndex = 1;

  showSlides(1);
  showSlides(1);

  // Next/previous controls
  function plusSlides(n) {
    slideIndex += n;
    showSlides(slideIndex);
  }

  // Thumbnail image controls
  function currentSlide() {
    slideIndex = n;
    showSlides(slideIndex);
  }

  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("plotSlideshow");
    var dots = document.getElementsByClassName("dot");

    if (n > slides.length) {
      slideIndex = 1;
    } else if (n < 1) {
      slideIndex = slides.length;
    }

    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
    }


    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }

    if(slides.length > 0){
      slides[slideIndex-1].style.display = "block";
      dots[slideIndex-1].className += " active";
    }
  }
  window.onload = function() {
    showSlides(1);
    showSlides(1);
  };
</script>

# Modelling specified logarithmic Alpha characteristics

## Fit to logarithmic Alpha characteristics

The following slideshow containing reproductions of the piecewise fittings to measured logarithmic Alpha characteristics.

<!-- Slideshow container -->
<div class="slideshow-container">

 <!-- Full-width images with number and caption text -->
  <div class="plotSlideshow">
    <div class="text">(1/6) Alpha logarithmic characteristic 05A.</div>
    <img src="../images/spec_characteristics/alpha_log_05A.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(2/6) Alpha logarithmic characteristic 10A.</div>
    <img src="../images/spec_characteristics/alpha_log_10A.png" style="width:100%">

  </div>

  <div class="plotSlideshow">
    <div class="text">(3/6) Alpha logarithmic characteristic 15A.</div>
    <img src="../images/spec_characteristics/alpha_log_15A.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(4/6) Alpha logarithmic characteristic 20A.</div>
    <img src="../images/spec_characteristics/alpha_log_20A.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(5/6) Alpha logarithmic characteristic 25A(K).</div>
    <img src="../images/spec_characteristics/alpha_log_25A(K).png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(6/6) Alpha logarithmic characteristic 30A.</div>
    <img src="../images/spec_characteristics/alpha_log_30A.png" style="width:100%">
  </div>

 <!-- Next and previous buttons -->
 <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
 <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
 <span class="dot" onclick="currentSlide(1)"></span>
 <span class="dot" onclick="currentSlide(2)"></span>
 <span class="dot" onclick="currentSlide(3)"></span>
 <span class="dot" onclick="currentSlide(4)"></span>
 <span class="dot" onclick="currentSlide(5)"></span>
 <span class="dot" onclick="currentSlide(6)"></span>
</div>

## Transitional values of piecewise function for linear characteristics

The corresponding transitional values for these functions are shown in the below table.

<div style="overflow-x:auto;">
  <table>
    <caption><span data-label="table:"><em>Optimised transition points of the general cubic-linear piecewise function, fit to the logarithmic potentiometer characteristic specified on the Alpha website. Values are rounded to 3 decimal places.</em></span></caption>
    <tbody>
      <tr class="even">
      <td align="left"></td>
      <th></th>
      <th>05A</th>
      <th>10A</th>
      <th>15A</th>
      <th>20A</th>
      <th>25A(K)</th>
      <th>30A</th>
      </tr>
      <tr class="border">
      <td align="left"></td>
      <td align="left"><span class="math inline"><em>x</em></span></td>
      <td align="left"><span class="math inline"><em>y</em></span></td>
      <td align="left"><span class="math inline"><em>y</em></span></td>
      <td align="left"><span class="math inline"><em>y</em></span></td>
      <td align="left"><span class="math inline"><em>y</em></span></td>
      <td align="left"><span class="math inline"><em>y</em></span></td>
      <td align="left"><span class="math inline"><em>y</em></span></td>
      </tr>
      <tr class="odd">
      <td align="left">-</td>
      <td align="left">0.000</td>
      <td align="left">0.000</td>
      <td align="left">0.000</td>
      <td align="left">0.000</td>
      <td align="left">0.000</td>
      <td align="left">0.000</td>
      <td align="left">0.000</td>
      </tr>
      <tr class="even">
      <td align="left">Lin.</td>
      <td align="left">0.050</td>
      <td align="left">0.003</td>
      <td align="left">0.003</td>
      <td align="left">0.003</td>
      <td align="left">0.004</td>
      <td align="left">0.002</td>
      <td align="left">0.004</td>
      </tr>
      <tr class="odd">
      <td align="left">Cub.</td>
      <td align="left">0.300</td>
      <td align="left">0.015</td>
      <td align="left">0.028</td>
      <td align="left">0.063</td>
      <td align="left">0.084</td>
      <td align="left">0.123</td>
      <td align="left">0.151</td>
      </tr>
      <tr class="even">
      <td align="left">Lin.</td>
      <td align="left">0.510</td>
      <td align="left">0.057</td>
      <td align="left">0.111</td>
      <td align="left">0.162</td>
      <td align="left">0.210</td>
      <td align="left">0.259</td>
      <td align="left">0.311</td>
      </tr>
      <tr class="odd">
      <td align="left">Cub.</td>
      <td align="left">0.700</td>
      <td align="left">0.284</td>
      <td align="left">0.363</td>
      <td align="left">0.410</td>
      <td align="left">0.443</td>
      <td align="left">0.501</td>
      <td align="left">0.542</td>
      </tr>
      <tr class="even">
      <td align="left">Lin.</td>
      <td align="left">0.920</td>
      <td align="left">0.954</td>
      <td align="left">0.959</td>
      <td align="left">0.958</td>
      <td align="left">0.952</td>
      <td align="left">0.954</td>
      <td align="left">0.965</td>
      </tr>
      <tr class="odd">
      <td align="left">Cub.</td>
      <td align="left">0.970</td>
      <td align="left">0.999</td>
      <td align="left">0.999</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      <td align="left">0.999</td>
      <td align="left">1.000</td>
      </tr>
      <tr class="even">
      <td align="left">Lin.</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      <td align="left">1.000</td>
      </tr>
    </tbody>
  </table>
</div>
