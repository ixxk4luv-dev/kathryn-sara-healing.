<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kathryn Sara — High Priestess of Love & Healing</title>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent1:#d97706; /* warm amber */
      --accent2:#8b5cf6; /* mystic purple */
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial; background: linear-gradient(180deg,#071026 0%, #081226 40%, #071022 100%); color:#e6eef8;}
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:28px}header{display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{display:flex;align-items:center;gap:12px}
.logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent2),var(--accent1));display:flex;align-items:center;justify-content:center;font-family:Playfair Display,serif;font-weight:700;color:#071022}
.brand h1{font-family:Playfair Display,serif;font-size:20px;margin:0}
.brand p{margin:0;font-size:12px;color:var(--muted)}

nav{display:flex;gap:12px;align-items:center}
.btn{padding:10px 14px;border-radius:12px;background:var(--glass);border:1px solid rgba(255,255,255,0.04);cursor:pointer}
.btn-primary{background:linear-gradient(90deg,var(--accent2),var(--accent1));color:#071022;border:none;font-weight:600}

.hero{display:grid;grid-template-columns:1fr;gap:22px;align-items:center;padding:36px 0}
.hero-inner{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:28px;border-radius:20px;box-shadow:0 6px 30px rgba(8,10,20,0.7)}
.hero h2{font-family:Playfair Display,serif;font-size:34px;margin:0 0 8px}
.hero p.lead{margin:0;color:var(--muted);line-height:1.6}

.services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:18px}
.card{background:var(--card);padding:20px;border-radius:14px;border:1px solid rgba(255,255,255,0.03)}
.card h3{margin:0 0 8px;font-size:18px}
.card p{margin:0;color:var(--muted);font-size:14px}

.two-cols{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:26px}

.testimonial{background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));padding:16px;border-radius:12px;border:1px solid rgba(255,255,255,0.02)}
.testimonial p{margin:0;color:var(--muted)}
.test-author{margin-top:12px;font-weight:600}

.contact{padding:18px;border-radius:12px;background:linear-gradient(180deg, rgba(139,92,246,0.06), rgba(217,119,6,0.03));border:1px solid rgba(255,255,255,0.02)}
label{display:block;font-size:13px;margin-bottom:6px}
input,textarea{width:100%;padding:10px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
textarea{min-height:110px}
.muted{color:var(--muted);font-size:13px}

footer{margin-top:36px;padding:18px 0;border-top:1px solid rgba(255,255,255,0.02);display:flex;justify-content:space-between;align-items:center}

/* responsive */
@media (max-width:900px){.two-cols{grid-template-columns:1fr}.hero h2{font-size:28px}}
@media (max-width:520px){header{flex-direction:column;align-items:flex-start}nav{width:100%;justify-content:space-between}}

/* decorative */
.badge{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.03);font-size:13px}
.highlight{background:linear-gradient(90deg,var(--accent2),var(--accent1));-webkit-background-clip:text;background-clip:text;color:transparent;font-family:Playfair Display,serif}

.pill{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.03);font-size:13px}

  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">KS</div>
        <div>
          <h1>Kathryn Sara</h1>
          <p>High Priestess of Love &amp; Healing</p>
        </div>
      </div>
      <nav>
        <a class="pill" href="#services">Services</a>
        <a class="pill" href="#testimonials">Testimonials</a>
        <a class="pill" href="#contact">Contact</a>
        <a class="btn btn-primary" href="#contact">Book Now</a>
      </nav>
    </header><main>
  <section class="hero">
    <div class="hero-inner">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;gap:18px;flex-wrap:wrap">
        <div style="flex:1;min-width:220px">
          <h2>Where energy meets intention and miracles are born</h2>
          <p class="lead">Welcome to the sacred space of <span class="highlight">Kathryn Sara</span>. Through Reiki healing, love spells, and protective rituals, Kathryn channels ancient wisdom and universal energy to restore balance, magnetize love, and awaken your truest self.</p>
          <div style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap">
            <a class="btn" href="#services">Explore Services</a>
            <a class="btn btn-primary" href="#contact">Book a Session</a>
          </div>
        </div>
        <div style="width:320px;min-width:220px" aria-hidden="true">
          <div class="card">
            <h3>Sessions &amp; Pricing</h3>
            <p class="muted">30-min Intuitive Reiki — $60<br>60-min Deep Reiki + Guidance — $120<br>Custom Love Spell Rites — from $150<br>Protection & Cleansing — $80</p>
          </div>
        </div>
      </div>
    </div>

    <div class="services" id="services" aria-labelledby="services-title" style="margin-top:8px">
      <div class="card">
        <h3>Reiki Healing</h3>
        <p>Gentle, restorative energy work to soothe body, mind, and spirit. Great for stress, sleep, and emotional release.</p>
      </div>
      <div class="card">
        <h3>Love Spells</h3>
        <p>Ethical rituals tailored to attract new love, rekindle a connection, or strengthen an existing relationship with clear intention.</p>
      </div>
      <div class="card">
        <h3>Protection & Cleansing</h3>
        <p>Rituals to remove negative energy and protect your aura so you can move forward with confidence and calm.</p>
      </div>
      <div class="card">
        <h3>Spiritual Guidance</h3>
        <p>Personalized readings and coaching to help you manifest purpose, clarity, and abundance.</p>
      </div>
    </div>
  </section>

  <section class="two-cols" style="margin-top:24px">
    <div>
      <div class="card">
        <h3>About Kathryn</h3>
        <p class="muted">Kathryn Sara has spent over a decade studying energy work and sacred ritual. Combining Reiki with compassionate guidance and carefully crafted spells, Kathryn helps clients heal emotional wounds, remove energetic blockages, and manifest deep, lasting love. Her practice is rooted in respect, clear intention, and the highest good of every client.</p>
        <p style="margin-top:12px" class="muted">"Energy flows where love grows."</p>
      </div>

      <div id="testimonials" style="margin-top:18px">
        <h3 style="margin-bottom:10px">Client Testimonials</h3>

        <article class="testimonial" style="margin-bottom:12px">
          <p>“Kathryn’s love spell completely transformed my relationship. Within two weeks, my partner opened his heart to me again. I’ve never felt so connected and loved. She’s pure magic!”</p>
          <div class="test-author">— Jessica M., New York</div>
        </article>

        <article class="testimonial" style="margin-bottom:12px">
          <p>“I came to Kathryn broken and uncertain. After her Reiki sessions, my energy shifted, and I found peace within myself. Days later, the person I’d been manifesting reached out. Her work is real and filled with love.”</p>
          <div class="test-author">— Elena R., California</div>
        </article>

        <article class="testimonial" style="margin-bottom:12px">
          <p>“Her guidance and rituals restored my faith in love. I can truly say Kathryn brought warmth and light into my life when everything felt lost. She’s a blessing.”</p>
          <div class="test-author">— Samantha L., Texas</div>
        </article>

        <article class="testimonial" style="margin-bottom:12px">
          <p>“At first, I was skeptical. But Kathryn’s calm energy and authenticity changed everything. Not only did her ritual bring my partner back, but I also feel spiritually stronger. Thank you, Kathryn.”</p>
          <div class="test-author">— Michael T., London</div>
        </article>

      </div>
    </div>

    <aside>
      <div class="contact" id="contact">
        <h3>Contact &amp; Booking</h3>
        <p class="muted">Ready to begin your healing journey or book a custom ritual? Reach out and Kathryn will respond with available times and next steps.</p>

        <div style="margin-top:12px">
          <strong>Phone</strong>
          <p class="muted">+1 513-279-8334</p>

          <strong>Email</strong>
          <p class="muted">axiiilord@gmail.com</p>

          <strong>Address</strong>
          <p class="muted">504 E. Main St., PO Box 2025<br>Alliance, Ohio, United States</p>
        </div>

        <form id="contactForm" onsubmit="return sendMail();" style="margin-top:12px">
          <label for="name">Your name</label>
          <input id="name" name="name" placeholder="Your full name" required>

          <label for="email">Your email</label>
          <input id="email" name="email" type="email" placeholder="you@example.com" required>

          <label for="message">Message</label>
          <textarea id="message" name="message" placeholder="Tell Kathryn a little about what you need..." required></textarea>

          <div style="display:flex;gap:8px;margin-top:10px">
            <button type="submit" class="btn btn-primary">Send Message</button>
            <a class="btn" href="mailto:axiiilord@gmail.com?subject=Booking%20Inquiry%20for%20Kathryn%20Sara">Or email directly</a>
          </div>
          <p id="formNote" class="muted" style="margin-top:10px">We reply within 48 hours. All sessions are confidential.</p>
        </form>

      </div>

      <div class="card" style="margin-top:14px">
        <h3>Ethical Practice</h3>
        <p class="muted">Kathryn performs spells and rituals with consent, integrity, and a focus on the highest good of all. No manipulative workings are performed.</p>
      </div>
    </aside>
  </section>

</main>

<footer>
  <div>
    <div style="display:flex;align-items:center;gap:10px">
      <div class="logo" style="width:44px;height:44px;font-size:16px">KS</div>
      <div style="line-height:1">
        <strong>Kathryn Sara</strong>
        <div class="muted" style="font-size:13px">High Priestess of Love &amp; Healing</div>
      </div>
    </div>
  </div>
  <div class="muted">© <span id="year"></span> Kathryn Sara — All rights reserved</div>
</footer>

  </div>  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    function sendMail(){
      // Build a mailto link from the form so the user's email opens in their client.
      var name = encodeURIComponent(document.getElementById('name').value || '');
      var email = encodeURIComponent(document.getElementById('email').value || '');
      var message = encodeURIComponent(document.getElementById('message').value || '');
      var subject = encodeURIComponent('Booking inquiry from ' + name);
      var body = encodeURIComponent('Name: ' + name + '\nEmail: ' + email + '\n\nMessage:\n' + message);
      var mailto = 'mailto:axiiilord@gmail.com?subject=' + subject + '&body=' + body;
      window.location.href = mailto;
      return false; // prevent actual form submission
    }
  </script></body>
</html>
