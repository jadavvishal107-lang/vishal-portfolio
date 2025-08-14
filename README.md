<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vishal Jadav — Graphic Designer</title>
  <meta name="description" content="Portfolio of Vishal Jadav — Graphic Designer from Ahmedabad, Gujarat. Video editing, photo editing, thumbnails for YouTubers." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b0d10;          /* matte near-black */
      --bg-soft:#11151a;     /* card bg */
      --text:#e8edf3;        /* main text */
      --muted:#9aa6b2;       /* muted text */
      --accent:#1fb6ff;      /* electric blue */
      --accent-2:#22d3a3;    /* teal green */
      --ring: rgba(31,182,255,.35);
      --radius: 18px;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:linear-gradient(180deg,var(--bg),#0d1117 40%, var(--bg));color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;scroll-behavior:smooth}
    a{color:var(--accent);text-decoration:none}
    a:hover{opacity:.9}
    .container{max-width:1100px;margin:0 auto;padding:28px}
    header{position:sticky;top:0;background:linear-gradient(180deg,rgba(11,13,16,.9),rgba(11,13,16,.65));backdrop-filter: blur(8px);border-bottom:1px solid rgba(255,255,255,.06);z-index:50}
    nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px;font-weight:800;letter-spacing:.5px}
    .brand .dot{width:10px;height:10px;border-radius:50%;background:linear-gradient(135deg,var(--accent),var(--accent-2));box-shadow:0 0 20px var(--accent)}
    .links a{margin-left:16px;color:var(--text)}
    .links a span{opacity:.8}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:10px 16px;border-radius:999px;background:linear-gradient(135deg,var(--accent),var(--accent-2));color:#001015;font-weight:700;border:none;box-shadow:0 8px 20px var(--ring)}.hero{display:grid;grid-template-columns:1.2fr .8fr;gap:28px;align-items:center;padding:64px 0}
.card{background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,.01));border:1px solid rgba(255,255,255,.08);border-radius:var(--radius);box-shadow:var(--shadow)}
.hero .left{padding:32px}
.pill{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:999px;background:rgba(34,211,163,.1);border:1px solid rgba(34,211,163,.25);color:#98f5e1;font-weight:600}
h1{font-size:48px;line-height:1.05;margin:14px 0 10px}
.tagline{font-size:20px;color:var(--muted)}
.hero-actions{margin-top:24px;display:flex;flex-wrap:wrap;gap:12px}

.profile{display:flex;align-items:center;justify-content:center;padding:24px}
.pfp{width:240px;height:240px;border-radius:22px;background:linear-gradient(135deg,#0e141b,#0a0f14);border:1px dashed rgba(255,255,255,.12);display:grid;place-items:center;position:relative;overflow:hidden}
.pfp::after{content:"VJ";font-size:72px;font-weight:800;letter-spacing:2px;background:linear-gradient(135deg,var(--accent),var(--accent-2));-webkit-background-clip:text;background-clip:text;color:transparent}

section{padding:26px 0}
.section-title{font-size:26px;margin:0 0 14px}
.grid{display:grid;gap:18px}
.two{grid-template-columns:1fr 1fr}
.three{grid-template-columns:repeat(3,1fr)}
.chip{display:inline-flex;align-items:center;gap:10px;padding:10px 12px;border-radius:14px;background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08)}
.muted{color:var(--muted)}

.project{padding:18px;border-radius:16px;background:linear-gradient(180deg,rgba(255,255,255,.03),rgba(255,255,255,.02));border:1px solid rgba(255,255,255,.08)}
.project h3{margin:6px 0 6px}
.project p{margin:0}

.contact-card{display:grid;gap:14px;padding:20px}
.contact-item{display:flex;align-items:center;gap:12px}
.icon{width:18px;height:18px;opacity:.9}

footer{padding:28px 0;color:var(--muted);border-top:1px solid rgba(255,255,255,.06);margin-top:36px}

@media (max-width: 900px){
  .hero{grid-template-columns:1fr}
  h1{font-size:38px}
  .three{grid-template-columns:1fr}
  .two{grid-template-columns:1fr}
  .pfp{width:200px;height:200px}
}

  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="brand"><span class="dot"></span> Vishal Jadav</div>
        <div class="links">
          <a href="#about"><span>About</span></a>
          <a href="#skills"><span>Skills</span></a>
          <a href="#projects"><span>Projects</span></a>
          <a href="#contact"><span>Contact</span></a>
        </div>
      </nav>
    </div>
  </header>  <main class="container">
    <section class="hero">
      <div class="left card">
        <span class="pill">Graphic Designer</span>
        <h1>Hi, I'm Vishal</h1>
        <p class="tagline">Graphic designer from Ahmedabad, Gujarat. I create high-impact thumbnails, visuals and clean edits for creators and brands.</p>
        <div class="hero-actions">
          <a class="btn" href="#contact">Contact Me</a>
          <a class="chip" href="tel:+919313710121">📞 9313710121</a>
          <a class="chip" href="mailto:jadavvishal107@gmail.com">✉️ Email</a>
        </div>
      </div>
      <div class="profile card">
        <div class="pfp" title="Add your photo by replacing this block in code"></div>
      </div>
    </section><section id="about">
  <h2 class="section-title">About Me</h2>
  <div class="card" style="padding:20px">
    <p>Hello, my name is <strong>Vishal Jadav</strong> & I'm from <strong>Ahmedabad, Gujarat</strong>. I'm a professional <strong>graphic designer</strong> with a focus on video editing and photo editing.</p>
  </div>
</section>

<section id="skills">
  <h2 class="section-title">Skills</h2>
  <div class="grid two">
    <div class="card chip"><svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4 6h16v12H4z" stroke="currentColor" stroke-width="1.5"/><path d="M4 15h16" stroke="currentColor" stroke-width="1.5"/><path d="M9 18h6" stroke="currentColor" stroke-width="1.5"/></svg> Video Editing</div>
    <div class="card chip"><svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><rect x="3" y="3" width="18" height="18" rx="2" stroke="currentColor" stroke-width="1.5"/><path d="M7 17l10-10" stroke="currentColor" stroke-width="1.5"/></svg> Photo Editing</div>
  </div>
  <p class="muted" style="margin-top:10px">Tools I use: Premiere Pro, After Effects, Photoshop (add or edit in code).</p>
</section>

<section id="projects">
  <h2 class="section-title">Selected Projects</h2>
  <div class="grid three">
    <div class="project card">
      <h3>YouTube Video Edits</h3>
      <p class="muted">Edited videos for creators including <strong>Dhruv Rathee</strong>, <strong>Harsh Beniwal</strong>, and <strong>Techno Gamerz</strong>.</p>
    </div>
    <div class="project card">
      <h3>Custom Thumbnails</h3>
      <p class="muted">Designed engaging thumbnails that improved click-through and brand consistency.</p>
    </div>
    <div class="project card">
      <h3>Brand Visuals</h3>
      <p class="muted">Clean, modern social media graphics and short-form edits for campaigns.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2 class="section-title">Contact</h2>
  <div class="card contact-card">
    <div class="contact-item"><svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2 5a2 2 0 012-2h3l2 5-2 1a15 15 0 006 6l1-2 5 2v3a2 2 0 01-2 2h-1C9.163 20 4 14.837 4 8V7a2 2 0 01-2-2z" stroke="currentColor" stroke-width="1.5"/></svg> <a href="tel:+919313710121">+91 9313710121</a></div>
    <div class="contact-item"><svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4 4h16v16H4z" stroke="currentColor" stroke-width="1.5"/><path d="M4 7l8 6 8-6" stroke="currentColor" stroke-width="1.5"/></svg> <a href="mailto:jadavvishal107@gmail.com">jadavvishal107@gmail.com</a></div>
    <div class="contact-item"><svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><circle cx="12" cy="12" r="10" stroke="currentColor" stroke-width="1.5"/><path d="M8 12h8M12 8v8" stroke="currentColor" stroke-width="1.5"/></svg> <a href="https://instagram.com/vishal_.sadhu" target="_blank" rel="noopener">Instagram: @vishal_.sadhu</a></div>
    <div class="contact-item"><svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M3 7h18v10H3z" stroke="currentColor" stroke-width="1.5"/><path d="M7 7v10M17 7v10" stroke="currentColor" stroke-width="1.5"/></svg> <a href="https://facebook.com/sadhu_vishal" target="_blank" rel="noopener">Facebook: @sadhu_vishal</a></div>
  </div>
</section>

<footer>
  <div class="container" style="padding:0">
    © <span id="year"></span> Vishal Jadav. All rights reserved.
  </div>
</footer>

  </main>  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
</html>
