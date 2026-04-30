<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Elite Auto Dealers | Used Cars for Sale</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #0d1b2a;
      color: white;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
      font-size: 22px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url("https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1500&q=80");
      background-size: cover;
      background-position: center;
      padding: 80px 40px;
      color: white;
      text-align: center;
    }

    .hero h2 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    .btn {
      background: #ffb703;
      padding: 12px 20px;
      color: black;
      font-weight: bold;
      text-decoration: none;
      border-radius: 5px;
    }

    .btn:hover {
      background: #ffa200;
    }

    section {
      padding: 40px;
      background: white;
      margin: 20px auto;
      max-width: 1100px;
      border-radius: 8px;
    }

    section h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #0d1b2a;
    }

    .cars {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .car-card {
      background: #f9f9f9;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    .car-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .car-card .info {
      padding: 15px;
    }

    .car-card h3 {
      margin: 0;
      font-size: 18px;
    }

    .car-card p {
      margin: 8px 0;
      font-size: 14px;
    }

    .price {
      font-size: 18px;
      font-weight: bold;
      color: green;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      text-align: center;
    }

    .service-box {
      background: #f9f9f9;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.15);
    }

    footer {
      background: #0d1b2a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 20px;
    }

    .contact p {
      text-align: center;
      font-size: 16px;
    }

    form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    input, textarea {
      padding: 12px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 15px;
    }

    textarea {
      resize: none;
      height: 120px;
    }

    button {
      background: #0d1b2a;
      color: white;
      border: none;
      padding: 12px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    button:hover {
      background: #1b263b;
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <h1>Elite Auto Dealers</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#cars">Cars</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- HERO SECTION -->
  <div class="hero" id="home">
    <h2>Quality Used Cars at Affordable Prices</h2>
    <p>Browse our wide selection of inspected and reliable vehicles.</p>
    <a href="#cars" class="btn">View Cars for Sale</a>
  </div>

  <!-- ABOUT SECTION -->
  <section id="about">
    <h2>About Us</h2>
    <p style="text-align:center; font-size:16px;">
      Elite Auto Dealers is a trusted used car dealership providing quality vehicles
      to customers. We specialize in affordable, reliable cars that are inspected and road-ready.
      Our mission is to offer excellent customer service and the best value for money.
    </p>
  </section>

  <!-- CARS FOR SALE -->
  <section id="cars">
    <h2>Cars for Sale</h2>

    <div class="cars">

      <div class="car-card">
        <img src="https://images.unsplash.com/photo-1542362567-b07e54358753?auto=format&fit=crop&w=1200&q=80" alt="Toyota Corolla">
        <div class="info">
          <h3>Toyota Corolla 2016</h3>
          <p>Mileage: 85,000 km</p>
          <p>Transmission: Automatic</p>
          <p class="price">P 95,000</p>
          <p><b>Contact:</b> +267 71 000 111</p>
        </div>
      </div>

      <div class="car-card">
        <img src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1200&q=80" alt="BMW">
        <div class="info">
          <h3>BMW 3 Series 2015</h3>
          <p>Mileage: 110,000 km</p>
          <p>Transmission: Manual</p>
          <p class="price">P 165,000</p>
          <p><b>Contact:</b> +267 71 000 111</p>
        </div>
      </div>

      <div class="car-card">
        <img src="https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1200&q=80" alt="Ford Ranger">
        <div class="info">
          <h3>Ford Ranger 2018</h3>
          <p>Mileage: 72,000 km</p>
          <p>Transmission: Automatic</p>
          <p class="price">P 245,000</p>
          <p><b>Contact:</b> +267 71 000 111</p>
        </div>
      </div>

      <div class="car-card">
        <img src="https://images.unsplash.com/photo-1609521263047-f8f205293f24?auto=format&fit=crop&w=1200&q=80" alt="Honda Fit">
        <div class="info">
          <h3>Honda Fit 2017</h3>
          <p>Mileage: 90,000 km</p>
          <p>Transmission: Automatic</p>
          <p class="price">P 88,000</p>
          <p><b>Contact:</b> +267 71 000 111</p>
        </div>
      </div>

    </div>
  </section>

  <!-- SERVICES -->
  <section id="services">
    <h2>Our Services</h2>

    <div class="services">
      <div class="service-box">
        <h3>Vehicle Sales</h3>
        <p>We sell quality used cars at affordable prices.</p>
      </div>

      <div class="service-box">
        <h3>Car Financing Advice</h3>
        <p>We help customers with financing and payment options.</p>
      </div>

      <div class="service-box">
        <h3>Car Imports</h3>
        <p>We assist with importing vehicles from South Africa and Japan.</p>
      </div>

      <div class="service-box">
        <h3>Vehicle Inspection</h3>
        <p>All cars are inspected for safety and performance.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>

    <p><b>Location:</b> Gaborone, Botswana</p>
    <p><b>Phone:</b> +267 71 000 111</p>
    <p><b>Email:</b> eliteautodealers@gmail.com</p>

    <h3 style="text-align:center;">Send an Inquiry</h3>

    <form>
      <input type="text" placeholder="Full Name" required>
      <input type="email" placeholder="Email Address" required>
      <input type="text" placeholder="Car Interested In (Optional)">
      <textarea placeholder="Write your message here..." required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>&copy; 2026 Elite Auto Dealers | All Rights Reserved</p>
  </footer>

</body>
</html>
