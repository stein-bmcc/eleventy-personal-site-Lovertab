title: Design Patterns
layout: base
tags:
  - patterns
  - graphic design
  - images
---
<main id="designpatterns">
        <div>
          <h1>Design Patterns, 2022, Adobe Illustrator</h1>
          <p>For this assignment, I had to create a logo design with my initials and use it to illustrate different design patterns (see below).<p></p>
        </div>
          <article>
            <div class="slideshow-container">
              <div class="mySlides fade">
                <figure><img src="/images/symmerty.png" alt="Symmerty" style="width:100%" class="img-responsive"> <figcaption class="captions">Symmerty</figcaption></figure>
              </div>
              
              <div class="mySlides fade">
                <figure><img src="/images/rhythm.png" alt="Rhythm" style="width:100%" class="img-responsive"> <figcaption class="captions">Rhythm</figcaption></figure>
              </div>
              
              <div class="mySlides fade">
                <figure><img src="/images/repetition.png" alt="Repetition" style="width:100%" class="img-responsive"> <figcaption class="captions">Repetition</figcaption></figure>
              </div>

              <div class="mySlides fade">
                <figure><img src="/images/contrast.png" alt="Contrast" style="width:100%" class="img-responsive"> <figcaption class="captions">Contrast</figcaption></figure>
              </div>

              <div class="mySlides fade">
                <figure><img src="/images/proximity.png" alt="Proximity" style="width:100%" class="img-responsive"> <figcaption class="captions">Proximity</figcaption></figure>
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