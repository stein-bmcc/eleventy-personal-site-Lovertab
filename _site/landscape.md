title: Landscape
layout: base
tags:
  - great wall of China
  - postcard
  - lanscape
---
<article class="program-card">
          <img src="/images/landscape.png" alt="Landscape" class="img-responsive-specific">
          <div class="card-body">
            <h4>Postcard: Landscape of the Great Wall of China, 2022</h4>
            <p>This postcard was a project that I created through Adobe Illustrator. I chose the Great Wall of China because it is a place I want to vist. I used the pen tool and layers to recreate a look of the Great Wall of China. I looked at different typefaces and fonts to see which would look best with the type of landscape I picked. This font fit with the caligraphy writing style which fitted perfectly with the landscape.</p>
          </div>
        </article>
        <article>
  <div class="slideshow-container">

    <div class="mySlides fade">
      <img src="images/landscapeprocess.png" style="width:100%">
    </div>
    
    <div class="mySlides fade">
      <img src="images/landscapeprocess1.png" style="width:100%">
    </div>
    
    <div class="mySlides fade">
      <img src="images/landscapeprocess2.png" style="width:100%">
    </div>
    </div>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 3000); // Change image every 2 seconds
}
</script>
</article>