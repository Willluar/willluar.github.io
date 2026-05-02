
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>William Campbell-Jones — Junior Games Programmer & Software Developer</title>
<meta name="description" content="Portfolio of William Campbell-Jones, BSc (Hons) Games Technology graduate. C#/Unity, C++, Python. Open to UK roles from May 2026.">
<style>
  :root {
    --bg: #fafaf7;
    --fg: #111111;
    --muted: #555555;
    --rule: #e5e5dd;
    --accent: #1a4f8a;
    --card-bg: #ffffff;
    --tag-bg: #eef0f3;
    --tag-fg: #1a4f8a;
    --max: 880px;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #111114;
      --fg: #f3f3ee;
      --muted: #a8a8a0;
      --rule: #25252a;
      --accent: #6ea8e8;
      --card-bg: #1a1a1f;
      --tag-bg: #25252a;
      --tag-fg: #9bbef0;
    }
  }
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    margin: 0;
    background: var(--bg);
    color: var(--fg);
    font: 17px/1.55 -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, sans-serif;
    -webkit-font-smoothing: antialiased;
  }
  main, header, footer { max-width: var(--max); margin: 0 auto; padding: 0 24px; }
  a { color: var(--accent); text-decoration: none; border-bottom: 1px solid transparent; transition: border-color .15s; }
  a:hover { border-bottom-color: var(--accent); }
  h1, h2, h3 { font-weight: 600; line-height: 1.2; letter-spacing: -0.01em; }
  h1 { font-size: 2.4rem; margin: 0 0 0.5rem; }
  h2 { font-size: 1.5rem; margin: 3rem 0 1rem; padding-bottom: 0.4rem; border-bottom: 1px solid var(--rule); }
  h3 { font-size: 1.1rem; margin: 0 0 0.35rem; }
  p { margin: 0 0 1rem; }
  small, .small { font-size: 0.875rem; color: var(--muted); }
 
  /* Header */
  .top { padding-top: 4rem; padding-bottom: 1rem; }
  .role { color: var(--muted); font-size: 1.1rem; margin: 0 0 1rem; }
  .status {
    display: inline-block;
    padding: 0.2rem 0.6rem;
    background: var(--tag-bg);
    color: var(--tag-fg);
    border-radius: 999px;
    font-size: 0.85rem;
    margin-bottom: 1.25rem;
  }
  .links { display: flex; flex-wrap: wrap; gap: 0.85rem 1.25rem; font-size: 0.95rem; }
 
  /* Project cards */
  .projects { display: grid; gap: 1rem; }
  .project {
    background: var(--card-bg);
    border: 1px solid var(--rule);
    border-radius: 10px;
    padding: 1.25rem 1.4rem;
  }
  .project-head { display: flex; justify-content: space-between; align-items: baseline; gap: 1rem; flex-wrap: wrap; }
  .project-meta { color: var(--muted); font-size: 0.9rem; }
  .tags { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-top: 0.6rem; }
  .tag {
    font-size: 0.78rem;
    padding: 0.15rem 0.55rem;
    background: var(--tag-bg);
    color: var(--tag-fg);
    border-radius: 4px;
    font-weight: 500;
  }
  .project-links { margin-top: 0.7rem; font-size: 0.9rem; display: flex; gap: 1.1rem; flex-wrap: wrap; }
  .project img {
    width: 100%;
    height: auto;
    border-radius: 6px;
    margin-top: 0.9rem;
    border: 1px solid var(--rule);
  }
 
  /* Skills */
  .skill-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 0.6rem 1.5rem; }
  .skill-grid div { padding: 0.25rem 0; color: var(--muted); }
  .skill-grid strong { color: var(--fg); display: block; margin-bottom: 0.25rem; font-size: 0.95rem; }
 
  /* Footer */
  footer { padding: 3rem 24px 4rem; color: var(--muted); font-size: 0.9rem; border-top: 1px solid var(--rule); margin-top: 4rem; }
  footer p { margin: 0; }
 
  @media (max-width: 480px) {
    h1 { font-size: 2rem; }
    .top { padding-top: 2.5rem; }
  }
</style>
</head>
<body>
 
<header class="top">
  <span class="status">Available from May 2026 — open to UK relocation</span>
  <h1>William Campbell-Jones</h1>
  <p class="role">Junior games programmer & software developer · Newton Abbot, UK</p>
  <nav class="links">
    <a href="mailto:williamcj@hotmail.co.uk">williamcj@hotmail.co.uk</a>
    <a href="https://github.com/Willluar">github.com/Willluar</a>
    <a href="https://www.linkedin.com/in/william-campbell-jones-456952152/">LinkedIn</a>
    <a href="cv.pdf">CV (PDF)</a>
  </nav>
</header>
 
<main>
 
<section id="about">
  <h2>About</h2>
  <p>
    I'm finishing a BSc (Hons) in Games Technology at the University of the West of England (May 2026).
    Most of my coursework has been in C# and C++, with Python and SQL alongside. I've done two game jams
    and a stack of team-based projects, all version-controlled in Git.
  </p>
  <p>
    Before university I spent four years in technical-support roles at BT and AXS, handling real-time
    troubleshooting under KPI pressure. That background means I write clear bug reports, talk to
    non-engineers without losing patience, and learn unfamiliar systems quickly. I'm looking for junior
    programmer, gameplay, or QA roles in games, or a junior software-developer or technical-support role
    elsewhere.
  </p>
</section>
 
<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
 
    <article class="project">
      <div class="project-head">
        <h3>[PROJECT NAME — e.g. Game Jam Entry Title]</h3>
        <span class="project-meta">Game jam · 2025</span>
      </div>
      <p>[One or two sentences on what the game is, what you built, what worked. E.g. "A 48-hour jam entry where I built the player controller and core combat loop in Unity. Team of four; I owned all gameplay code."]</p>
      <div class="tags">
        <span class="tag">C#</span>
        <span class="tag">Unity</span>
        <span class="tag">Git</span>
      </div>
      <div class="project-links">
        <a href="#">View on GitHub</a>
        <a href="#">Play in browser (itch.io)</a>
      </div>
      <!-- Replace with real screenshot. Recommended: 1600x900 PNG/JPG. -->
      <!-- <img src="projects/jam1.png" alt="Screenshot of [project name]"> -->
    </article>
 
    <article class="project">
      <div class="project-head">
        <h3>[PROJECT NAME — second jam or coursework]</h3>
        <span class="project-meta">Game jam · 2024</span>
      </div>
      <p>[One or two sentences. Highlight the technically interesting bit: AI you built, a system you debugged, a problem you solved.]</p>
      <div class="tags">
        <span class="tag">C#</span>
        <span class="tag">Unity</span>
      </div>
      <div class="project-links">
        <a href="#">View on GitHub</a>
      </div>
    </article>
 
    <article class="project">
      <div class="project-head">
        <h3>[UNIVERSITY COURSEWORK — e.g. Graphics Programming Project]</h3>
        <span class="project-meta">UWE coursework · 2025</span>
      </div>
      <p>[Describe the brief, your approach, the result. If it's a graphics project, mention the rendering technique. If it's an AI project, mention the algorithm.]</p>
      <div class="tags">
        <span class="tag">C++</span>
        <span class="tag">OpenGL</span>
      </div>
      <div class="project-links">
        <a href="#">View on GitHub</a>
      </div>
    </article>
 
    <article class="project">
      <div class="project-head">
        <h3>[UNIVERSITY COURSEWORK — e.g. AI Systems Module]</h3>
        <span class="project-meta">UWE coursework · 2025</span>
      </div>
      <p>[Brief description. What was the problem, what did you implement, what did you learn?]</p>
      <div class="tags">
        <span class="tag">Python</span>
        <span class="tag">Algorithms</span>
      </div>
      <div class="project-links">
        <a href="#">View on GitHub</a>
      </div>
    </article>
 
  </div>
</section>
 
<section id="skills">
  <h2>Skills</h2>
  <div class="skill-grid">
    <div>
      <strong>Languages</strong>
      C#, C++, Python, SQL
    </div>
    <div>
      <strong>Tools</strong>
      Unity, Git & GitHub, Visual Studio
    </div>
    <div>
      <strong>Practices</strong>
      OOP, Agile workflows, Software testing, Technical documentation
    </div>
    <div>
      <strong>Other</strong>
      RESTful APIs, Problem solving & debugging
    </div>
  </div>
</section>
 
<section id="experience">
  <h2>Experience</h2>
  <p><strong>Retail Assistant</strong>, Co-op · 2025 — present</p>
  <p><strong>Live Chat Agent</strong>, AXS (Foundever) · May 2024 — Sept 2024. Real-time technical support for ticketing customers.</p>
  <p><strong>Front Line Agent</strong>, BT · Mar 2018 — Apr 2020. Broadband and telephony technical support; consistent KPI delivery on quality and resolution.</p>
</section>
 
<section id="contact">
  <h2>Contact</h2>
  <p>
    Easiest way to reach me is email at
    <a href="mailto:williamcj@hotmail.co.uk">williamcj@hotmail.co.uk</a>.
    I'm on
    <a href="https://www.linkedin.com/in/william-campbell-jones-456952152/">LinkedIn</a>
    and code lives on
    <a href="https://github.com/Willluar">GitHub</a>.
  </p>
</section>
 
</main>
 
<footer>
  <p>© 2026 William Campbell-Jones. Built with HTML and CSS. Hosted on GitHub Pages.</p>
</footer>
 
</body>
</html>
