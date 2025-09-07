<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Genrev Fernandez.dev</title>
  <style>
    :root{
      --bg: #0b1020;
      --card: #121a33;
      --muted: #8da2d6;
      --text: #e8eeff;
      --accent: #7aa2ff;
      --ring: rgba(122,162,255,.35);
      --chip: #1a2346;
      --chip-border: #2a3b78;
      --shadow: 0 10px 30px rgba(2, 6, 23, .5);
      --radius-xl: 22px;
      --radius-lg: 14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font: 16px/1.6 system-ui, sans-serif;
      color:var(--text);
      background: var(--bg);
      display:grid;
      place-items:center;
      padding:24px;
    }
    .card{
      width:min(920px, 100%);
      background:var(--card);
      border:1px solid rgba(255,255,255,.06);
      box-shadow:var(--shadow);
      border-radius:var(--radius-xl);
      overflow:hidden;
    }
    .banner{
      height:120px;
      background: conic-gradient(from 210deg at 70% 10%, #2b3e7d, #1f2f63, #2b3e7d);
    }
    .wrap{
      padding:22px 32px 28px;
      display:grid;
      gap:22px;
      grid-template-columns: 160px 1fr;
    }
    @media (max-width:720px){
      .wrap{ grid-template-columns: 1fr; }
      .avatar{ margin:-72px auto 0 auto; }
    }

    .avatar{
      margin-top:-84px;
      position:relative;
      width:160px;height:160px;
      border-radius:28px;
      border:1px solid rgba(255,255,255,.08);
      overflow:hidden;
    }
    .avatar img{
      width:100%;height:100%;object-fit:cover;
      display:block;
    }

    .header {
  display: flex;
  align-items: flex-end;
  gap: 14px;
  flex-wrap: wrap;
  padding-block: 8px;
  margin-top: 55px; 
}

    h1{ font-size:26px; margin:0; }
    .role{
      font-weight:600;
      color:var(--accent);
      background:rgba(122,162,255,.12);
      border:1px solid var(--ring);
      padding:4px 10px;
      border-radius:999px;
    }
    .about{ color:var(--muted); margin-top:4px; }

    .grid{ display:grid; gap:14px; grid-template-columns: repeat(2, 1fr); }
    @media (max-width:560px){ .grid{ grid-template-columns:1fr; } }
    .item{
      background:rgba(255,255,255,.04);
      border:1px solid rgba(255,255,255,.08);
      padding:14px 16px;
      border-radius:var(--radius-lg);
    }
    .label{ font-size:12px; color:var(--muted); text-transform:uppercase; }
    .value{ font-weight:600; margin-top:4px; }

    .chips{ display:flex; flex-wrap:wrap; gap:8px; margin-top:8px; }
    .chip{
      background:var(--chip);
      border:1px solid var(--chip-border);
      padding:6px 10px; border-radius:999px; font-size:14px;
    }

    .contact{ display:flex; gap:10px; flex-wrap:wrap; margin-top:12px; }
    .btn{
      display:inline-flex; align-items:center; gap:8px;
      border:1px solid var(--ring);
      background:rgba(122,162,255,.1);
      padding:10px 14px; border-radius:12px;
      text-decoration:none; color:var(--text);
    }
  </style>
</head>
<body>
  <article class="card">
    <div class="banner"></div>
    <div class="wrap">
      <figure class="avatar">
        <img src="Fernandez_logo.jpg" alt="Avatar of Genrev Carl Fernandez">
      </figure>

      <section>
        <div class="header">
          <h1 id="name">Genrev Carl Fernandez</h1>
          <span class="role">3rd Year IT Student</span>
        </div>
        <p class="about">
          Passionate about crafting fast, accessible, and beautiful web experiences.
          Enjoys design systems, CSS architecture, and a good cup of coffee (Caramel Macchiato).
        </p>

        <div class="grid">
          <div class="item"><div class="label">Email</div><div class="value">genrevcarlfernandez25@gmail.com</div></div>
          <div class="item"><div class="label">Phone</div><div class="value">+63 970 723 0884</div></div>
          <div class="item"><div class="label">Location</div><div class="value">Ilocos Sur, Philippines</div></div>
          <div class="item"><div class="label">Birthday</div><div class="value">October 25, 2004</div></div>
          <div class="item"><div class="label">Education</div><div class="value">BSIT Student - ISPSC</div></div>
          <div class="item"><div class="label">Website</div><div class="value">genrev.dev</div></div>
        </div>

        <h2 style="margin:18px 0 6px 0; font-size:18px">Skills</h2>
        <div class="chips">
          <span class="chip">HTML</span>
          <span class="chip">CSS</span>
          <span class="chip">a bit of JavaScript</span>
          <span class="chip">a bit of PHP</span>

          
        </div>

        <h2 style="margin:18px 0 6px 0; font-size:18px">Contact</h2>
        <div class="contact">
          <a class="btn" href="mailto:genrevcarlfernandez25@gmail.com">✉️ Email</a>
          <a class="btn" href="tel:+639707230884">📞 Call</a>
          <a class="btn" href="#">🌐 Facebook</a>
          
        </div>
      </section>
    </div>
  </article>
</body>
</html>
\
