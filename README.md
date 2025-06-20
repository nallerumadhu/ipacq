<section class="protection-grid">
  <a href="products.html#hand-protection" class="grid-box">
    <img src="images/hand.jpg" alt="Hand Protection" />
    <div class="label">Hand Protection</div>
  </a>
  <a href="products.html#foot-protection" class="grid-box">
    <img src="images/foot.jpg" alt="Foot Protection" />
    <div class="label">Foot Protection</div>
  </a>
  <a href="products.html#body-protection" class="grid-box">
    <img src="images/body.jpg" alt="Body Protection" />
    <div class="label">Body Protection</div>
  </a>
  <a href="products.html#head-protection" class="grid-box">
    <img src="images/head.jpg" alt="Head Protection" />
    <div class="label">Head Protection</div>
  </a>
  <a href="products.html#fall-protection" class="grid-box">
    <img src="images/fall.jpg" alt="Fall Protection" />
    <div class="label">Fall Protection</div>
  </a>
  <a href="products.html#eye-protection" class="grid-box">
    <img src="images/eye.jpg" alt="Protecting Your Eyes" />
    <div class="label">Protecting Your Eyes</div>
  </a>
</section>


.protection-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 40px 5%;
  background: #fff;
}

.grid-box {
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  text-decoration: none;
  color: white;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s;
}

.grid-box:hover {
  transform: scale(1.03);
}

.grid-box img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  display: block;
}

.grid-box .label {
  position: absolute;
  bottom: 0;
  width: 100%;
  background: rgba(0, 0, 64, 0.8);
  text-align: center;
  padding: 10px;
  font-size: 16px;
  font-weight: bold;
}

