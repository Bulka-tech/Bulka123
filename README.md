<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Rocket League Fan Site</title>
  <meta name="description" content="A simple GitHub Pages site about Rocket League — tips, modes, cars, and community links." />
  <style>
    :root{--accent:#ff6b00;--bg:#0b1220;--card:#0f1724;--muted:#9aa5b1}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,Helvetica,Arial;background:linear-gradient(180deg,#07101a 0%,#081828 60%);color:#e6eef6}
    header{padding:28px 16px;display:flex;align-items:center;justify-content:space-between;gap:16px}
    .logo{display:flex;align-items:center;gap:10px}
    .logo .mark{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,#ff8b3d,#ff3b8f);display:flex;align-items:center;justify-content:center;font-weight:700}
    nav a{color:var(--muted);text-decoration:none;margin-left:14px}
    .hero{padding:48px 16px 36px;display:grid;grid-template-columns:1fr;gap:20px;max-width:1100px;margin:0 auto}
    .hero .card{background:rgba(255,255,255,0.03);padding:22px;border-radius:12px}
    h1{font-size:38px;margin:0 0 6px}
    p.lead{margin:0;color:var(--muted)}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:18px}
    .tile{background:var(--card);padding:16px;border-radius:10px}
    .section{max-width:1100px;margin:28px auto;padding:0 16px}
    .two{display:grid;grid-template-columns:1fr 360px;gap:18px}
    ul.list{padding-left:18px;color:var(--muted)}
    footer{padding:20px;text-align:center;color:var(--muted)}
    a.btn{display:inline-block;background:var(--accent);color:#05121a;padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:600}
    code{background:#00121a;padding:6px;border-radius:6px;color:#8be7ff}
    @media (max-width:900px){.grid{grid-template-columns:1fr}.two{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <div class="mark">RL</div>
      <div>
        <div style="font-weight:700">Rocket League Fan Site</div>
        <div style="font-size:12px;color:var(--muted)">Guides, modes, cars, and quick tips</div>
      </div>
    </div>
    <nav>
      <a href="#about">About</a>
      <a href="#modes">Modes</a>
      <a href="#tips">Tips</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="card">
        <h1>Rocket League — quick fan site</h1>
        <p class="lead">A simple, responsive GitHub Pages-ready site with gameplay overviews, tips for beginners, and community links. Perfect as a school project or fan landing page.</p>
        <div style="margin-top:12px">
          <a class="btn" href="#modes">Explore modes</a>
        </div>
      </div>

      <div class="grid">
        <div class="tile">
          <h3>What is Rocket League?</h3>
          <p class="lead">Rocket League is a high-energy vehicular soccer game where players control rocket-powered cars to hit a ball into the opponent's goal. Matches reward team coordination, aerial control, and smart use of boost.</p>
        </div>

        <div class="tile">
          <h3>Top features</h3>
          <ul class="list">
            <li>Cross-platform multiplayer</li>
            <li>Competitive ranked play and casual modes</li>
            <li>Custom cars, cosmetics, and esports events</li>
          </ul>
        </div>

        <div class="tile">
          <h3>Quick stats</h3>
          <ul class="list">
            <li>Team sizes: 1v1, 2v2, 3v3, 4v4</li>
            <li>Match length: ~5 minutes</li>
            <li>Key mechanics: flipping, aerials, boost management</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="about" class="section">
      <div class="two">
        <div>
          <h2>About the game</h2>
          <p>Rocket League blends driving and sports gameplay. Beginners should focus on camera settings, simple dribbling, and conserving boost. Advanced players practice aerials, rotations, and kickoff diversity.</p>

          <h3 id="modes">Main modes</h3>
          <ul class="list">
            <li><strong>Casual</strong> — fun quick matches without rank pressure.</li>
            <li><strong>Competitive</strong> — ranked ladder with divisions and seasons.</li>
            <li><strong>Extra Modes</strong> — Hoops (basketball), Rumble (power-ups), Dropshot (floor damage).</li>
          </ul>

          <h3 id="tips">Beginner tips</h3>
          <ol class="list">
            <li>Start with free play to practice ball control.</li>
            <li>Use small camera distance and faster rotation speed for better spatial awareness.</li>
            <li>Always rotate back into defense —don't chase the ball together.</li>
            <li>Pick up boost pads (12 boost) and save big pads (100 boost) for important plays.</li>
          </ol>
        </div>

        <aside class="tile">
          <h3>Quick links</h3>
          <p class="lead">Useful resources</p>
          <ul class="list">
            <li><a href="https://www.rocketleague.com" target="_blank" rel="noopener noreferrer">Official site</a></li>
            <li><a href="https://www.reddit.com/r/RocketLeague" target="_blank" rel="noopener noreferrer">r/RocketLeague</a></li>
            <li><a href="https://prosettings.net/rocket-league" target="_blank" rel="noopener noreferrer">Pro settings & guides</a></li>
          </ul>

          <h4 style="margin-top:12px">Embed</h4>
          <p class="lead">Paste a YouTube embed below to show a trailer or tutorial.</p>
          <div style="font-size:12px;background:#04131a;padding:10px;border-radius:8px;overflow:auto">
            <code>&lt;iframe width="100%" height="180" src="https://www.youtube.com/embed/VIDEO_ID" title="YouTube video" frameborder="0" allowfullscreen&gt;&lt;/iframe&gt;</code>
          </div>
        </aside>
      </div>
    </section>

    <section class="section">
      <div class="card" style="padding:18px">
        <h2>Car Guide — pick that style</h2>
        <p class="lead">All cars are cosmetic variants of hitboxes. Choose a car you like visually — consistency in camera and hitbox familiarity beats swapping constantly.</p>
        <div style="display:flex;gap:10px;margin-top:12px;flex-wrap:wrap">
          <div style="background:#071520;padding:12px;border-radius:10px;min-width:160px">Octane — balanced</div>
          <div style="background:#071520;padding:12px;border-radius:10px;min-width:160px">Fennec — Octane feel, boxy</div>
          <div style="background:#071520;padding:12px;border-radius:10px;min-width:160px">Dominus — longer hitbox</div>
        </div>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="tile">
        <h2>Make it your site</h2>
        <p class="lead">This file is ready to be published as <code>index.html</code> on GitHub Pages. To publish:</p>
        <ol class="list">
          <li>Create a new GitHub repository (public or personal site).</li>
          <li>Upload this file as <code>index.html</code> to the repository's root.</li>
          <li>Go to repository Settings → Pages and choose the main branch / root folder to publish.</li>
          <li>Wait a minute and your site will be available at <code>https://&lt;username&gt;.github.io/&lt;repo&gt;/</code>.</li>
        </ol>
        <p class="lead">Want me to customize the site (change colors, add your favorite car, or make a multi-page site)? Tell me what you want and I’ll update the code.</p>
      </div>
    </section>
  </main>

  <footer>
    Built for a quick GitHub Pages demo • Edit <code>index.html</code> to personalize • Good luck and have fun! 
  </footer>
</body>
</html>
