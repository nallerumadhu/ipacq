<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <input type="text" name="name" placeholder="Name" required />
  <input type="email" name="email" placeholder="Email" required />
  <textarea name="message" placeholder="Message" required></textarea>
  <button type="submit">Send Message</button>
</form>
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" onsubmit="showSuccess()">
  ...
</form>

<script>
  function showSuccess() {
    alert("Thank you! Your message has been sent.");
  }
</script>

<input type="text" name="_gotcha" style="display:none">
