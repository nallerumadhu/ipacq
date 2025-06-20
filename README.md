<section class="protection-categories">
  <div class="category-box">
    <a href="products.html#hand-protection">
      <img src="images/hand.jpg" alt="Hand Protection" />
      <div class="category-label">HAND PROTECTION</div>
    </a>
  </div>
  <div class="category-box">
    <a href="products.html#foot-protection">
      <img src="images/foot.jpg" alt="Foot Protection" />
      <div class="category-label">FOOT PROTECTION</div>
    </a>
  </div>
  <div class="category-box">
    <a href="products.html#body-protection">
      <img src="images/body.jpg" alt="Body Protection" />
      <div class="category-label">BODY PROTECTION</div>
    </a>
  </div>
  <div class="category-box">
    <a href="products.html#head-protection">
      <img src="images/head.jpg" alt="Head Protection" />
      <div class="category-label">HEAD PROTECTION</div>
    </a>
  </div>
  <div class="category-box">
    <a href="products.html#fall-protection">
      <img src="images/fall.jpg" alt="Fall Protection" />
      <div class="category-label">FALL PROTECTION</div>
    </a>
  </div>
  <div class="category-box">
    <a href="products.html#eye-protection">
      <img src="images/eye.jpg" alt="Protecting Your Eyes" />
      <div class="category-label">PROTECTING YOUR EYES</div>
    </a>
  </div>
</section>

.protection-categories {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px 5%;
  background-color: #fff;
}

.category-box {
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 4px;
  transition: transform 0.3s;
  background: #f9f9f9;
}

.category-box:hover {
  transform: scale(1.02);
}

.category-box img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
}

.category-label {
  background-color: #0056a3; /* dark blue */
  color: white;
  text-align: center;
  padding: 12px 0;
  font-weight: bold;
  font-size: 15px;
  text-transform: uppercase;
}


@media (max-width: 768px) {
  .protection-categories {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .protection-categories {
    grid-template-columns: 1fr;
  }
}

