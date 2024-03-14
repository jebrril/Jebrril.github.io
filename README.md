<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CatLive</title>
    <style>
        /* Slide */
        * {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
        */
        /* Réinitialisation des styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Styles généraux */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            background-color: #fff;
            color: #663399;
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
            margin-top: 20px;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }

        main {
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        section {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 800px;
        }

        section h2 {
            color: #fff;
            font-size: 24px;
            margin-bottom: 10px;
            background-color: #663399;
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
        }

        section h2::after {
            content: " 🐱";
            font-size: 24px;
        }

        section p {
            color: #333;
            line-height: 1.6;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        .activation-links a {
            margin: 0 10px;
            color: #fff;
            text-decoration: none;
            font-size: 24px;
        }

        .activation-links a:hover {
            color: #ffcc00;
        }

        .review-bar {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .star {
            color: #ffcc00;
            font-size: 24px;
            margin: 0 2px;
        }
        .logo {
            position: absolute;
            top: 20px;
            left: 20px;
            z-index: 9999; /* Pour s'assurer que le logo reste au-dessus du contenu */
        }

        /* Ajustements de style pour le logo */
        .logo img {
            width: 150px; /* Taille du logo */
            height: auto; /* Hauteur ajustée automatiquement */
            border-radius: 50%; /* Forme du contour du logo */
            border: 3px solid #fff; /* Bordure blanche */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Ombre légère */
        }

    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="images/catlive18.jpg" alt="CatLive Logo">
        </div>
        
        <h1>How To Deal And Be Humanized With CATLIVE</h1>
        <nav>
            <ul>
                <li><a href="adoption.html">Adoption</a></li>
                <li><a href="food.html">Food</a></li>
                <li><a href="health.html">Health</a></li>
                <li><a href="education.html">Education</a></li>
                <li><a href="everyday_life.html">Everyday Life</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <div class="slideshow-container">

        <div class="mySlides fade">
          <div class="numbertext">1 / 3</div>
          <img src="images/catlive6.jpg" style="width:100%">
          <div class="text">Catlive</div>
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">2 / 3</div>
          <img src="images/catlive17.jpg" style="width:100%">
          <div class="text">Caption Two</div>
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">3 / 3</div>
          <img src="images/catlive12.jpg" style="width:100%">
          <div class="text">Caption Three</div>
        </div>
        
        <a class="prev" onclick="plusSlides(-1)">❮</a>
        <a class="next" onclick="plusSlides(1)">❯</a>
        
        </div>
        <br>
        
        <div style="text-align:center">
          <span class="dot" onclick="currentSlide(1)"></span> 
          <span class="dot" onclick="currentSlide(2)"></span> 
          <span class="dot" onclick="currentSlide(3)"></span> 
        </div>
    <main>
        <section id="introduction">
            <h2>Introduction</h2>
            <p>Welcome to "Catlive" your one-stop guide to the enchanting world of feline companions. Whether you're a passionate cat owner, considering adopting a cat, or just curious about these fascinating creatures, this document is designed to provide a comprehensive overview of all things cat-related.</p>
        </section>

        <section id="home">
            <h2>Share Your Passion for Cats</h2>
            <p>Discover the feline universe through Catlive Chat.</p>
            <img src="images/catlive1.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <!-- Other content elements -->
        </section>
<section id="table-of-contents">
            <h2>Table of Contents</h2>
            <ul>
                <li><a href="#history-of-cats">History of Cats</a></li>
                <li><a href="#popular-cat-breeds">Popular Cat Breeds</a></li>
                <li><a href="#cat-care-and-health">Cat Care and Health</a></li>
                <li><a href="#behavior-and-communication">Behavior and Communication</a></li>
                <li><a href="#feeding-and-nutrition">Feeding and Nutrition</a></li>
                <li><a href="#training-and-enrichment">Training and Enrichment</a></li>
                <li><a href="#fun-facts">Fun Facts</a></li>
                <li><a href="#resources">Resources</a></li>
            </ul>
        </section>

        <section id="History of Cats">
            <h2>History of Cats</h2>
            <img src="images/catlive2.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <p>Explore the captivating history of cats, from their ancient origins to their roles in various cultures. Learn about their evolution alongside humans and the enduring bond between cats and people.</p>
        </section>

        <section id="Popular Cat Breeds">
            <h2>Popular Cat Breeds</h2>
            <img src="images/catlive17.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <p>Discover the diversity of cat breeds, each with its own unique characteristics, temperament, and charm. Whether you prefer the sleek Siamese, the regal Persian, or the playful Bengal, find the perfect match for your lifestyle!</p>
        </section>

        <section id="Cat Care and Health">
            <h2>Cat Care and Health</h2>
            <img src="images/catlive4.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <p>Ensure the well-being of your feline companion with essential tips on cat care and health. From grooming and vaccinations to regular veterinary check-ups, this section covers everything you need to keep your cat happy and healthy.</p>
        </section>

        <section id="Behavior and Communication">
            <h2>Behavior and Communication</h2>
           <img src="images/catlive5.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <p>Decode the language of cats by understanding their behavior and communication cues. Explore the meaning behind different meows, purrs, and body language, fostering a deeper connection with your furry friend.</p>
        </section>

        <section id="Feeding and Nutrition">
            <h2>Feeding and Nutrition</h2>
           <img src="images/catlive6.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <p>Navigate the world of cat nutrition, from choosing the right cat food to understanding dietary requirements at different life stages. Learn about portion control, treats, and maintaining a balanced diet for optimal feline health.</p>
        </section>

        <section id="Training and Enrichment">
            <h2>Training and Enrichment</h2>
           <img src="images/catlive7.jpg" alt="Cat story"style="width: 650px;height: 490px;">
            <p>Discover effective training techniques and enrichment activities to stimulate your cat's mind and body. Whether teaching basic commands or providing engaging toys, enhance the quality of life for both you and your feline companion.</p>
        </section>

        <section id="Fun Facts">
            <h2>Fun Facts</h2>
            <p>Uncover intriguing and entertaining facts about cats that showcase their unique qualities and behaviors. From ancient superstitions to modern-day trivia, these fun facts celebrate the quirks and charms of our beloved cats.</p>
        </section>

        <section id="Resources">
    <h2>Resources</h2>
    <p>Explore additional resources for further information on cat care, behavior, and community:</p>
    <ul>
        <li><a href="https://catvets.com/">American Association of Feline Practitioners (AAFP)</a></li>
        <li><a href="https://cfa.org/kids/breeds-and-colors/cfa-breeds/">The Cat Fanciers' Association (CFA)</a></li>
        <li><a href="https://catcaresociety.org/">Cat Care Society</a></li>
        <li><a href="https://www.nationalgeographic.com/animals/mammals/facts/domestic-cat">National Geographic's Cats: Everything You Need to Know</a></li>
    </ul>
</section>

        <div class="review-bar">
            <span class="star">&#9733;</span>
            <span class="star">&#9733;</span>
            <span class="star">&#9733;</span>
            <span class="star">&#9733;</span>
            <span class="star">&#9733;</span>
        </div>
</main>

    <footer>
        <div class="activation-links">
            <p> Useful links</p>
            <a href="https://www.facebook.com/people/Cat-Ferlive/pfbid0BdmEDU352LKqiFBYQrW5zzyQsF18MJd2dpREAuuG2qNqA2HmZxmCKz5887y6x82Rl/">Facebook</a>
            <a href="https://www.instagram.com/catlive889/">Instagram</a>
            <a href="https://www.youtube.com/@josef-jebril">Youtube</a>
        </div>
        <p>TEL +212 0666812087 +212 0687004842 ---🐱--- catlive889@gmail.com</p>
        <p>&copy; 2024 CatLive</p>
    </footer>

    <script>
        let slideIndex = 1;
        showSlides(slideIndex);
        
        function plusSlides(n) {
          showSlides(slideIndex += n);
        }
        
        function currentSlide(n) {
          showSlides(slideIndex = n);
        }
        
        function showSlides(n) {
          let i;
          let slides = document.getElementsByClassName("mySlides");
          let dots = document.getElementsByClassName("dot");
          if (n > slides.length) {slideIndex = 1}    
          if (n < 1) {slideIndex = slides.length}
          for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";  
          }
          for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
          }
          slides[slideIndex-1].style.display = "block";  
          dots[slideIndex-1].className += " active";
        }
        </script>
</body> 
