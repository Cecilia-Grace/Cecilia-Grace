# Hi there, I'm Cecilia Grace Matini Nyanje! 👋

<img src="https://img.freepik.com/premium-photo/female-developer-background_665280-9660.jpg" alt="Female developer background | Premium AI-generated image"/>


<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GitHub Profile — README Template</title>
  <style>
    :root{ --bg:#0f1724; --card:#0b1220; --muted:#9aa4b2; --accent:#00bcd4; --glass:rgba(255,255,255,0.03); }
    *{box-sizing:border-box}
    body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, 'Helvetica Neue', Arial; margin:0; background:linear-gradient(180deg,#071122 0%, #07162a 100%); color:#e6eef6; -webkit-font-smoothing:antialiased}
    .wrap{max-width:980px;margin:36px auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:12px;box-shadow:0 6px 30px rgba(2,6,23,0.7);} 
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:14px;background:linear-gradient(135deg,#0ea5a4,#2563eb);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:42px;color:white}
    h1{margin:0;font-size:22px}
    .subtitle{color:var(--muted);margin-top:6px}
    .badges{display:flex;gap:8px;margin-top:12px;flex-wrap:wrap}
    .badge{display:inline-flex;gap:8px;align-items:center;padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--muted);font-weight:600;font-size:13px}

    .grid{display:grid;grid-template-columns:1fr 320px;gap:22px;margin-top:22px}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .section-title{font-size:14px;color:var(--accent);text-transform:uppercase;letter-spacing:0.08em;margin-bottom:10px}

    .about p{color:#dbe7f3;line-height:1.5;margin:0}
    .stack{display:flex;flex-wrap:wrap;gap:8px}
    .tech{background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:8px 10px;border-radius:8px;font-weight:600;color:var(--muted);font-size:13px}

    .projects{display:grid;grid-template-columns:1fr;gap:12px}
    .project{display:flex;flex-direction:column;gap:6px;padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.015), transparent)}
    .project h4{margin:0;font-size:15px}
    .project p{margin:0;color:var(--muted);font-size:13px}

    .stats{display:flex;flex-direction:column;gap:8px}
    .stat{display:flex;justify-content:space-between;padding:10px;border-radius:8px;background:var(--glass);font-weight:700}

    footer{margin-top:20px;color:var(--muted);font-size:13px;text-align:center}

    a{color:inherit;text-decoration:none}
    .cta{display:inline-block;margin-top:12px;padding:10px 14px;border-radius:999px;background:linear-gradient(90deg,#06b6d4,#2563eb);color:#071122;font-weight:700}

    /* responsive */
    @media (max-width:880px){.grid{grid-template-columns:1fr;}.avatar{width:92px;height:92px;font-size:34px}.wrap{margin:18px;padding:18px}}
  </style>
</head>
<body>
  <article class="wrap">
    <header>
      <div class="avatar">CE</div>
      <div>
        <h1>I'm <strong>Cecilia Grace Matini Nyanje</strong> — Backend Software Engineer</h1>
        <div class="subtitle">Passionate about low-level systems, automation, scalable backend services, and building tools that make engineers happier.</div>
        <div class="badges" aria-hidden>
          <span class="badge">⚙️ Backend • Systems</span>
          <span class="badge">📚 ALX Backend Engineering</span>
          <span class="badge">💡 Open to opportunities</span>
        </div>
      </div>
    </header>

    <div class="grid">
      <main>
        <section class="card about">
          <div class="section-title">About me</div>
          <p>I am a detail-oriented Software Engineer with experience in backend development. I enjoy tackling complex problems, learning new technologies, and collaborating with diverse teams to deliver meaningful solutions. I focus on writing clean, maintainable code and building reliable systems. I am actively learning low-level programming, scripting & automation, higher-level programming, web development, system design, and DevOps.</p>

          <a class="cta" href="#featured-projects">Featured Projects</a>
        </section>

        <section id="featured-projects" class="card" style="margin-top:14px">
          <div class="section-title">Featured projects</div>
          <div class="projects">
            <!-- Copy this block for each project -->
            <article class="project">
              <h4><a href="https://github.com/username/project-one" target="_blank">Project One — High-performance queue</a></h4>
              <p>Custom persistent job queue in C with a small Rust tool for monitoring. Focus: low-level concurrency, reliability, and benchmark-driven optimization.</p>
              <div style="display:flex;gap:8px;margin-top:8px"><span class="tech">C</span><span class="tech">Rust</span><span class="tech">Linux</span></div>
            </article>

            <article class="project">
              <h4><a href="https://github.com/username/project-two" target="_blank">Project Two — Automation Toolkit</a></h4>
              <p>Bash + Python toolkit to automate infrastructure tasks, CI helpers, and developer utilities. Focus: idempotency, tests, and clear docs.</p>
              <div style="display:flex;gap:8px;margin-top:8px"><span class="tech">Bash</span><span class="tech">Python</span><span class="tech">Docker</span></div>
            </article>

            <article class="project">
              <h4><a href="https://github.com/username/project-three" target="_blank">Project Three — Web Service</a></h4>
              <p>Scalable REST API with async workers, health checks, and observability. Shows system design and production readiness.</p>
              <div style="display:flex;gap:8px;margin-top:8px"><span class="tech">Go</span><span class="tech">Postgres</span><span class="tech">Kubernetes</span></div>
            </article>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">How I work</div>
          <ul style="margin:0;padding-left:18px;color:var(--muted);line-height:1.6">
            <li>Write clear, well-tested code and document design decisions.</li>
            <li>Prefer small, incremental changes and CI-driven development.</li>
            <li>Instrument systems with logs, metrics, and health checks.</li>
            <li>Mentor others and collaborate with designers, QA, and product owners.</li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">Open to</div>
          <p style="color:var(--muted);margin:0">Roles in Backend Engineering, Systems Programming, SRE/DevOps, and Automation — both remote and on-site. Looking for internships, junior-mid level positions, and collaborative teams.</p>
        </section>
      </main>

      <aside>
        <div class="card">
          <div class="section-title">Tech & tools</div>
          <div class="stack">
            <span class="tech">C</span>
            <span class="tech">C++</span>
            <span class="tech">Rust</span>
            <span class="tech">Go</span>
            <span class="tech">Python</span>
            <span class="tech">Bash</span>
            <span class="tech">Docker</span>
            <span class="tech">Kubernetes</span>
            <span class="tech">Postgres</span>
            <span class="tech">Redis</span>
            <span class="tech">Linux</span>
            <span class="tech">Git</span>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <div class="section-title">Quick stats</div>
          <div class="stats">
            <div class="stat"><span>Top languages</span><span>Go • Python</span></div>
            <div class="stat"><span>Years coding</span><span>2+ years</span></div>
            <div class="stat"><span>Public repos</span><span>12</span></div>
            <div class="stat"><span>Contributions (last year)</span><span>420+</span></div>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <div class="section-title">Get in touch</div>
          <p style="margin:0;color:var(--muted)">Email: <a href="mailto:ceciliagrace2003@gmail.com">ceciliagrace2003@gmail.com</a> | <a href="mailto:cecigrace2003@gmail.com">cecigrace2003@gmail.com</a></p>
          <p style="margin:6px 0 0;color:var(--muted)">LinkedIn: <a href="https://www.linkedin.com/in/cecilia-matini-4b5ab3274/?trk=opento_sprofile_topcard" target="_blank">/in/cecilia-matini</a></p>
          <p style="margin:6px 0 0;color:var(--muted)">Portfolio: <a href="https://yourportfolio.example" target="_blank">yourportfolio.example</a></p>
        </div>

        <div class="card" style="margin-top:14px;text-align:center">
          <div class="section-title">Resume</div>
          <a class="cta" href="/resume.pdf" target="_blank">Download PDF</a>
        </div>
      </aside>
    </div>

    <footer>
      <div style="margin-top:18px">Thanks for visiting — I'm actively improving my work. | <a href="#">Read my blog</a> • <a href="#">Follow</a></div>
    </footer>
  </article>
</body>
</html>
