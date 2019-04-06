---
layout: default
title: "Modelling measured linear Alpha characteristics"
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

# Modelling measured linear Alpha characteristics

## Fit to linear Alpha characteristics

The following slideshow containing reproductions of the piecewise fittings to measured linear Alpha characteristics.

<!-- Slideshow container -->
<div class="slideshow-container">

 <!-- Full-width images with number and caption text -->
  <div class="plotSlideshow">
    <div class="text">(1/3) Measured Alpha linear characteristic.</div>
    <img src="../images/meas_characteristics/lin1.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(2/3) Measured Alpha linear characteristic.</div>
    <img src="../images/meas_characteristics/lin2_1.png" style="width:100%">

  </div>

  <div class="plotSlideshow">
    <div class="text">(3/3) Measured Alpha linear characteristic.</div>
    <img src="../images/meas_characteristics/lin3.png" style="width:100%">
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
</div>

## Transitional values of piecewise function for linear characteristics

The corresponding transitional values for these functions are shown in the below table.

<div style="overflow-x:auto;">
  <table>
    <caption><span data-label="table:"><em>Optimised transition points of the general cubic-linear piecewise function, fit to the linear potentiometer characteristic measured directly from Alpha potentiometers. Values are rounded to 3 decimal places.</em></span></caption>
    <tbody>
      <tr class="even">
        <td align="left"></td>
        <th colspan="2">1</th>
        <th colspan="2">2</th>
        <th colspan="2">3</th>
      </tr>
      <tr class="odd">
      <td align="right"></td>
      <td align="right"><span class="math inline"><em>x</em></span></td>
      <td align="right"><span class="math inline"><em>y</em></span></td>
      <td align="right"><span class="math inline"><em>x</em></span></td>
      <td align="right"><span class="math inline"><em>y</em></span></td>
      <td align="right"><span class="math inline"><em>x</em></span></td>
      <td align="right"><span class="math inline"><em>y</em></span></td>
      </tr>
      <tr class="even">
      <td align="left">-</td>
      <td align="right">0.000</td>
      <td align="right">0.000</td>
      <td align="right">0.000</td>
      <td align="right">0.000</td>
      <td align="right">0.000</td>
      <td align="right">0.000</td>
      </tr>
      <tr class="odd">
      <td align="left">Lin.</td>
      <td align="right">0.109</td>
      <td align="right">0.112</td>
      <td align="right">0.076</td>
      <td align="right">0.028</td>
      <td align="right">0.050</td>
      <td align="right">0.000</td>
      </tr>
      <tr class="even">
      <td align="left">Cub.</td>
      <td align="right">0.389</td>
      <td align="right">0.429</td>
      <td align="right">0.189</td>
      <td align="right">0.187</td>
      <td align="right">0.093</td>
      <td align="right">0.041</td>
      </tr>
      <tr class="odd">
      <td align="left">Lin.</td>
      <td align="right">0.814</td>
      <td align="right">0.871</td>
      <td align="right">0.785</td>
      <td align="right">0.825</td>
      <td align="right">0.951</td>
      <td align="right">1.000</td>
      </tr>
      <tr class="even">
      <td align="left">Cub.</td>
      <td align="right">0.946</td>
      <td align="right">1.000</td>
      <td align="right">0.944</td>
      <td align="right">0.999</td>
      <td align="right">0.951</td>
      <td align="right">1.000</td>
      </tr>
      <tr class="odd">
      <td align="left">Lin.</td>
      <td align="right">1.000</td>
      <td align="right">1.000</td>
      <td align="right">1.000</td>
      <td align="right">1.000</td>
      <td align="right">1.000</td>
      <td align="right">1.000</td>
      </tr>
    </tbody>
  </table>
</div>
