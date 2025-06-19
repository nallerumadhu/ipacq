<section class="about-gallery">
  <div class="gallery-container">
    <img src="images/about1.jpg" alt="Workplace 1" />
    <img src="images/about2.jpg" alt="Workplace 2" />
    <img src="images/about3.jpg" alt="Workplace 3" />
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

.gallery-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
  align-items: center;
  margin-bottom: 40px;
}

.gallery-container img {
  width: 100%;
  max-width: 800px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
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


