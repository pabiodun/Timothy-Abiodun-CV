<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cinematographer — TIMOTHY ABIODUN</title>
  <meta name="description" content="Cinematographer CV / showreel link / equipment list / credits" />
  <style>
    /* Simple, print-friendly CV layout */
    :root{
      --accent: #1f6feb;
      --muted: #6b7280;
      --bg: #ffffff;
      --text: #0f172a;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--text);line-height:1.45;padding:20px}
    .container{max-width:900px;margin:0 auto;border:1px solid #e6eefc;padding:28px;border-radius:8px}

    header{display:flex;gap:20px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:8px;background:#f3f4f6;display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--muted)}
    h1{margin:0;font-size:24px}
    h2{margin:0;font-size:14px;color:var(--muted)}

    .contact{margin-left:auto;text-align:right}
    .contact a{color:var(--accent);text-decoration:none}

    .summary{margin:18px 0;padding:16px;border-left:4px solid var(--accent);background:#fbfdff}

    .grid{display:grid;grid-template-columns:2fr 1fr;gap:20px}

    section.card{background:#ffffff;padding:14px;border-radius:6px}
    .section-title{display:flex;align-items:center;justify-content:space-between;margin-bottom:10px}
    .section-title h3{margin:0;font-size:16px}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{padding:6px 10px;border-radius:16px;border:1px solid #e6eefc;font-size:13px;color:var(--muted)}

    ul{margin:0;padding-left:18px}
    .credits li{margin-bottom:8px}
    .meta{font-size:13px;color:var(--muted)}

    .equipment{font-size:14px}
    .reel{display:inline-block;padding:8px 12px;border-radius:6px;background:var(--accent);color:#fff;text-decoration:none}

    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}

    /* Responsive */
    @media (max-width:700px){
      .grid{grid-template-columns:1fr}
      .contact{text-align:left;margin-left:0}
      header{flex-direction:row}
    }

    /* Print tweaks */
    @media print{
      body{padding:0}
      .container{border:0;padding:0}
      .reel{display:inline-block}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">[P img.jpg]</div>
      <div>
        <h1>TIMOTHY ABIODUN</h1>
        <h2>Cinematographer / Director of Photography</h2>
        <div class="meta">Based in City, Country • Available for film, commercial & music video projects</div>
      </div>

      <div class="contact">
        <div class="meta">Email: <a href="mailto:you@example.com">you@example.com</a></div>
        <div class="meta">Phone: +234 8033111178</div>
        <div class="meta">Website: <a href="https://example.com" target="_blank">example.com</a></div>
        <div style="margin-top:8px"><a class="reel" href="https://vimeo.com/yourreel" target="_blank">Watch Reel</a></div>
      </div>
    </header>

    <div class="summary">
      <strong>Profile</strong>
      <p style="margin:8px 0 0 0">Creative and technically skilled cinematographer with 10+ years experience in narrative film, commercials, and music videos. Comfortable leading camera and lighting departments, planning look development, and collaborating closely with directors to realise visual storytelling goals.</p>
    </div>

    <div class="grid">
      <main>
        <section class="card">
          <div class="section-title">
            <h3>Selected Credits</h3>
            <div class="meta">(Camera / DoP)</div>
          </div>
          <ul class="credits">
            <li><strong>Feature — "Title of Film"</strong> (Director's Name) — DoP — <span class="meta">2024</span>
              <div class="meta">Notes: 35mm look, pushed color grade, night exterior driving sequences.</div>
            </li>
            <li><strong>Short — "Another Title"</strong> (Director) — DoP — <span class="meta">2023</span>
              <div class="meta">Festival: Sundance 2024 (Official Selection)</div>
            </li>
            <li><strong>Commercial — Brand Name</strong> — Camera / Lighting — <span class="meta">2022</span></li>
            <li><strong>Music Video — Artist Name</strong> — DoP — <span class="meta">2021</span></li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title"><h3>Experience</h3><div class="meta">Previous Roles</div></div>
          <ul>
            <li><strong>Director of Photography</strong> — Freelance (2018 — Present)
              <div class="meta">Responsibilities: Lighting design, camera/crew management, look development, camera movement & framing.</div>
            </li>
            <li style="margin-top:8px"><strong>Camera Operator</strong> — Production Company (2015 — 2018)
              <div class="meta">Worked across commercials and short films; familiar with Arri, RED, Sony cinema cameras.</div>
            </li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title"><h3>Education & Training</h3><div class="meta">Relevant courses</div></div>
          <ul>
            <li><strong>B.A. Film Production</strong> — Film School Name — <span class="meta">2012 — 2015</span></li>
            <li><strong>Advanced Lighting Workshop</strong> — [Instructor/Company] — <span class="meta">2020</span></li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title"><h3>Awards & Festivals</h3><div class="meta"></div></div>
          <ul>
            <li>Best Cinematography — Short Film Festival — <span class="meta">2023</span></li>
            <li>Official Selection — Sundance Film Festival — <span class="meta">2024</span></li>
          </ul>
        </section>
      </main>

      <aside>
        <section class="card">
          <div class="section-title"><h3>Key Skills</h3><div class="meta">Technical & creative</div></div>
          <div class="skills">
            <div class="skill">Lighting Design</div>
            <div class="skill">Camera Operation</div>
            <div class="skill">Color Grading (DaVinci)</div>
            <div class="skill">Gimbal & Crane</div>
            <div class="skill">Digital & Film Workflows</div>
            <div class="skill">Look Development</div>
            <div class="skill">Crew Management</div>
            <div class="skill">Storyboarding</div>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title"><h3>Equipment (select)</h3><div class="meta">Cameras & Lenses</div></div>
          <div class="equipment">
            <ul>
              <li>Arri Alexa Mini / LF</li>
              <li>RED Komodo / RED V-RAPTOR (optional)</li>
              <li>Canon / Zeiss CP.2 lenses</li>
              <li>Cooke S4/i (when requested)</li>
              <li>Gimbal: Ronin 2 / Movi Pro</li>
              <li>Lighting: ARRI Skypanel, Kino Flo, HMI kits</li>
            </ul>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title"><h3>Languages</h3><div class="meta"></div></div>
          <ul>
            <li>English — Native</li>
            <li>French — Conversational</li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title"><h3>References</h3><div class="meta">Available on request</div></div>
          <p class="meta">References and full credits list available on request or via website.</p>
        </section>
      </aside>
    </div>

    <footer>
      <div>Updated: <span class="meta">[November 2025]</span> • PDF-friendly | Print to PDF for a one-page CV</div>
    </footer>
  </div>
</body>
</html>
