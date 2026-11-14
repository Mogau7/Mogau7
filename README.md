<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mogau Mamabolo — Software Developer</title>
  <style>
    :root {
      --bg: #0c0c0e;
      --surface: #141418;
      --border: #24242c;
      --text: #ececf1;
      --muted: #8e8ea0;
      --accent: #38bdf8;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, "Inter", "Segoe UI", Roboto, sans-serif;
      line-height: 1.7;
      padding: 4rem 1.5rem;
      -webkit-font-smoothing: antialiased;
    }

    main {
      max-width: 640px;
      margin: 0 auto;
    }

    header {
      margin-bottom: 3.5rem;
    }

    header h1 {
      font-size: 1.5rem;
      font-weight: 600;
      letter-spacing: -0.02em;
    }

    header p {
      color: var(--muted);
      font-size: 0.95rem;
      margin-top: 0.25rem;
    }

    section {
      margin-bottom: 3.5rem;
    }

    .label {
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
      margin-bottom: 1rem;
      display: block;
    }

    .bio p {
      font-size: 1.05rem;
      color: #d4d4dc;
      margin-bottom: 1.25rem;
    }

    blockquote {
      border-left: 2px solid var(--accent);
      padding-left: 1rem;
      margin: 2rem 0;
      color: var(--text);
      font-style: italic;
      font-size: 1.05rem;
    }

    .stack-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .tag {
      background: var(--surface);
      border: 1px solid var(--border);
      padding: 0.35rem 0.75rem;
      border-radius: 6px;
      font-size: 0.85rem;
      font-family: ui-monospace, SFMono-Regular, Menlo, monospace;
      color: #d4d4dc;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1rem;
    }

    .stat-card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 1.1rem;
    }

    .stat-card .num {
      font-size: 1.35rem;
      font-weight: 600;
      color: var(--text);
      display: block;
    }

    .stat-card .desc {
      font-size: 0.8rem;
      color: var(--muted);
    }

    .activity-box {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 1.25rem;
      font-size: 0.9rem;
      color: var(--muted);
    }

    .links {
      display: flex;
      gap: 1.5rem;
      flex-wrap: wrap;
    }

    .links a {
      color: var(--text);
      text-decoration: none;
      font-size: 0.95rem;
      border-bottom: 1px solid var(--border);
      padding-bottom: 2px;
      transition: border-color 0.2s, color 0.2s;
    }

    .links a:hover {
      color: var(--accent);
      border-color: var(--accent);
    }

    footer {
      margin-top: 4rem;
      padding-top: 1.5rem;
      border-top: 1px solid var(--border);
      color: var(--muted);
      font-size: 0.85rem;
    }

    @media (max-width: 520px) {
      .stats-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <main>
    <header>
      <h1>Mogau Mamabolo — Software Developer</h1>
      <p>Self-taught builder · South Africa</p>
    </header>

    <section class="bio">
      <span class="label">Who am I</span>
      <p>
        Self-taught developer based in South Africa. I build software end to end — the logic, the interface, and the deploy.
      </p>
      <p>
        I started learning programming the hard way in Notepad++, and now pair those fundamentals with AI tools to build and ship faster.
      </p>
      <p>
        I like software that runs on your machine, works without an account, and keeps working when the internet doesn't. If it needs a manual, it isn't finished.
      </p>
      <blockquote>
        "I don't talk much. I just pay attention and build."
      </blockquote>
    </section>

    <section>
      <span class="label">What I work with · Stack</span>
      <div class="stack-grid">
        <span class="tag">JavaScript (ES6+)</span>
        <span class="tag">HTML5</span>
        <span class="tag">CSS3</span>
        <span class="tag">Python</span>
        <span class="tag">Cursor</span>
        <span class="tag">VS Code</span>
        <span class="tag">Git & GitHub</span>
        <span class="tag">Claude</span>
      </div>
    </section>

    <section>
      <span class="label">Contributions · Activity</span>
      <div class="activity-box">
        Building web tools, experimenting with AI-assisted workflows, and shipping clean code on <a href="https://github.com" style="color: var(--accent); text-decoration: none;">://github.com</a>.
      </div>
    </section>

    <section>
      <span class="label">Numbers · GitHub Statistics</span>
      <div class="stats-grid">
        <div class="stat-card">
          <span class="num">100%</span>
          <span class="desc">Local-first mindset</span>
        </div>
        <div class="stat-card">
          <span class="num">0</span>
          <span class="desc">Unnecessary accounts</span>
        </div>
        <div class="stat-card">
          <span class="num">24/7</span>
          <span class="desc">Beats, charts & code</span>
        </div>
      </div>
    </section>

    <section>
      <span class="label">Find me</span>
      <div class="links">
        <a href="https://github.com" target="_blank" rel="noopener">GitHub</a>
        <a href="https://linkedin.com" target="_blank" rel="noopener">LinkedIn</a>
        <a href="mailto:mogaumamabolo93@gmail.com">Email</a>
      </div>
    </section>

    <footer>
      © Mogau Mamabolo · South Africa
    </footer>
  </main>
</body>
</html>
