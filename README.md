[index.html](https://github.com/user-attachments/files/22590103/index.html)
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Nick Befort Coaching</title>
  <meta name="description" content="Online fitness coaching with custom training, nutrition plans, and weekly check-ins." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#0f1115;--card:#151923;--muted:#94a3b8;--text:#e5e7eb;--brand:#60a5fa;--ring:#93c5fd;}
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif}
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;padding:20px 0}
    .logo{font-weight:800;letter-spacing:.2px;font-size:20px}
    .badge{font-size:12px;color:var(--muted)}
    .btn{display:inline-block;padding:12px 18px;border-radius:12px;font-weight:600;border:1px solid #2a3343;background:#1b2230}
    .btn.primary{background:var(--brand);border-color:var(--brand);color:#0b1220;box-shadow:0 8px 20px rgba(96,165,250,.25)}
    .btn.ghost{background:transparent;border-color:#2a3343;color:var(--text)}
    .hero{display:grid;gap:18px;padding:56px 0}
    .hero h1{font-size:40px;line-height:1.1;margin:0}
    .hero p{color:var(--muted);font-size:16px;margin:0}
    .hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:8px}
    .grid{display:grid;gap:16px}
    @media(min-width:900px){.grid.cols-3{grid-template-columns:repeat(3,1fr)}.hero{grid-template-columns:1.2fr .8fr;align-items:center}}
    .card{background:linear-gradient(180deg,#151923, #121723);border:1px solid #22283a;border-radius:16px;padding:22px}
    .card h3{margin:0 0 8px 0;font-size:18px}
    .card p{margin:8px 0;color:var(--muted)}
    .features{display:grid;gap:10px;margin-top:12px}
    .feature{display:flex;gap:10px;align-items:flex-start;color:var(--muted);font-size:14px}
    .dot{width:8px;height:8px;border-radius:999px;background:var(--brand);margin-top:6px;flex:0 0 8px}
    .pricing{margin-top:10px}
    .price{font-size:28px;font-weight:800}
    .per{color:var(--muted);font-weight:600;margin-left:6px;font-size:14px}
    .cta{margin-top:14px;display:flex;gap:10px;flex-wrap:wrap}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:#0b1220;border:1px solid #1e2636;color:#9fb0ca;font-size:12px}
    .section-title{margin:40px 0 12px 0;font-size:22px}
    .row{display:grid;gap:16px}
    @media(min-width:900px){.row.cols-2{grid-template-columns:1fr 1fr}}
    .faq details{background:#0e1420;border:1px solid #1f2a3f;border-radius:14px;padding:14px}
    .faq summary{font-weight:600;cursor:pointer}
    footer{padding:40px 0;color:var(--muted);font-size:14px}
    .tag{font-size:11px;color:#cbd5e1;background:#0c1320;border:1px solid #1c2535;border-radius:999px;padding:4px 8px}
    .stripe-note{font-size:12px;color:#9aa7bd}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <div class="logo">Nick Befort Coaching</div>
        <div class="badge">Online Training • Nutrition • Accountability</div>
      </div>
      <nav>
        <a class="btn ghost" href="#pricing">Pricing</a>
        <a class="btn primary" href="#apply">Apply</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <h1>Build the body no one can touch.</h1>
        <p>1:1 online coaching designed for real progress: customized training plans, dialed-in nutrition, and weekly check-ins that keep you accountable.</p>
        <div class="hero-actions">
          <a class="btn primary" href="#pricing">See coaching options</a>
          <a class="btn ghost" href="mailto:nickbefort.coaching@gmail.com?subject=Coaching%20Inquiry">Email Nick</a>
        </div>
        <div style="margin-top:10px" class="stripe-note">Payments are processed securely via Stripe.</div>
      </div>
      <div class="card">
        <h3>What you get</h3>
        <div class="features">
          <div class="feature"><span class="dot"></span><div>Custom training split built around your goals and equipment</div></div>
          <div class="feature"><span class="dot"></span><div>Nutrition plan with gram-accurate macros and food lists</div></div>
          <div class="feature"><span class="dot"></span><div>Weekly check-ins with adjustments based on progress</div></div>
          <div class="feature"><span class="dot"></span><div>Form reviews, cues, and messaging support</div></div>
        </div>
        <div style="margin-top:14px"><span class="tag">Natural bodybuilding focused</span> <span class="tag">Faith & discipline</span> <span class="tag">Client-first</span></div>
      </div>
    </section>

    <h2 id="pricing" class="section-title">Pricing</h2>
    <div class="grid cols-3">
      <div class="card">
        <h3>Month-to-Month</h3>
        <div class="pricing">
          <span class="price">$100</span><span class="per">per month</span>
        </div>
        <p>Flexible start with full coaching access and weekly check-ins.</p>
        <div class="features">
          <div class="feature"><span class="dot"></span><div>Cancel anytime</div></div>
          <div class="feature"><span class="dot"></span><div>Training + nutrition + check-ins</div></div>
        </div>
        <div class="cta">
          <a class="btn primary" href="#" target="_blank" rel="noopener">Start month-to-month</a>
        </div>
      </div>

      <div class="card">
        <h3>3 Months (Paid in Full)</h3>
        <div class="pricing">
          <span class="price">$285</span><span class="per">one-time</span>
        </div>
        <p>Commit for a quarter and save versus monthly.</p>
        <div class="features">
          <div class="feature"><span class="dot"></span><div>All coaching features included</div></div>
          <div class="feature"><span class="dot"></span><div>Save $15 vs $300</div></div>
        </div>
        <div class="cta">
          <a class="btn primary" href="#" target="_blank" rel="noopener">Get 3 months</a>
          <span class="pill">Popular</span>
        </div>
      </div>

      <div class="card">
        <h3>6 Months (Paid in Full)</h3>
        <div class="pricing">
          <span class="price">$540</span><span class="per">one-time</span>
        </div>
        <p>Dial it in for the long game and save more.</p>
        <div class="features">
          <div class="feature"><span class="dot"></span><div>Progress phases + deloads mapped</div></div>
          <div class="feature"><span class="dot"></span><div>Save $60 vs $600</div></div>
        </div>
        <div class="cta">
          <a class="btn primary" href="#" target="_blank" rel="noopener">Get 6 months</a>
        </div>
      </div>
    </div>

    <div class="grid cols-3" style="margin-top:16px">
      <div class="card" style="grid-column:1 / -1">
        <h3>12 Months (Paid in Full)</h3>
        <div class="pricing">
          <span class="price">$999</span><span class="per">one-time</span>
        </div>
        <p>Best value — a full year of structure, adjustments, and accountability.</p>
        <div class="features">
          <div class="feature"><span class="dot"></span><div>Peak a show, rebuild, or recomposition</div></div>
          <div class="feature"><span class="dot"></span><div>Save $200+ vs $1,200</div></div>
        </div>
        <div class="cta">
          <a class="btn primary" href="#" target="_blank" rel="noopener">Get 12 months</a>
          <span class="pill">Best value</span>
        </div>
      </div>
    </div>

    <div class="row cols-2" id="apply" style="margin-top:24px">
      <div class="card">
        <h3>About Nick</h3>
        <p>Natural bodybuilding coach focused on sustainable results. I build programs you can actually stick to — with clarity, cues, and weekly feedback so you always know the next step.</p>
        <p>Ready to get started? Apply below and I’ll reply within 24 hours.</p>
        <div class="cta">
          <a class="btn primary" href="mailto:nickbefort.coaching@gmail.com?subject=Coaching%20Application&body=Name:%0AGoals:%0ATraining%20history:%0ACurrent%20weight/height:%0AInjuries/limits:%0A" target="_blank" rel="noopener">Apply via email</a>
          <a class="btn ghost" href="#" target="_blank" rel="noopener">Book a consult (link)</a>
        </div>
      </div>
      <div class="card faq">
        <h3>FAQ</h3>
        <details>
          <summary>What happens after I pay?</summary>
          <p>You’ll receive a confirmation email and an intake form. I’ll build your plan and send it with your first-week instructions.</p>
        </details>
        <details>
          <summary>Do you offer refunds?</summary>
          <p>Coaching is a service; refunds aren’t offered once programming is delivered. If something’s off, I’ll fix it fast.</p>
        </details>
        <details>
          <summary>How do check-ins work?</summary>
          <p>Weekly check-ins via email or WhatsApp with photos, weigh-ins, and notes. I adjust training/nutrition based on your progress.</p>
        </details>
      </div>
    </div>

    <footer>
      <div>© <span id="year"></span> Nick Befort Coaching • <a href="mailto:nickbefort.coaching@gmail.com">nickbefort.coaching@gmail.com</a></div>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
