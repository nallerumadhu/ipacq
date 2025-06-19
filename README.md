<header class="navbar">
  <div class="logo">
    <img src="images/ipacq-logo.png" alt="iPACQ Logo" />
  </div>

  <nav class="nav-links">
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <a href="#contact" class="cta-button red">Get In Touch</a>

  <div class="hamburger" onclick="toggleMenu()">
    <i class="fas fa-bars"></i>
  </div>
</header>




.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #00264d;
  padding: 15px 30px;
  position: sticky;
  top: 0;
  z-index: 999;
}

.logo img {
  height: 40px;
}

.nav-links {
  display: flex;
  gap: 25px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  font-size: 16px;
}

.nav-links a:hover {
  color: #00c3ff;
}

.cta-button.red {
  background-color: #e60000;
  padding: 10px 20px;
  border-radius: 6px;
  color: white;
  font-weight: bold;
  text-decoration: none;
}

.cta-button.red:hover {
  background-color: #cc0000;
}

.hamburger {
  display: none;
  font-size: 24px;
  color: white;
  cursor: pointer;
}

/* Responsive */
@media (max-width: 768px) {
  .nav-links {
    display: none;
    flex-direction: column;
    background-color: #00264d;
    position: absolute;
    top: 60px;
    left: 0;
    width: 100%;
    padding: 20px;
  }

  .nav-links.show {
    display: flex;
  }

  .hamburger {
    display: block;
  }

  .cta-button.red {
    display: none;
  }
}


<script>
  function toggleMenu() {
    document.querySelector('.nav-links').classList.toggle('show');
  }
</script>

