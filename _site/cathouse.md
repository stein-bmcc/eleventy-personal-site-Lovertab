title: Cat and House
layout: base
tags:
  - cat
  - house
  - adobe illustrator
---
<main id="cathouse">
        <article class="program-card">
          <img src="/images/catandhouse.png" alt="Cat and House" class="img-responsive-specific">
          <div class="card-body">
            <h4>Cat and House Design, 2022, Adobe Illustrator</h4>
            <p>This was my first design created in Adobe Illustrator.  I wanted to use something that had more primitive shapes that would be easy to recreate since I wanted to get used to the different tools available in the software. I used the pen tool to create the sun and clouds and the ground, while I used the shape tool to create the house and the cat shape. The goal of this project was to get accustomed to the options and tools available in Illustrator.</p>
          </div>
        </article>
        <article>
          <div class="slideshow-container">
        
            <div class="mySlides fade">
              <img src="images/cathouse1.png" style="width:100%">
            </div>
            
            <div class="mySlides fade">
              <img src="images/cathouse2.png" style="width:100%">
            </div>
            
            <div class="mySlides fade">
              <img src="images/cathouse3.png" style="width:100%">
            </div>

            <div class="mySlides fade">
              <img src="images/cathouse4.png" style="width:100%">
            </div>

            <div class="mySlides fade">
              <img src="images/cathouse5.png" style="width:100%">
            </div>
            </div>
        
        <div style="text-align:center">
          <span class="dot"></span> 
          <span class="dot"></span> 
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
</main>
