---
layout: default
title: "Modelling specified linear Alpha characteristics"
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

# Modelling specified linear Alpha characteristics

## Fit to linear Alpha characteristics

The following slideshow containing reproductions of the piecewise fittings to the linear Alpha characteristics. These have been separated for improved clarity, and can be scrolled through with the arrows at each side of the image.

<!-- Slideshow container -->
<div class="slideshow-container">

 <!-- Full-width images with number and caption text -->
  <div class="plotSlideshow">
    <div class="text">(1/6) Alpha linear characteristic B.</div>
    <img src="../images/spec_characteristics/alpha_lin_B.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(2/6) Alpha linear characteristic 1B.</div>
    <img src="../images/spec_characteristics/alpha_lin_1B.png" style="width:100%">

  </div>

  <div class="plotSlideshow">
    <div class="text">(3/6) Alpha linear characteristic 2B.</div>
    <img src="../images/spec_characteristics/alpha_lin_2B.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(4/6) Alpha linear characteristic 3B.</div>
    <img src="../images/spec_characteristics/alpha_lin_3B.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(5/6) Alpha linear characteristic 4B.</div>
    <img src="../images/spec_characteristics/alpha_lin_4B.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(6/6) Alpha linear characteristic 5B.</div>
    <img src="../images/spec_characteristics/alpha_lin_5B.png" style="width:100%">
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
    <caption><span data-label="table:"><em>Optimised transition points of the general cubic-linear piecewise function, fit to the linear potentiometer characteristic specified on the Alpha website. Values are rounded to 3 decimal places.</em></span></caption>
    <tbody>
      <tr class="even">
        <td align="left"></td>
        <th colspan="2">B</th>
        <th colspan="2">1B</th>
        <th colspan="2">2B</th>
        <th colspan="2">3B</th>
        <th colspan="2">4B</th>
        <th colspan="2">5B</th>
      </tr>
      <tr class="border">
        <td align="left"></td>
        <td align="left"><span class="math inline"><em>x</em></span></td>
        <td align="left"><span class="math inline"><em>y</em></span></td>
        <td align="left"><span class="math inline"><em>x</em></span></td>
        <td align="left"><span class="math inline"><em>y</em></span></td>
        <td align="left"><span class="math inline"><em>x</em></span></td>
        <td align="left"><span class="math inline"><em>y</em></span></td>
        <td align="left"><span class="math inline"><em>x</em></span></td>
        <td align="left"><span class="math inline"><em>y</em></span></td>
        <td align="left"><span class="math inline"><em>x</em></span></td>
        <td align="left"><span class="math inline"><em>y</em></span></td>
        <td align="left"><span class="math inline"><em>x</em></span></td>
        <td align="left"><span class="math inline"><em>y</em></span></td>
      </tr>
      <tr class="even">
        <td align="left">-</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
        <td align="left">0.050</td>
        <td align="left">0.000</td>
        <td align="left">0.055</td>
        <td align="left">0.000</td>
        <td align="left">0.113</td>
        <td align="left">0.006</td>
        <td align="left">0.163</td>
        <td align="left">0.018</td>
        <td align="left">0.155</td>
        <td align="left">0.032</td>
        <td align="left">0.296</td>
        <td align="left">0.032</td>
      </tr>
      <tr class="even">
        <td align="left">Cub.</td>
        <td align="left">0.125</td>
        <td align="left">0.071</td>
        <td align="left">0.294</td>
        <td align="left">0.231</td>
        <td align="left">0.352</td>
        <td align="left">0.283</td>
        <td align="left">0.457</td>
        <td align="left">0.433</td>
        <td align="left">0.415</td>
        <td align="left">0.296</td>
        <td align="left">0.420</td>
        <td align="left">0.198</td>
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
        <td align="left">0.932</td>
        <td align="left">0.997</td>
        <td align="left">0.763</td>
        <td align="left">0.863</td>
        <td align="left">0.741</td>
        <td align="left">0.877</td>
        <td align="left">0.661</td>
        <td align="left">0.816</td>
        <td align="left">0.574</td>
        <td align="left">0.719</td>
        <td align="left">0.565</td>
        <td align="left">0.803</td>
      </tr>
      <tr class="even">
        <td align="left">Cub.</td>
        <td align="left">0.935</td>
        <td align="left">0.998</td>
        <td align="left">0.921</td>
        <td align="left">0.996</td>
        <td align="left">0.955</td>
        <td align="left">0.999</td>
        <td align="left">0.931</td>
        <td align="left">0.997</td>
        <td align="left">0.795</td>
        <td align="left">0.958</td>
        <td align="left">0.699</td>
        <td align="left">0.973</td>
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
        <td align="left">1.000</td>
        <td align="left">1.000</td>
        <td align="left">1.000</td>
        <td align="left">1.000</td>
        <td align="left">1.000</td>
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
