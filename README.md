<form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <input type="text" name="name" placeholder="Name" required />
  <input type="email" name="email" placeholder="Email" required />
  <input type="tel" name="mobile" placeholder="Mobile Number" required pattern="[0-9]{10}" />
  <textarea name="message" placeholder="Message" required></textarea>
  <button type="submit">Send Message</button>
</form>

<div id="form-response" style="margin-top: 20px; font-weight: bold; color: green;"></div>

<script>
  const form = document.getElementById("contact-form");
  const responseDiv = document.getElementById("form-response");

  form.addEventListener("submit", async function (e) {
    e.preventDefault(); // Prevent redirect

    const formData = new FormData(form);
    const action = form.action;

    try {
      const response = await fetch(action, {
        method: 'POST',
        body: formData,
        headers: {
          'Accept': 'application/json'
        }
      });

      if (response.ok) {
        responseDiv.textContent = "✅ Thank you! Your message has been sent.";
        form.reset(); // Clear form
      } else {
        responseDiv.textContent = "❌ Oops! Something went wrong.";
      }
    } catch (error) {
      responseDiv.textContent = "❌ Error connecting to server.";
    }
  });
</script>
