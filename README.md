<section class="contact-section">
  <div class="contact-card">
    <h2>Contact Us</h2>
    <form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <input type="tel" name="mobile" placeholder="Mobile Number" required pattern="[0-9]{10}" />
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
      <div id="form-response"></div>
    </form>
  </div>
</section>

.contact-section {
  background: white url('images/logo-bg.png') center center no-repeat;
  background-size: 300px auto;
  padding: 60px 20px;
  display: flex;
  justify-content: center;
}

.contact-card {
  background: #ffffffee;
  padding: 40px;
  border-radius: 12px;
  max-width: 600px;
  width: 100%;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.08);
  z-index: 1;
}

.contact-card h2 {
  margin-bottom: 24px;
  text-align: center;
  font-size: 28px;
  color: #00264d;
}

.contact-card form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.contact-card input,
.contact-card textarea {
  padding: 12px 16px;
  border: 1px solid #ccc;
  border-radius: 6px;
  font-size: 16px;
  width: 100%;
  box-sizing: border-box;
}

.contact-card textarea {
  min-height: 120px;
  resize: vertical;
}

.contact-card button {
  padding: 12px;
  background-color: #0047ab;
  color: #fff;
  border: none;
  font-size: 16px;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact-card button:hover {
  background-color: #003380;
}

#form-response {
  margin-top: 10px;
  font-weight: bold;
  color: green;
}
