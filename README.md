<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Explore The World</title>
  <link rel="stylesheet" href="travel.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">

</head>
<body>
  <header>
     <div class="dropdown">
    <button onclick="toggleDropdown()" class="dropdown-btn">Menu</button>
    <div id="myDropdown" class="dropdown-content">
      <a href="travel.html">Home</a>
      <a href="About.html">About</a>
      <a href="service.html">Services</a>
      <a href="contact.html">Contact</a>
    </div>
  </div>
    <div class="slider">
        <div class="slide">
            <img class="image1" src="skardu-visit.jpg"  width="100%" >
            <img class="image1" src="Nagar-valley-e1651487264247.jpg"  width="100%" height="300px" >
            <img class="image1" src="Dubai-to-Skardu.png" width="100%" height="300px">
            <img class="image1" src="istockphoto-1684364300-612x612.jpg" width="100%"  height="300px">
        </div>
    </div>
    <div class="hero">
      <h1>EXPLORE THE PAKISTAN WITH US</h1>
      <p>YOUR ADVENTURE BEGINS HERE</p>
      <a href="booking" class="btn" >📅 Book Now</a>
    </div>
     <!-- <button class="prev" onclick="prevbtn()">&#10094</button>
        <button class="next" onclick="nextbtn()">&#10095</button>  -->
  </header>

  <section class="destinations"> 
    <h2>POPULAR DESTINATIONS</h2>
    <div class="cards">
      <div class="card">
        <img src="gilgit.jpeg" alt="Dubai">
        <h3>GILGIT</h3>
        <a href="https://en.wikipedia.org/wiki/Gilgit" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="Dubai-to-Skardu.png" alt="GilGit Baltistan">
        <h3>SKARDU</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="istockphoto-1684364300-612x612.jpg" alt="GilGit Baltistan">
        <h3>HUNZA</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="Golden-Peak..jpg" alt="GilGit Baltistan">
        <h3>NAGER</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="diamer.jpeg" alt="GilGit Baltistan">
        <h3>DIAMER</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
    </div>
    <div class="cardsi">
      <div class="card">
        <img src="skardu-visit.jpg" alt="Dubai">
        <h3>ASTORE</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="ghizer12.jpg" alt="GilGit Baltistan">
        <h3>GHIZER</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="shiger.jpeg" alt="GilGit Baltistan">
        <h3>SHIGAR</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="ganche.jpg" alt="GilGit Baltistan">
        <h3>GHANCHE</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
      <div class="card">
        <img src="kharmang.webp" alt="GilGit Baltistan">
        <h3>KHARMANG</h3>
        <a href="#book" class="btn">Book Now</a>
      </div>
    </div>
  </section>
  <section id="book" class="booking">
    <h2>Book Your Trip</h2>
    <form>
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email Address" required />
      <input type="date" required />
      <button type="submit">Submit Booking</button>
    </form>
  </section>
  <footer>
        <div class="foot-cont">
            <div class="product">
                <h3>Product</h3>
                <p>Pricing</p>
                <p>Start Your Business</p>
                <p>Manage Your Corporation</p>
                <p>Professional Partners</p>
                <p>Ownr Shares</p>
            </div>
            <div class="product" style="width: 11%;">
                <h3>Resources</h3>
                <p>RBC Offer Details</p>
                <p>Perks</p>
                <p>Business Guides</p>
                <p>Blog</p>
            </div>
            <div class="product" style="width: 6%;">
                <h3>Company</h3>
                <p>About</p>
                <p>Partners</p>
                <p>Affiliates</p>
                <p>Careers</p>
                <p>Security</p>
                <p>Reviews</p>
                <p>Press</p>
            </div>
            <div class="product" style="width: 7%;">
                <h3>Support</h3>
                <p>Live Chat</p>
                <p>Email Us</p>
                <p>Help Centre</p>
            </div>
            <div class="logoo">
                <img src="logo2.png" alt="" width="100px">
            </div>
        </div>
        <hr class="tag">
        <div class="privacy">
            <div class="legal">
                <p>Ownr™ is not a law firm and does not provide legal advice or legal services. We provide self-help
                    services at your specific direction.
                </p>
                <p class="RBC">RBC Ventures Inc. Website, ©2024</p>
                <div class="term-and-condition">
                    <p>Legal   | Privacy & Policy   | Accessbility   | Terms & Conditions</p>
                </div>
            </div>
            <div class="footer-icons">
                <select name="language" id="lang">
                    <option>English</option>
                    <option>Urdu</option>
                    <option>Arabic</option>
                    <option>Parsia</option>  
                </select>
                <div class="insta">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-instagram"></i>
                    <i class="fa-brands fa-x-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
            </div>
        </div>
    </footer> 
    
    <p>© 2025 Travel Agency | All rights reserved</p>
  </footer>
  <script src="travel.js"></script>
</body>
</html>
