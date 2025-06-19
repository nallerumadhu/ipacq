<section class="about-gallery">
  <div class="gallery-scroll">
    <img src="images/about1.jpg" alt="Team at Work" />
    <img src="images/about2.jpg" alt="Factory Floor" />
    <img src="images/about3.jpg" alt="Product Showcase" />
  </div>

  <div class="about-description">
    <h2>About iPACQ Solutions</h2>
    <p>
      At iPACQ Solutions, we specialize in delivering high-quality Personal Protective Equipment (PPE) that protects workers and boosts industrial safety.
      Our mission is to offer certified, reliable, and affordable safety gear across sectors like manufacturing, construction, and logistics.
    </p>
    <p>
      With a growing network and experienced team, we ensure quality control, rapid delivery, and unmatched customer support.
    </p>
  </div>
</section>

.about-gallery {
  padding: 60px 20px;
  background: #fff;
}

.gallery-scroll {
  display: flex;
  gap: 20px;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  -webkit-overflow-scrolling: touch;
  margin-bottom: 40px;
}

.gallery-scroll img {
  flex: 0 0 auto;
  width: 80%;
  max-width: 600px;
  border-radius: 8px;
  scroll-snap-align: start;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

.about-description {
  max-width: 800px;
  margin: auto;
  text-align: center;
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
  margin-bottom: 16px;
}
