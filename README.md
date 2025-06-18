.contact-section {
  padding: 60px 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background: transparent;
}

.contact-card {
  background: #fff;
  padding: 40px;
  max-width: 500px;
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
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
  gap: 16px;
}

.contact-card input,
.contact-card textarea {
  padding: 12px 16px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 16px;
  background-color: #f9f9f9;
}

.contact-card input:focus,
.contact-card textarea:focus {
  border-color: #0047ab;
  outline: none;
  background-color: #fff;
}

.contact-card button {
  padding: 12px;
  background-color: #0047ab;
  color: white;
  border: none;
  border-radius: 8px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  transition: background 0.3s ease;
}

.contact-card button:hover {
  background-color: #003380;
}

#form-response {
  margin-top: 10px;
  text-align: center;
  font-weight: bold;
  color: green;
}

.social-links {
  margin-top: 20px;
  text-align: center;
}

.social-links a {
  display: inline-block;
  margin: 0 10px;
  font-size: 20px;
  color: #0047ab;
  background-color: #f2f2f2;
  padding: 10px;
  border-radius: 50%;
  transition: all 0.3s ease;
}

.social-links a:hover {
  background-color: #0047ab;
  color: #fff;
}
