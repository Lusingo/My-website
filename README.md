# My-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lusingo Consultancy - Home</title>
  <link rel="stylesheet" href="style.css">
  <style>
    .moving-text {
      position: relative;
      animation: moveUp 10s linear infinite;
    }

    @keyframes moveUp {
      0% { top: 0; }
      100% { top: -20px; }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Lusingo Consultancy Logo" class="logo">
    <h1 class="moving-text">Lusingo Consultancy</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <h2>Welcome to Lusingo Consultancy</h2>
    <p>We offer expert accounting, IT, and business advisory services to help you grow and stay compliant.</p>
    <a class="whatsapp-button" href="https://wa.me/255759844716" target="_blank">Chat with us on WhatsApp</a>
  </main>

  <footer>
    &copy; 2025 Lusingo Consultancy
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lusingo Consultancy - Services</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Lusingo Consultancy Logo" class="logo">
    <h1>Lusingo Consultancy</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <h2>Our Services</h2>
    <ul>
      <li>Accounting & Bookkeeping</li>
      <li>Tax Consultation & Compliance</li>
      <li>Financial Reporting</li>
      <li>IT & Systems Integration</li>
      <li>Business & Financial Advisory</li>
    </ul>
  </main>

  <footer>
    &copy; 2025 Lusingo Consultancy
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lusingo Consultancy - Contact</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Lusingo Consultancy Logo" class="logo">
    <h1>Lusingo Consultancy</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 0759 844 716</p>
    <p><strong>Email:</strong> nyamhokyalusingo10@gmail.com</p>
    <p><strong>Location:</strong> Tua Moyo, Kigamboni, Dar es Salaam</p>

    <a class="whatsapp-button" href="https://wa.me/255759844716" target="_blank">Chat with us on WhatsApp</a>

    <h3>Send Us a Message</h3>
    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
      <label for="name">Full Name:</label><br>
      <input type="text" id="name" name="name" required><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="_replyto" required><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5" required></textarea><br>

      <button type="submit">Send</button>
    </form>
  </main>

  <footer>
    &copy; 2025 Lusingo Consultancy
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

header {
  background: #2c3e50;
  color: #fff;
  padding: 20px;
  text-align: center;
  position: relative;
}

.logo {
  width: 100px;
  position: absolute;
  top: 10px;
  left: 20px;
}

nav a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

main {
  max-width: 800px;
  margin: auto;
  padding: 30px;
  background: white;
  border-radius: 10px;
  margin-top: 20px;
}

footer {
  background: #2c3e50;
  color: #fff;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}

.whatsapp-button {
  display: inline-block;
  margin: 20px 0;
  padding: 10px 20px;
  background: #25D366;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

.whatsapp-button:hover {
  background: #1ebe5b;
}

form input, form textarea {
  width: 100%;
  margin-bottom: 15px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  background-color: #2c3e50;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
}

