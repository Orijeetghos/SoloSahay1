<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="SoloSahay: Trusted home help services like cleaning, cooking, and handyman support starting at ₹399/hour." />
  <meta name="keywords" content="SoloSahay, home services, cleaning, cooking, repairs, Kolkata helper" />
  <meta name="author" content="SoloSahay Team" />
  <title>SoloSahay | Home Help Services</title>

  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- Style -->
  <style>
    /* Your full CSS copied from previous code block without changes */
    /* Paste your CSS here (already present in your earlier message) */
    /* ... [Use exactly what you already wrote for styling] ... */
  </style>
</head>

<body>
  <!-- Header/Navbar -->
  <header>
    <nav class="navbar">
      <div class="logo">
        <i class="fas fa-tools"></i> SoloSahay
      </div>
      <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#testimonials">Reviews</a>
        <a href="#booking">Book Now</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="hero-content">
      <h1>Your Home Deserves The Best Care</h1>
      <p>Professional home helping services starting at just ₹399/hour. Book cleaning, cooking, repairs, and more with trusted experts.</p>
      <a href="#booking" class="btn">Book Now</a>
    </div>
  </section>

  <!-- Services Section -->
  <!-- [Paste your full Services section here - already complete] -->

  <!-- Testimonials Section -->
  <!-- [Paste your full Testimonials section here - already complete] -->

  <!-- Booking Form Section -->
  <section class="booking" id="booking">
    <div class="section-title">
      <h2>Book Your Service</h2>
      <p>Fill out the form below and we'll get back to you shortly.</p>
    </div>
    <div class="form-container">
      <form action="https://formspree.io/f/your-form-id" method="POST">
        <div class="form-group">
          <label for="name">Full Name</label>
          <input type="text" id="name" name="name" class="form-control" required>
        </div>

        <div class="form-group">
          <label for="phone">Phone Number</label>
          <input type="tel" id="phone" name="phone" class="form-control" required>
        </div>

        <div class="form-group">
          <label for="address">Address</label>
          <textarea id="address" name="address" class="form-control" rows="3" required></textarea>
        </div>

        <div class="form-group">
          <label>Service Type</label>
          <div class="radio-group">
            <div class="radio-option">
              <input type="radio" id="basic" name="serviceType" value="Basic Help (₹399/hr)" checked>
              <label for="basic">Basic Help (₹399/hr)</label>
            </div>
            <div class="radio-option">
              <input type="radio" id="advanced" name="serviceType" value="Advanced Help (₹599/hr)">
              <label for="advanced">Advanced Help (₹599/hr)</label>
            </div>
          </div>
        </div>

        <div class="form-group">
          <label for="service">Select Service</label>
          <select id="service" name="service" class="form-control" required>
            <option value="">-- Select a service --</option>
            <option value="cleaning">Home Cleaning</option>
            <option value="cooking">Cooking/Meal Prep</option>
            <option value="laundry">Laundry & Ironing</option>
            <option value="plumbing">Plumbing</option>
            <option value="electrical">Electrical Work</option>
            <option value="other">Other</option>
          </select>
        </div>

        <div class="form-group">
          <label for="hours">Hours Needed</label>
          <input type="number" id="hours" name="hours" class="form-control" min="1" value="1" required>
        </div>

        <button type="submit" class="btn" style="width: 100%;">Book Now</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer id="contact">
    <div class="footer-grid">
      <div class="footer-col">
        <h3>SoloSahay</h3>
        <p>Making home maintenance simple and affordable.</p>
        <div class="social-links">
          <a href="#"><i class="fab fa-facebook-f"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-linkedin-in"></i></a>
        </div>
      </div>

      <div class="footer-col">
        <h3>Services</h3>
        <ul>
          <li><a href="#services">Home Cleaning</a></li>
          <li><a href="#services">Cooking Services</a></li>
          <li><a href="#services">Handyman Repairs</a></li>
          <li><a href="#services">Laundry Services</a></li>
        </ul>
      </div>

      <div class="footer-col">
        <h3>Company</h3>
        <ul>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>

    <div class="copyright">
      © 2025 SoloSahay | Made with ❤️ in Kolkata
    </div>
  </footer>
</body>
</html>
