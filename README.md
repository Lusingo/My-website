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
