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

The following slideshow containing reproductions of the piecewise fittings to the logarithmic Alpha characteristics. These have been separated for improved clarity, and can be scrolled through with the arrows at each side of the image.

<!-- Slideshow container -->
<div class="slideshow-container">

 <!-- Full-width images with number and caption text -->
  <div class="plotSlideshow">
    <div class="text">(1/6) Alpha logarithmic characteristic 05A.</div>
    <img src="../images/meas_characteristics/log1.png" style="width:100%">
  </div>

  <div class="plotSlideshow">
    <div class="text">(2/6) Alpha logarithmic characteristic 10A.</div>
    <img src="../images/meas_characteristics/log2.png" style="width:100%">

  </div>

  <div class="plotSlideshow">
    <div class="text">(3/6) Alpha logarithmic characteristic 15A.</div>
    <img src="../images/meas_characteristics/log3.png" style="width:100%">
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

## Transitional values of piecewise function for logarithmic characteristics

The corresponding transitional values for these functions are shown in the below table.

<div style="overflow-x:auto;">
  <table>
    <caption><span data-label="table:"><em>Optimised transition points of the general cubic-linear piecewise function, fit to measured logarithmic potentiometer characteristics. Values are rounded to 3 decimal places.</em></span></caption>
    <tbody>
      <tr class="even">
        <td align="left"></td>
        <th colspan="2">1</th>
        <th colspan="2">2</th>
        <th colspan="2">3</th>
      </tr>
      <tr class="border">
        <td align="left"></td>
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
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
        <td align="left">0.071</td>
        <td align="left">0.005</td>
        <td align="left">0.119</td>
        <td align="left">0.008</td>
        <td align="left">0.000</td>
        <td align="left">0.000</td>
      </tr>
      <tr class="even">
        <td align="left">Cub.</td>
        <td align="left">0.239</td>
        <td align="left">0.045</td>
        <td align="left">0.339</td>
        <td align="left">0.080</td>
        <td align="left">0.285</td>
        <td align="left">0.053</td>
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
        <td align="left">0.603</td>
        <td align="left">0.215</td>
        <td align="left">0.553</td>
        <td align="left">0.188</td>
        <td align="left">0.598</td>
        <td align="left">0.199</td>
      </tr>
      <tr class="even">
        <td align="left">Cub.</td>
        <td align="left">0.659</td>
        <td align="left">0.368</td>
        <td align="left">0.670</td>
        <td align="left">0.328</td>
        <td align="left">0.669</td>
        <td align="left">0.349</td>
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
        <td align="left">0.850</td>
        <td align="left">0.939</td>
        <td align="left">0.904</td>
        <td align="left">0.980</td>
        <td align="left">0.869</td>
        <td align="left">0.941</td>
      </tr>
      <tr class="even">
        <td align="left">Cub.</td>
        <td align="left">0.908</td>
        <td align="left">0.997</td>
        <td align="left">0.950</td>
        <td align="left">1.000</td>
        <td align="left">0.924</td>
        <td align="left">0.997</td>
      </tr>
      <tr class="odd">
        <td align="left">Lin.</td>
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
