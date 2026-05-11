<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Green Valley School - Welcome</title>
    
    <style>
        /* ========================================
           GENERAL STYLES & RESET
           ======================================== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        /* ========================================
           HEADER & NAVIGATION
           ======================================== */
        header {
            background-color: #0052cc;
            color: white;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            z-index: 100;
        }

        .header-container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .school-name {
            font-size: 1.8rem;
            font-weight: bold;
        }

        /* Navigation Menu */
        nav ul {
            list-style: none;
            display: flex;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 1rem;
            transition: color 0.3s ease;
        }

        /* Hover effect on navigation links */
        nav a:hover {
            color: #ffdd00;
            text-decoration: underline;
        }

        /* ========================================
           MAIN CONTAINER
           ======================================== */
        main {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        section {
            background-color: white;
            margin: 2rem 0;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            display: none;
        }

        /* Show the active section */
        section.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        /* Fade-in animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            color: #0052cc;
            margin-bottom: 1rem;
            font-size: 2rem;
        }

        h2 {
            color: #0052cc;
            margin-bottom: 1rem;
            margin-top: 1.5rem;
            font-size: 1.5rem;
        }

        p {
            margin-bottom: 1rem;
            line-height: 1.8;
        }

        /* ========================================
           HOME SECTION - BANNER
           ======================================== */
        .banner {
            background: linear-gradient(135deg, #0052cc 0%, #0080ff 100%);
            color: white;
            padding: 3rem 2rem;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 2rem;
        }

        .banner h1 {
            color: white;
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .banner p {
            font-size: 1.1rem;
            margin-bottom: 0;
        }

        /* ========================================
           BUTTONS
           ======================================== */
        .btn {
            background-color: #0052cc;
            color: white;
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.3s ease, transform 0.2s ease;
            display: inline-block;
            text-decoration: none;
        }

        /* Hover effect on buttons */
        .btn:hover {
            background-color: #0041a3;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,82,204,0.3);
        }

        .btn:active {
            transform: translateY(0);
        }

        /* ========================================
           COURSES SECTION
           ======================================== */
        .courses-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .course-card {
            background-color: #f9f9f9;
            border-left: 5px solid #0052cc;
            padding: 1.5rem;
            border-radius: 5px;
            transition: box-shadow 0.3s ease, transform 0.3s ease;
        }

        /* Hover effect on course cards */
        .course-card:hover {
            box-shadow: 0 8px 16px rgba(0,82,204,0.2);
            transform: translateY(-5px);
        }

        .course-card h3 {
            color: #0052cc;
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        .course-card p {
            color: #666;
            font-size: 0.95rem;
        }

        /* ========================================
           FORM STYLES
           ======================================== */
        .contact-form {
            max-width: 600px;
            margin: 2rem auto;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        label {
            display: block;
            margin-bottom: 0.5rem;
            color: #0052cc;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            font-family: Arial, sans-serif;
            transition: border-color 0.3s ease;
        }

        input[type="text"]:focus,
        input[type="email"]:focus,
        textarea:focus {
            outline: none;
            border-color: #0052cc;
            box-shadow: 0 0 5px rgba(0,82,204,0.3);
        }

        textarea {
            resize: vertical;
            min-height: 150px;
        }

        .error {
            color: #e74c3c;
            font-size: 0.85rem;
            margin-top: 0.3rem;
        }

        /* ========================================
           FOOTER
           ======================================== */
        footer {
            background-color: #0052cc;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        footer p {
            margin: 0;
            color: white;
        }

        /* ========================================
           RESPONSIVE DESIGN
           ======================================== */
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column;
                gap: 1rem;
            }

            nav ul {
                flex-direction: column;
                gap: 0.5rem;
                text-align: center;
            }

            nav a {
                display: block;
                padding: 0.5rem 0;
            }

            h1 {
                font-size: 1.5rem;
            }

            h2 {
                font-size: 1.2rem;
            }

            .banner h1 {
                font-size: 1.8rem;
            }

            .banner {
                padding: 2rem 1rem;
            }

            main {
                padding: 10px;
            }

            section {
                padding: 1.5rem;
                margin: 1rem 0;
            }

            .courses-container {
                grid-template-columns: 1fr;
            }

            .contact-form {
                padding: 0 10px;
            }
        }

        /* ========================================
           WELCOME BUTTON STYLES
           ======================================== */
        .welcome-message {
            background-color: #e8f4f8;
            color: #0052cc;
            padding: 1rem;
            border-radius: 5px;
            margin-top: 1rem;
            text-align: center;
            display: none;
            animation: slideDown 0.5s ease;
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .welcome-message.show {
            display: block;
        }
    </style>
</head>
<body>
    <!-- ================================
         HEADER & NAVIGATION
         ================================ -->
    <header>
        <div class="header-container">
            <div class="school-name">🎓 Green Valley School</div>
            <nav>
                <ul>
                    <!-- Navigation links that trigger section changes -->
                    <li><a href="#" data-section="home">Home</a></li>
                    <li><a href="#" data-section="about">About</a></li>
                    <li><a href="#" data-section="courses">Courses</a></li>
                    <li><a href="#" data-section="contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- ================================
         MAIN CONTENT
         ================================ -->
    <main>
        <!-- ===== HOME SECTION ===== -->
        <section id="home" class="active">
            <!-- Banner with welcome message -->
            <div class="banner">
                <h1>Welcome to Green Valley School</h1>
                <p>Empowering students to achieve their dreams</p>
            </div>

            <!-- Interactive welcome button -->
            <div style="text-align: center;">
                <button class="btn" id="welcomeBtn">Click to Learn More</button>
            </div>

            <!-- Welcome message that appears on button click -->
            <div class="welcome-message" id="welcomeMessage">
                <h2>Welcome to our school! 🎉</h2>
                <p>We are committed to providing quality education and developing well-rounded individuals. Our school offers excellent facilities, experienced teachers, and a supportive learning environment.</p>
            </div>

            <!-- Short home content -->
            <h2>Why Choose Us?</h2>
            <ul style="margin-left: 2rem; margin-bottom: 1rem;">
                <li>Expert and dedicated faculty members</li>
                <li>Modern learning facilities and technology</li>
                <li>Comprehensive curriculum covering academics and sports</li>
                <li>Supportive and inclusive learning environment</li>
            </ul>
        </section>

        <!-- ===== ABOUT SECTION ===== -->
        <section id="about">
            <h1>About Green Valley School</h1>
            
            <h2>Our History</h2>
            <p>Green Valley School was established in 1985 with a vision to provide quality education to students from all backgrounds. Over the years, we have grown into one of the leading educational institutions in the region.</p>

            <h2>Our Mission</h2>
            <p>Our mission is to nurture young minds and help them develop critical thinking skills, creativity, and character values. We believe in holistic development and prepare students for success in higher education and beyond.</p>

            <h2>Our Vision</h2>
            <p>We envision a school where every student feels valued, challenged, and supported to reach their full potential. We aim to create engaged learners who become responsible citizens and contribute positively to society.</p>

            <h2>Our Values</h2>
            <ul style="margin-left: 2rem;">
                <li><strong>Excellence:</strong> Striving for the highest standards in everything we do</li>
                <li><strong>Integrity:</strong> Upholding honesty and strong moral principles</li>
                <li><strong>Respect:</strong> Valuing diversity and treating everyone with dignity</li>
                <li><strong>Collaboration:</strong> Working together to achieve common goals</li>
            </ul>
        </section>

        <!-- ===== COURSES SECTION ===== -->
        <section id="courses">
            <h1>Our Courses</h1>
            <p>We offer a diverse range of courses designed to meet the needs of all students. Here are some of our main offerings:</p>

            <div class="courses-container">
                <!-- Course Card 1 -->
                <div class="course-card">
                    <h3>📚 English & Literature</h3>
                    <p>Develop strong communication skills and explore great literary works. Learn to express ideas clearly through writing and speaking.</p>
                </div>

                <!-- Course Card 2 -->
                <div class="course-card">
                    <h3>🔬 Science & Technology</h3>
                    <p>Explore the wonders of physics, chemistry, and biology. Hands-on experiments help students understand scientific concepts.</p>
                </div>

                <!-- Course Card 3 -->
                <div class="course-card">
                    <h3>➕ Mathematics</h3>
                    <p>Master fundamental and advanced mathematical concepts. Build problem-solving skills through regular practice and interactive learning.</p>
                </div>

                <!-- Course Card 4 -->
                <div class="course-card">
                    <h3>🌍 Social Studies</h3>
                    <p>Understand history, geography, and social sciences. Learn about different cultures and how societies function and evolve.</p>
                </div>

                <!-- Course Card 5 -->
                <div class="course-card">
                    <h3>🎨 Arts & Creativity</h3>
                    <p>Express yourself through art, music, and drama. Develop creative thinking and appreciation for different forms of artistic expression.</p>
                </div>

                <!-- Course Card 6 -->
                <div class="course-card">
                    <h3>⚽ Physical Education</h3>
                    <p>Build fitness and learn various sports. Develop teamwork and leadership skills through physical activity and outdoor games.</p>
                </div>
            </div>
        </section>

        <!-- ===== CONTACT SECTION ===== -->
        <section id="contact">
            <h1>Contact Us</h1>
            <p>Have questions? We'd love to hear from you! Fill out the form below and we'll get back to you as soon as possible.</p>

            <!-- Contact Form -->
            <form class="contact-form" id="contactForm">
                <!-- Name Field -->
                <div class="form-group">
                    <label for="name">Full Name *</label>
                    <input type="text" id="name" name="name" placeholder="Enter your full name">
                    <div class="error" id="nameError"></div>
                </div>

                <!-- Email Field -->
                <div class="form-group">
                    <label for="email">Email Address *</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email address">
                    <div class="error" id="emailError"></div>
                </div>

                <!-- Message Field -->
                <div class="form-group">
                    <label for="message">Message *</label>
                    <textarea id="message" name="message" placeholder="Type your message here..."></textarea>
                    <div class="error" id="messageError"></div>
                </div>

                <!-- Submit Button -->
                <button type="submit" class="btn" style="width: 100%;">Send Message</button>
            </form>

            <!-- Contact Information -->
            <h2>Contact Information</h2>
            <p><strong>Address:</strong> 123 Education Lane, Learning City, SC 12345</p>
            <p><strong>Phone:</strong> (555) 123-4567</p>
            <p><strong>Email:</strong> info@greenvalleyschool.edu</p>
            <p><strong>Office Hours:</strong> Monday - Friday, 8:00 AM - 4:00 PM</p>
        </section>
    </main>

    <!-- ================================
         FOOTER
         ================================ -->
    <footer>
        <p>&copy; 2026 Green Valley School. All rights reserved. | Empowering Students, Building Futures</p>
    </footer>

    <!-- ================================
         JAVASCRIPT - FUNCTIONALITY
         ================================ -->
    <script>
        // ========================================
        // NAVIGATION - SWITCH BETWEEN SECTIONS
        // ========================================
        // Get all navigation links
        const navLinks = document.querySelectorAll('nav a');
        
        // Add click event listener to each navigation link
        navLinks.forEach(link => {
            link.addEventListener('click', function(event) {
                event.preventDefault(); // Prevent default link behavior
                
                // Get the section ID from data attribute
                const sectionId = this.getAttribute('data-section');
                
                // Call function to show the selected section
                showSection(sectionId);
            });
        });

        // Function to show/hide sections
        function showSection(sectionId) {
            // Get all sections
            const sections = document.querySelectorAll('section');
            
            // Hide all sections by removing 'active' class
            sections.forEach(section => {
                section.classList.remove('active');
            });
            
            // Show the selected section by adding 'active' class
            const activeSection = document.getElementById(sectionId);
            if (activeSection) {
                activeSection.classList.add('active');
            }
        }

        // ========================================
        // WELCOME BUTTON - INTERACTIVE FEATURE
        // ========================================
        // Get the welcome button and message elements
        const welcomeBtn = document.getElementById('welcomeBtn');
        const welcomeMessage = document.getElementById('welcomeMessage');

        // Add click event listener to welcome button
        welcomeBtn.addEventListener('click', function() {
            // Toggle the 'show' class to display/hide the welcome message
            welcomeMessage.classList.toggle('show');
            
            // Change button text based on state
            if (welcomeMessage.classList.contains('show')) {
                welcomeBtn.textContent = 'Hide Message';
            } else {
                welcomeBtn.textContent = 'Click to Learn More';
            }
        });

        // ========================================
        // CONTACT FORM VALIDATION & SUBMISSION
        // ========================================
        // Get the contact form
        const contactForm = document.getElementById('contactForm');

        // Add submit event listener to the form
        contactForm.addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent default form submission
            
            // Clear previous error messages
            document.getElementById('nameError').textContent = '';
            document.getElementById('emailError').textContent = '';
            document.getElementById('messageError').textContent = '';
            
            // Get form input values
            const name = document.getElementById('name').value.trim();
            const email = document.getElementById('email').value.trim();
            const message = document.getElementById('message').value.trim();

            // Validate inputs
            let isValid = true;

            // Check if name is empty
            if (name === '') {
                document.getElementById('nameError').textContent = 'Please enter your name.';
                isValid = false;
            }

            // Check if email is empty
            if (email === '') {
                document.getElementById('emailError').textContent = 'Please enter your email address.';
                isValid = false;
            } 
            // Check if email format is valid using regular expression
            else if (!isValidEmail(email)) {
                document.getElementById('emailError').textContent = 'Please enter a valid email address.';
                isValid = false;
            }

            // Check if message is empty
            if (message === '') {
                document.getElementById('messageError').textContent = 'Please enter your message.';
                isValid = false;
            }

            // If all validations pass, show success message
            if (isValid) {
                alert('✓ Message sent successfully! Thank you for contacting Green Valley School. We will get back to you soon.');
                
                // Reset the form fields
                contactForm.reset();
            }
        });

        // Function to validate email format
        function isValidEmail(email) {
            // Regular expression for basic email validation
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            return emailRegex.test(email);
        }
    </script>
</body>
</html>
