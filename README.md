# global-credit-union

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Global Credit Union</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Header -->
  <header class="top-bar">
    <div class="logo">
      <img src="https://www.globalcu.org/globalassets/images/logo.svg" alt="Global Credit Union Logo">
    </div>
    <button class="sign-in-btn">Sign In</button>
    <div class="menu">&#9776;</div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Strength in members</h1>
    <p>For today’s financial needs, and tomorrow’s financial milestones.</p>
    <a href="https://www.globalcu.org" class="cta-btn">Learn more</a>
  </section>

  <!-- Image Section -->
  <section class="image-banner">
    <img src="https://www.globalcu.org/globalassets/images/homepage/family-hiking.jpg" alt="Family by lake">
  </section>

  <!-- Quick Links -->
  <section class="quick-links">
    <div class="link-box">
      <img src="https://www.globalcu.org/globalassets/icons/payment.svg" alt="Payment icon">
      <a href="#">Make a Payment</a>
    </div>
    <div class="link-box">
      <img src="https://www.globalcu.org/globalassets/icons/calendar.svg" alt="Appointment icon">
      <a href="#">Make an Appointment</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Global Credit Union. All rights reserved.</p>
  </footer>

</body>
</html>

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background-color: #fff;
}

.top-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px;
  background-color: white;
}

.logo img {
  height: 30px;
}

.sign-in-btn {
  background-color: #ffc107;
  border: none;
  padding: 8px 15px;
  font-weight: bold;
  cursor: pointer;
}

.menu {
  font-size: 24px;
  cursor: pointer;
}

.hero {
  background-color: #003366;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

.hero h1 {
  font-size: 1.8em;
  margin-bottom: 10px;
}

.hero p {
  color: #66ccff;
  font-size: 1em;
  margin-bottom: 20px;
}

.cta-btn {
  background-color: #ffc107;
  color: #003366;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 3px;
}

.image-banner img {
  width: 100%;
  height: auto;
  display: block;
}

.quick-links {
  background-color: #f5f5f5;
  padding: 20px;
}

.link-box {
  display: flex;
  align-items: center;
  margin: 15px 0;
}

.link-box img {
  height: 30px;
  margin-right: 15px;
}

.link-box a {
  text-decoration: none;
  color: #003366;
  font-weight: bold;
}

footer {
  background-color: #003366;
  color: white;
  text-align: center;
  padding: 15px;
  font-size: 0.9em;
