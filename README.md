<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Luméé — Noir Collection | Own Your Light</title>
  <meta name="description" content="Luméé Noir Collection — Parisian chic eyewear. Chic. Classic. Unapologetically Parisian. Join the waitlist." />
  <meta property="og:title" content="Luméé — Noir Collection" />
  <meta property="og:description" content="Chic. Classic. Unapologetically Parisian. Join the waitlist." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://images.unsplash.com/photo-1469474968028-56623f02e42e?q=80&w=1200&auto=format&fit=crop" />
  <meta name="theme-color" content="#0b0b0c" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b0b0c; --fg:#f5f3ef; --muted:#c6c2b6; --gold:#d4af37; --card:#121214;
      --max:1120px;
    }
    *{box-sizing:border-box}
    html,body{margin:0; padding:0; background:var(--bg); color:var(--fg); font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif}
    img{max-width:100%; display:block}
    a{color:var(--fg); text-decoration:none}
    .container{max-width:var(--max); margin:0 auto; padding:0 20px}
    .btn{display:inline-block; padding:14px 22px; border:1px solid var(--gold); color:var(--fg); letter-spacing:.06em; text-transform:uppercase; font-weight:600; transition:.25s ease; background:transparent}
    .btn:hover{background:var(--gold); color:#111}
    header{position:sticky; top:0; backdrop-filter:saturate(120%) blur(8px); background:rgba(11,11,12,.6); border-bottom:1px solid rgba(212,175,55,.25); z-index:50}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:16px 0}
    .brand{font-family:'Playfair Display',serif; font-weight:700; letter-spacing:.18em}
    .accent{color:var(--gold)}
    .hero{position:relative; min-height:84vh; display:grid; place-items:center; text-align:center; overflow:hidden}
    .hero::before{content:""; position:absolute; inset:0; background:url('https://images.unsplash.com/photo-1483721310020-03333e577078?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat; filter:grayscale(100%) contrast(1.1) brightness(.65)}
    .hero-inner{position:relative; padding:64px 20px}
    .kicker{letter-spacing:.28em; text-transform:uppercase; color:var(--muted); font-size:.78rem}
    .title{font-family:'Playfair Display',serif; font-weight:700; font-size:clamp(36px,6vw,68px); line-height:1.05; margin:.2em 0}
    .subtitle{color:var(--muted); max-width:760px; margin:12px auto 28px; font-size:1.06rem}

    .split{display:grid; gap:36px; grid-template-columns:1fr; padding:84px 0; border-top:1px solid #1e1e22; border-bottom:1px solid #1e1e22}
    @media(min-width:900px){ .split{grid-template-columns:1.1fr .9fr} }
    .card{background:var(--card); padding:28px; border:1px solid #1b1b1f}
    .h2{font-family:'Playfair Display',serif; font-size:clamp(26px,4.2vw,40px); margin:0 0 10px}
    .muted{color:var(--muted)}
    .features{display:grid; gap:18px; margin-top:18px}
    .feat{display:flex; gap:12px; align-items:flex-start}
    .dot{width:8px; height:8px; border-radius:50%; background:var(--gold); margin-top:9px}

    .gallery{display:grid; gap:16px; grid-template-columns:1fr; margin:42px 0}
    @media(min-width:800px){ .gallery{grid-template-columns:1.2fr .8fr} }

    .quote{padding:68px 0; text-align:center}
    .quote blockquote{font-family:'Playfair Display',serif; font-size:clamp(22px,3.5vw,32px); margin:0 auto; max-width:840px}
    .quote cite{display:block; margin-top:10px; color:var(--muted); font-style:normal}

    .cta{padding:84px 0; text-align:center}
    footer{padding:36px 0; color:var(--muted)}
    .footer-grid{display:flex; flex-wrap:wrap; gap:12px; align-items:center; justify-content:space-between}
    .small{font-size:.9rem}
    /* Utility */
    .shadow{box-shadow:0 10px 30px rgba(0,0,0,.45)}
    .rounded{border-radius:14px}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">LUM<span class="accent">ÉÉ</span></div>
      <nav class="small"><a href="#noir">Noir Collection</a> &nbsp;•&nbsp; <a href="#story">Our Story</a> &nbsp;•&nbsp; <a href="#waitlist">Waitlist</a></nav>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero" id="top" aria-label="Luméé Noir hero">
      <div class="hero-inner container">
        <p class="kicker">Paris — Est. 2000s</p>
        <h1 class="title">Own Your Light</h1>
        <p class="subtitle">Introducing the <strong>Noir Collection</strong> — chic silhouettes and classic lines crafted with French precision. Unapologetically Parisian.</p>
        <a class="btn" href="#waitlist">Join the Waitlist</a>
      </div>
    </section>

    <!-- PRODUCT / STORY SPLIT -->
    <section class="split container" id="noir">
      <div class="card shadow rounded">
        <img class="rounded" alt="Luméé Noir sunglasses on marble with case" src="https://images.unsplash.com/photo-1520975916090-3105956dac38?q=80&w=1400&auto=format&fit=crop" />
        <div style="margin-top:18px">
          <h2 class="h2">The Noir Collection</h2>
          <p class="muted">Oversized, sculpted frames with UV protection — a statement piece designed for city light.</p>
          <div class="features">
            <div class="feat"><span class="dot"></span><div><strong>Parisian Chic</strong><br/><span class="muted">Bold geometry inspired by Haussmann lines.</span></div></div>
            <div class="feat"><span class="dot"></span><div><strong>Luxury Craft</strong><br/><span class="muted">Hand-finished details, premium materials.</span></div></div>
            <div class="feat"><span class="dot"></span><div><strong>Signature Case</strong><br/><span class="muted">Matte-black pebbled case with gold emboss.</span></div></div>
          </div>
        </div>
      </div>
      <div class="card shadow rounded" id="story">
        <h2 class="h2">A French Story Since the 2000s</h2>
        <p class="muted">Born from a Marais atelier, Lumée blends timeless French craftsmanship with a modern, unapologetic aesthetic. Every curve and contour nods to Paris — the city that taught us to turn light into style.</p>
        <div class="gallery">
          <img class="rounded" alt="Paris street in black and white" src="https://images.unsplash.com/photo-1483721310020-03333e577078?q=80&w=1200&auto=format&fit=crop" />
          <img class="rounded" alt="Lifestyle shot with sunglasses" src="https://images.unsplash.com/photo-1520975916090-3105956dac38?q=80&w=1200&auto=format&fit=crop" />
        </div>
        <a class="btn" href="#waitlist">Be First to Know</a>
      </div>
    </section>

    <!-- QUOTE -->
    <section class="quote">
      <div class="container">
        <blockquote>“Chic yet timeless — a Parisian statement for every day.”<cite>— Editorial, Noir Launch</cite></blockquote>
      </div>
    </section>

    <!-- FINAL CTA -->
    <section class="cta" id="waitlist">
      <div class="container">
        <h2 class="h2" style="margin-bottom:6px">Limited Release</h2>
        <p class="muted" style="margin-top:0">First drop opens soon. Join the list for early access and insider previews.</p>
        <!-- 👉 Replace the href below with your Google Form / Typeform / Mailchimp URL  -->
        <a class="btn" href="https://forms.gle/placeholder" target="_blank" rel="noopener">Join the Waitlist</a>
        <p class="small muted" style="margin-top:14px">Portfolio project — concept by YOUR NAME.</p>
      </div>
    </section>
  </main>

  <footer>
    <div class="container footer-grid">
      <div class="small">© <span class="brand">LUM<span class="accent">ÉÉ</span></span> — Noir Collection</div>
      <div class="small"><a href="https://instagram.com/lumee.eyewear" target="_blank" rel="noopener">@lumee.eyewear</a> &nbsp;•&nbsp; #MyLumeeLook</div>
    </div>
  </footer>
</body>
</html>
