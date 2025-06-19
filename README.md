<!-- Swiper CSS -->
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
/>

<section class="about-gallery">
  <!-- Swiper -->
  <div class="swiper mySwiper">
    <div class="swiper-wrapper">
      <div class="swiper-slide">
        <img src="images/about1.jpg" alt="About image 1" />
      </div>
      <div class="swiper-slide">
        <img src="images/about2.jpg" alt="About image 2" />
      </div>
      <div class="swiper-slide">
        <img src="images/about3.jpg" alt="About image 3" />
      </div>
    </div>
  </div>

  <div class="about-description">
    <h2>About iPACQ Solutions</h2>
    <p>
      iPACQ Solutions is committed to providing certified PPE to protect your workforce. From quality gloves to industrial gear, we ensure safety, compliance, and comfort across industries.
    </p>
  </div>
</section>

<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<script>
  const swiper = new Swiper(".mySwiper", {
    loop: true,
    autoplay: {
      delay: 3000,
      disableOnInteraction: false,
    },
    effect: "slide",
    speed: 600,
  });
</script>

.about-gallery {
  padding: 60px 20px;
  background: #fff;
  text-align: center;
}

.swiper {
  width: 100%;
  max-width: 800px;
  margin: auto;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.swiper-slide img {
  width: 100%;
  display: block;
  height: auto;
}

.about-description {
  margin-top: 40px;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.about-description h2 {
  font-size: 28px;
  color: #00264d;
  margin-bottom: 20px;
}

.about-description p {
  font-size: 16px;
  color: #555;
  line-height: 1.6;
}
