<section class="home-slider">
  <div class="swiper homeSwiper">
    <div class="swiper-wrapper">
      <div class="swiper-slide"><img src="images/home1.jpg" alt="Slide 1" /></div>
      <div class="swiper-slide"><img src="images/home2.jpg" alt="Slide 2" /></div>
      <div class="swiper-slide"><img src="images/home3.jpg" alt="Slide 3" /></div>
    </div>
  </div>
</section>

<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<script>
  const homeSwiper = new Swiper(".homeSwiper", {
    loop: true,
    autoplay: {
      delay: 3000,
      disableOnInteraction: false,
    },
    effect: "slide",
    speed: 600,
  });
</script>

.home-slider {
  margin-top: 70px; /* match your navbar height */
}

.homeSwiper {
  width: 100vw;
  height: 60vh;
  overflow: hidden;
}

.homeSwiper .swiper-slide img {
  width: 100vw;
  height: 60vh;
  object-fit: cover;
  display: block;
}
