<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Hearing | Mobile Ear Wax Removal</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }
    header {
      background: #2a6fb3;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      font-size: 2rem;
    }
    header p {
      font-size: 1.1rem;
      margin: 0.5rem 0 1.5rem;
    }
    .btn {
      background: #ffd700;
      color: #000;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      text-decoration: none;
    }
    .section {
      padding: 2rem 1rem;
      max-width: 800px;
      margin: auto;
    }
    .steps {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1rem;
    }
    .step {
      background: #fff;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .testimonial {
      background: #fff;
      padding: 1rem;
      border-left: 4px solid #2a6fb3;
      margin: 1rem 0;
    }
    form {
      display: grid;
      gap: 1rem;
      background: #fff;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    input, textarea {
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #777;
    }
    @media (min-width: 600px) {
      .steps {
        grid-template-columns: repeat(3, 1fr);
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Simple Hearing</h1>
    <p>Clear Ears. At Your Door Or Place Of Work!</p>
    <a href="#contact" class="btn">Enquire Today</a>
  </header>

  <section class="section">
    <h2>How It Works</h2>
    <div class="steps">
      <div class="step">
        <h3>1. Enquire or Book Today</h3>
        <p>Choose a time that works for you.</p>
      </div>
      <div class="step">
        <h3>2. We Come to You</h3>
        <p>Our specialist arrives with professional equipment. 
        
        We use Microsuction and Manual Extration.</p>
      </div>
      <div class="step">
        <h3>3. Hear Clearly Again</h3>
        <p>Enjoy gentle, effective treatment right at home or place of work</p>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>What People Say</h2>
    <div class="testimonial">
      <p>“So convenient! I didn’t even have to leave the house and my hearing feels so much better. Highly recommend Simple Hearing!”</p>
      <p><strong>— Sarah M.</strong></p>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Enquire Today</h2>
    <form name="contact" method="POST" data-netlify="true">
      <input type="hidden" name="form-name" value="contact" />
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Email Address" required />
      <input type="tel" name="phone" placeholder="Phone Number" required />
      <textarea name="message" rows="4" placeholder="Your Address or Notes" required></textarea>
      <button type="submit" class="btn">Submit</button>
    </form>
    <p style="margin-top:1rem; font-size:0.9rem; color:#555;">
      You can also reach us at <strong>contact@simplehearing.com</strong> or call <strong>07878 894006</strong>.
    </p>
    <p style="font-size:0.9rem; color:#555;">
      Follow us on 
      <a href="https://www.instagram.com/simple_hearing/" target="_blank">Instagram</a> 
      and 
      <a href="https://www.facebook.com/profile.php?id=61570751494403" target="_blank">Facebook</a>.
    </p>
  </section>

  <footer>
    &copy; 2025 Simple Hearing. All rights reserved.
  </footer>
</body>
</html>
