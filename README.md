# brawn
Software Developer website

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Web Development Agency</title>
    <link rel="stylesheet" href="../swiftCode/swiftBrawn.css">
    <script src="../swiftCode/swifbrawn.js"></script>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <h1 id="greeting"></h1>
            <h2 id="day">Software Engineering Development</h2>
            <h3 id="message"></h3>
            <nav>
                <ul>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#services">Our Projections</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
                <button id="kero"><a href="#">Request Quote!</a></button>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1 class="brands">SWIFTBRAWN</h1>
            <h2>Your One-Stop Solution for Web Development</h2>
            <h3>Software Engineering Developer Wizard with 99.9% Tenacity</h3>
            <p>We build websites that help grow your business.</p>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We are a team of passionate web developers who specialize in creating robust and scalable web applications. With years of experience, we deliver high-quality solutions tailored to your business needs.</p>
        </div>
    </section>

    <!-- Our Projections Section -->
    <section id="services" class="services">
        <div class="container">
            <h2>Our Projections</h2>
            <ul>
                <li>We aim to increase user engagement through optimized UI/UX design.</li>
                <li>We predict a rise in interactive and dynamic content for better conversions.</li>
                <li>Our team is dedicated to utilizing cutting-edge technologies for faster, secure websites.</li>
                <li>Focus on building mobile-responsive websites with faster loading speeds.</li>
            </ul>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Our Portfolio</h2>
            <div class="portfolio-gallery">
                <div class="portfolio-item"       id="image-container">
                  <img id="estate" src="../swiftCode/img/real.jpg" alt="Estate image" width="300px" height="400px" onclick="estate">
                    <h3>Real Estate Landing Website</h3>
                </div>

                <div class="portfolio-item" id="image-container">
                    <img id="gaming" src="../swiftCode/img/pro2.jpg" alt="Project 2" width="300px"  height="400px">
                    <h3>Gaming Gear E-commerce Websites</h3>
                </div>
                <div class="portfolio-item" id="image-container">
                    <img id="Food" src="../swiftCode/img/pr3.jpg" alt="Project 3" width="300px"  height="400px" onclick="document.getElementById(estate)">
                    <h3>Food Vendor Websites</h3>
                </div>
                
            <div class="portfolio-item" id="image-container">
                <img id="Video" src="../swiftCode/img/pr4.jpg" alt="Project 3" width="300px"  height="400px">
                <h3>Video Editing Website</h3>
            </div>
            <div class="portfolio-item" id="image-container">
                <img id="consult" src="../swiftCode/img/sco.jpg" alt="Project 3" width="300px"  height="400px" onclick="consult()">
                <h3>Consultant Website</h3>
            </div>
            <div class="portfolio-item" id="image-container">
                <img id="firm" src="../swiftCode/img/cons.jpg" alt="Project 3" width="300px"  height="400px" onclick="firm()">
                <h3>Construction</h3>
            </div>
            </div>
        </div>
    </section>

    
            <!-- What we do section -->
            <section id="offer" class="offer">
                <div class="container">
                 <h2>What swiftBrawn does!</h2>
                    <li><strong>Our Software Engineer:</strong> <br>General software development roles focusing on designing, coding, testing, and maintaining software applications.</li>
                     <li><strong> <br>Our Frontend Developer:</strong> <br>Specializes in building user interfaces and experiences using technologies like HTML, CSS, and JavaScript.</li>
                     <li id="offer"><strong> <br>Our Backend Developer:</strong> <br>Works on server-side logic, databases, and APIs using languages like Java, Python, Ruby, or Node.js.</li>
                     <li><strong> <br>Our Full Stack Developer:</strong> <br>Combines both frontend and backend skills to build complete web applications.</li>
                     <li><strong> <br> Our DevOps Engineer:</strong> <br>Focuses on the integration of development and operations, ensuring smooth deployment and scaling of applications.</li>
                     <li><strong><br> Our Data Engineer:</strong> <br>Specializes in managing and optimizing data pipelines and databases.</li>
                     <li><strong> <br> Our Machine Learning Engineer:</strong> <br> Works on developing and deploying machine learning models and algorithms.</li>
                     <li><strong> <br> Our Quality Assurance (QA) Engineer:</strong> <br> Focuses on testing software to ensure it meets quality standards.</li>
                 </ul>
                </div>
                 </section>

    <!-- Contact Us Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="submit_form.php" method="POST" class="contact-form">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Web Development Agency. All Rights Reserved.</p>
        </div>
    </footer>
    <script src="../swiftCode/swifbrawn.js"></script>
</body>
</html>

