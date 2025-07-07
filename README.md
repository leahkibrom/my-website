<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Charity: Water Landing Page</title>
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #fbd502; /* Yellow background */
      color: #000;
    }
    /* Navigation Bar */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background-color: #00a5c3;
    }
    .logo {
      display: flex;
      align-items: center;
      font-weight: bold;
      font-size: 1.2rem;
      color: black;
    }
    .logo img {
      height: 40px;
      margin-right: 10px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      padding: 10px 20px;
      background-color: #fbd502;
      color: black;
      border-radius: 20px;
      font-weight: bold;
    }
    /* Hero Section */
    .hero {
      text-align: center;
      padding: 40px 20px;
    }
    .hero h1 {
      font-size: 3rem;
      font-weight: bold;
      color: #00a5c3;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 15px;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }
    /* CTA Button */
    .cta-button {
      display: inline-block;
      margin-top: 25px;
      padding: 15px 30px;
      background-color: #00a5c3;
      color: white;
      font-weight: bold;
      font-size: 1.2rem;
      border-radius: 30px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #007d99;
    }
    /* Image Section */
    .hero-image {
      margin-top: 40px;
      text-align: center;
    }
    .hero-image img {
      width: 90%;
      max-width: 600px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    }
    /* Footer optional */
    footer {
      text-align: center;
      margin-top: 50px;
      padding: 20px;
      font-size: 0.9rem;
      color: #555;
    }
  </style>
    </head>
    <body>   
      <header>
        </div>
        <nav>
          <a href="#">Home</a>
          <a href="#">Our Impact</a>
          <a href="#">About Us</a>
          <a href="#">Discover More</a>
        </nav>
        <!-- Added cw.jpg centered next to the nav-links -->
        <div style="display: flex; align-items: center; justify-content: center; margin-left: 20px;">
          <img src="cw.jpg" style="max-width: 80px; border-radius: 8px;">
        </div>
      </header>
      <!-- Hero Section -->
      <section class="hero">
        <h1>Together, We Can End the Water Crisis</h1>
        <p>100% of your donation brings clean, life-changing water to people in need. Help a community. Change lives. Help kids and adults dream bigger — all because of monthly donors.</p>
        <p><strong>Millions of people</strong> are suffering without access to safe water. Donate to people in extreme need today.</p>
        <a class="cta-button" href="#">Donate Now</a>
        <!-- Added Zimbabwe_2022_CG-0382.jpg under the donate now button -->
        <div style="margin-top: 30px;">
          <img src="Zimbabwe_2022_CG-0382.jpg" style="max-width: 400px; width: 100%; border-radius: 10px;">
        </div>
      </section>
