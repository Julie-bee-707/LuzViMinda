<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="UTF-8">
    <title>Business website</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://www.w3schools.com/lib/w3-colors-highway.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>

      <div class="navigation w3-highway-blue w3-container">
        <nav class="nav-container w3-padding-large">
          <div class="logo">
            <a href="#home" >LUZVIMINDA<span>JOURNEYS</span></a>
          </div>
          <div class="mobile-button">
            <span style="float: right;" onclick="toggleMobileNavigation()">&#9776;</span>
          </div>
          <div class="links">
            <a href="#about" >About</a>
            <a href="#services" >Services</a>
            <a href="#contact" >Contact</a>            
          </div>
          <div id="mobile-sidenav" class="mobile-links w3-highway-blue">
            <div class="mobile-logo" style="display: inline;">
              <a href="#home" class="logo">LUZVIMINDA<span>JOURNEYS</span></a>
              <span style="width: 100%;"></span>
              <a href="javascript:void(0)" class="closebtn" onclick="toggleMobileNavigation()">&times;</a>
            </div>
            <a href="#about" onclick="toggleMobileNavigation()">About Us</a>
            <a href="#services" onclick="toggleMobileNavigation()">Services</a>
            <a href="#contact" onclick="toggleMobileNavigation()">Contact</a>
          </div>
        </nav>
      </div>

      <div class="hero" id="home">
        <div class="text container">
          <p class="pre-title">Welcome to</p>
          <h1 class="title"> LUZVIMINDA<span>JOURNEYS</span></h1>
          <p class="post-title">Your Ticket To Discover 7,641 Islands!</p>
          <a class="w3-button w3-round-large w3-indigo w3-hover-blue" href="#services">OUR SERVICES</a> 
        </div>
      </div>

      <div class="about container w3-padding-large" id="about">
        <div class="text-one">
          <h2>About Us</h2>
          <p>LuzViMinda Journeys offers domestic tours around the Philippines, being the best option for those seeking tours
             that align with their preferences and provide unexpected experiences. It serves as the passport to the Filipino paradise, 
             offering travelers a chance to escape and appreciate the diverse destinations here in the Philippines. With the growing trend
              of travel as a lifestyle, we are expanding our offerings to include highly-requested trip packages and special event arrangements.</p> 
        </div>
        <div class="text-one">
          <h2>Our Vision</h2>
          <p>By 2030, LuzViMinda Journeys will be one of the most trusted travel agencies and the go - to choice for travelers and act
             as a bridge between clients and their dream destinations here in the Philippines, facilitating memorable and satisfying 
             travel experiences that will resonate for a lifetime.</p>
      </div>
        <div class="text-one">
          <h2>Our Mission</h2>
          <p>Provide travelers with authentic and unforgettable experiences that celebrate the diverse cultures,
             stunning landscapes while promoting sustainable tourism practices that preserve and protect our rich,
              nature and cultural heritage of the Philippines..</p>
      </div>
       

      <div class="services container" id="services">
        <h2 class="w3-center">Our Services</h2>
        <div class="cards w3-padding-large w3-margin-top">
          <div class="card w3-card-2 w3-padding-large w3-border w3-border-blue w3-round-large">
            <h3>PASSPORT PROCESSING</h3>
            <div class="card-text">
              <p>Hassle-free assistance in securing new passports or renewing existing ones, ensuring smooth and timely processing.</p>
            </div>
          </div>
          <div class="card w3-card-2 w3-padding-large w3-border w3-border-blue w3-round-large">
            <h3>AIRLINE TICKETING</h3>
            <div class="card-text">
              <p>Convenient booking of domestic flights at competitive rates, tailored to your preferred schedule and budget.</p>
            </div>
          </div>
          <div class="card w3-card-2 w3-padding-large w3-border w3-border-blue w3-round-large">
            <h3>TRANSPORTATION SERVICES</h3>
            <div class="card-text">
              <p>Reliable and comfortable transport solutions, including airport transfers and private rentals.</p>
            </div>
          </div>
          <div class="card w3-card-2 w3-padding-large w3-border w3-border-blue w3-round-large">
            <h3>PERSONALIZED TOUR</h3>
            <div class="card-text">
              <p>Custom-made itineraries designed to match your interests and schedule, providing unique and memorable travel experiences.</p>
        </div>
      </div>

      <div class="contact container" id="contact">
        <div class="short-contact">
            <h2>Contact us</h2>
          <p class="w3-xlarge">We would like to hear from you!</p>
          <div class="w3-large w3-margin-top contact-info">
            <i class="fa fa-location-arrow"></i><span style="margin-left:10px;"><a href="https://www.google.com/maps/place/MTS+BUILDING/@13.9367134,121.6071593,17z/data=!3m1!4b1!4m6!3m5!1s0x33bd4bb06b5532f3:0x39862f6ea49b343a!8m2!3d13.9367082!4d121.6097342!16s%2Fg%2F11sv2yltzd!5m1!1e2?entry=ttu&g_ep=EgoyMDI1MDkxMC4wIKXMDSoASAFQAw%3D%3D">3rd Floor MTS Building M.I Tagarao St. Lucena City</a></span><br>
            <i class="fa fa-envelope-o"></i><span style="margin-left:10px;"><a href="luzviminda.journeys@gmail.com">luzviminda.journeys@gmail.com</a></span><br>
            <i class="fa fa-phone"></i><span style="margin-left:10px;"><a href="+63 995-415-9041">+63 995-415-9041</a></span><br>
          <div class="w3-large w3-margin-top contact-info">
            <i class="fa fa-instagram"></i><span style="margin-left:10px;"><a href="https://www.instagram.com/juyanmais/">- luzvimindajourneys</a></span><br>
            <i class="fa fa-facebook"></i><span style="margin-left:10px;"><a href="https://www.facebook.com/juliane.venerayan?mibextid=wwXIfr&mibextid=wwXIfr"> - LuzViMinda Journeys</a></span><br>
            <i class="fa fa-music"></i><span style="margin-left:10px;"><a href="https://www.tiktok.com/@juliebee_jj?_r=1&_d=secCgYIASAHKAESPgo8GPgjM2dH6Nvu20q94gBQJJiCRaUTD8QvRmWtEUXRcgxH27kDW5IowFskilp4pHELed2pysnB0tP%2B8sJoGgA%3D&_svg=1&checksum=f78925ce69e4f32222fefbdfa2e6e5dc7601db88ebf1413a56622cb86abc1114&item_author_type=1&sec_uid=MS4wLjABAAAAN8nTjcual1Yqzq6Dr6SBFlmLqAdc0mM5FMlPbRQe06CTzV4iyucRCIwsMB4MloYR&sec_user_id=MS4wLjABAAAAN8nTjcual1Yqzq6Dr6SBFlmLqAdc0mM5FMlPbRQe06CTzV4iyucRCIwsMB4MloYR&share_app_id=1180&share_author_id=7434930569061090359&share_link_id=046628E8-2A73-490B-AC76-DF11BDC2111F&share_scene=1&sharer_language=en&social_share_type=4&source=h5_t&timestamp=1757728433&tt_from=copy&u_code=eh63he9d1625c2&ug_btm=b8727%2Cb0&user_id=7434930569061090359&utm_campaign=client_share&utm_medium=ios&utm_source=copy">- luzvimindajourneys</a></span><br>
          </div>
        </div>
        <div class="form w3-margin-top">
          <div class="container w3-round-xlarge">
            <form class="w3-highway-blue w3-padding-large w3-round-large">
              <label for="fname">First Name</label>
              <input type="text" id="name" name="name" placeholder="Your name">

              <label for="lname">Email</label>
              <input type="text" id="email" name="email" placeholder="Your email">

              <label for="subject">Subject</label>
              <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
              
              <p>By submiting this form, you agree to our <a href="privacy-policy.html" target="_blank">privacy policy</a></p><br>
              <input class="w3-metro-blue" type="submit" value="Submit">
            </form>
          </div>
        </div>
      </div>

      <div class=" w3-highway-blue w3-padding-large" id="footer">
        <p class="w3-center logo">© 2025 - LUZVIMINDA<span>JOURNEYS</span> - All rights reserved</p>
      </div>

  <script>
    function toggleMobileNavigation() {
      const mobileNavigation = document.getElementById("mobile-sidenav");
      mobileNavigation.classList.toggle('mobile-links-active');
    }
</script>
