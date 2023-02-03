<!DOCTYPE html>
<html>
<head>
  <title> Oken Media</title>
</head>
<body>
  <header>
    <h1>Oken Media</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <p>We are Oken Media, a full-service digital media company. Our team of experts offers a wide range of services, from website design and development to social media management and digital marketing.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Website Design and Development</li>
        <li>Social Media Management</li>
        <li>Search Engine Optimization (SEO)</li>
        <li>Pay-Per-Click (PPC) Advertising</li>
        <li>Content Marketing</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Get in Touch</h2>
      <form action="submit-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>

        <input type="submit" value="Submit">
      </form>
    </section>
  </main>

  <footer>
    <p>Copyright &copy; Oken Media 2023</p>
  </footer>
</body>
</html>
