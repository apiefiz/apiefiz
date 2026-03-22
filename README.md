<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Arpit Saxena – GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&family=Sora:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d1117;
    --surface: #161b22;
    --border: #30363d;
    --accent: #58a6ff;
    --accent2: #3fb950;
    --accent3: #f78166;
    --accent4: #d2a8ff;
    --text: #e6edf3;
    --muted: #8b949e;
    --code-bg: #1f2937;
    --radius: 8px;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Sora', sans-serif;
    line-height: 1.7;
    padding: 2rem 1rem;
  }
  .container {
    max-width: 860px;
    margin: 0 auto;
  }

  /* HEADER */
  .header {
    text-align: center;
    padding: 3rem 2rem 2rem;
    position: relative;
  }
  .header h1 {
    font-size: 2.4rem;
    font-weight: 700;
    letter-spacing: -0.5px;
    margin-bottom: 0.5rem;
  }
  .header .tagline {
    color: var(--muted);
    font-size: 1rem;
    font-weight: 300;
    margin-bottom: 1.5rem;
  }
  .badges {
    display: flex;
    justify-content: center;
    gap: 0.6rem;
    flex-wrap: wrap;
    margin-top: 1rem;
  }
  .badge {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.35rem 0.9rem;
    border-radius: 999px;
    font-size: 0.78rem;
    font-family: 'JetBrains Mono', monospace;
    font-weight: 600;
    text-decoration: none;
    transition: opacity 0.2s;
  }
  .badge:hover { opacity: 0.8; }
  .badge-linkedin { background: #0e76a8; color: #fff; }
  .badge-leetcode { background: #f89f1b; color: #fff; }
  .badge-gmail    { background: #d93025; color: #fff; }

  /* GIF / AVATAR AREA */
  .hero-gif {
    display: flex;
    justify-content: center;
    margin: 1.5rem 0;
  }
  .hero-gif img { border-radius: 12px; max-width: 260px; }

  /* SECTION CARD */
  .card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 1.6rem 2rem;
    margin-bottom: 1.4rem;
  }
  .card h2 {
    font-size: 1.15rem;
    font-weight: 600;
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    border-bottom: 1px solid var(--border);
    padding-bottom: 0.7rem;
  }
  .card p, .card li {
    color: var(--muted);
    font-size: 0.92rem;
  }
  .card ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
  }
  .card li::before {
    content: "▸ ";
    color: var(--accent);
    font-size: 0.8rem;
  }
  .card strong { color: var(--text); }

  /* CODE BLOCK */
  .code-block {
    background: var(--code-bg);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 1.2rem 1.6rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.82rem;
    line-height: 1.9;
    overflow-x: auto;
    margin-bottom: 1.4rem;
  }
  .kw  { color: #ff7b72; }
  .fn  { color: #d2a8ff; }
  .str { color: #a5d6ff; }
  .key { color: #79c0ff; }
  .cm  { color: var(--muted); }

  /* TECH GRID */
  .tech-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  .chip {
    padding: 0.3rem 0.8rem;
    border-radius: 999px;
    font-size: 0.76rem;
    font-family: 'JetBrains Mono', monospace;
    font-weight: 600;
    border: 1px solid;
  }
  .chip-blue   { color: var(--accent);  border-color: var(--accent);  background: rgba(88,166,255,.08); }
  .chip-green  { color: var(--accent2); border-color: var(--accent2); background: rgba(63,185,80,.08);  }
  .chip-red    { color: var(--accent3); border-color: var(--accent3); background: rgba(247,129,102,.08);}
  .chip-purple { color: var(--accent4); border-color: var(--accent4); background: rgba(210,168,255,.08);}

  /* STATS */
  .stats-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
  }
  @media (max-width: 600px) {
    .stats-row { grid-template-columns: 1fr; }
    .header h1 { font-size: 1.7rem; }
  }
</style>
</head>
<body>
<div class="container">

  <!-- HEADER -->
  <div class="header">
    <h1>Hi there, I'm Arpit Saxena 🙋 ✨</h1>
    <p class="tagline">Engineering at Salesforce · Full Stack · Ex-Informatica, Deloitte</p>
    <div class="badges">
      <a class="badge badge-linkedin" href="https://www.linkedin.com/in/arpitsaxena6799/" target="_blank">
        🔗 LinkedIn
      </a>
      <a class="badge badge-leetcode" href="https://leetcode.com/saxenaarpit61/" target="_blank">
        ⚡ LeetCode
      </a>
      <a class="badge badge-gmail" href="mailto:saxenaarpit61@gmail.com">
        ✉ Gmail
      </a>
    </div>
  </div>

  <div class="hero-gif">
    <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--zNqcSN_E--/c_imagga_scale,f_auto,fl_progressive,h_900,q_66,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/2ciu6mo6r9x9zyverc10.gif" alt="coding gif" />
  </div>

  <!-- ABOUT -->
  <div class="card">
    <h2>👋 About Me</h2>
    <p>
      I have <strong>5+ years of experience</strong> designing and building high-performance backend systems and APIs.
      I specialize in <strong>Java &amp; Spring Boot</strong> for robust server-side architecture and microservices development,
      with hands-on experience in <strong>React.js &amp; Next.js</strong> for functional frontend interfaces.
      Currently a <strong>Member of Technical Staff at Salesforce</strong>, building AI-powered solutions including
      an integrated assistant for our internal Customer 360 platform — leveraging LLMs (Claude, Gemini, OpenAI)
      and developing custom MCP servers.
    </p>
  </div>

  <!-- PERSONAL STUFFS -->
  <div class="card">
    <h2>⚡ Talking about Personal Stuffs:</h2>
    <ul>
      <li><strong>💻 I'm a Full Stack Developer</strong> — specialized in backend, comfortable end-to-end.</li>
      <li><strong>🚀 I enjoy building web applications,</strong> designing scalable architectures, and learning algorithms &amp; math.</li>
      <li><strong>🤖 Currently working on</strong> AI-powered integrations using LLMs and custom MCP servers.</li>
      <li><strong>💬 Ask me about</strong> Java, Spring Boot, Microservices, React JS, Next.js, ServiceNow, LLM integration.</li>
      <li><strong>♟️ Outside work,</strong> I like to play cricket, travel &amp; spend time with family.</li>
      <li><strong>📝 Wanna know more?</strong> <a href="https://drive.google.com/file/d/1cmVYCVIagG5Mf4xoY9RVjujeyGFzQClY/view?usp=sharing" target="_blank" style="color: var(--accent);">Check out my Resume</a></li>
    </ul>
  </div>

  <!-- SKILLS CODE BLOCK -->
  <div class="code-block">
<span class="kw">let</span> <span class="fn">arpit</span> = {<br>
&nbsp;&nbsp;<span class="key">languages</span>: [<span class="str">"Java"</span>, <span class="str">"JavaScript"</span>, <span class="str">"TypeScript"</span>, <span class="str">"SQL"</span>, <span class="str">"C++"</span>],<br>
&nbsp;&nbsp;<span class="key">backend</span>:   [<span class="str">"Spring Boot"</span>, <span class="str">"Microservices"</span>, <span class="str">"RESTful APIs"</span>, <span class="str">"Node.js"</span>],<br>
&nbsp;&nbsp;<span class="key">frontend</span>:  [<span class="str">"React.js"</span>, <span class="str">"Next.js"</span>, <span class="str">"HTML"</span>, <span class="str">"CSS"</span>],<br>
&nbsp;&nbsp;<span class="key">ai</span>:        [<span class="str">"LLM Integration"</span>, <span class="str">"MCP Servers"</span>, <span class="str">"Claude"</span>, <span class="str">"Gemini"</span>, <span class="str">"OpenAI"</span>],<br>
&nbsp;&nbsp;<span class="key">databases</span>: [<span class="str">"PostgreSQL"</span>, <span class="str">"MongoDB"</span>, <span class="str">"MySQL"</span>],<br>
&nbsp;&nbsp;<span class="key">tools</span>:     [<span class="str">"Postman"</span>, <span class="str">"GitHub"</span>, <span class="str">"IntelliJ"</span>, <span class="str">"WebStorm"</span>],<br>
&nbsp;&nbsp;<span class="key">current</span>:   <span class="str">"Building AI-powered Customer 360 at Salesforce 🚀"</span><br>
};
  </div>

  <!-- TOOLS & FRAMEWORKS -->
  <div class="card">
    <h2>🛠 Familiar Tools &amp; Frameworks</h2>
    <div class="tech-grid">
      <span class="chip chip-blue">Java</span>
      <span class="chip chip-blue">Spring Boot</span>
      <span class="chip chip-blue">Microservices</span>
      <span class="chip chip-green">React.js</span>
      <span class="chip chip-green">Next.js</span>
      <span class="chip chip-green">Node.js</span>
      <span class="chip chip-purple">LLM Integration</span>
      <span class="chip chip-purple">MCP Servers</span>
      <span class="chip chip-purple">Claude / OpenAI</span>
      <span class="chip chip-red">PostgreSQL</span>
      <span class="chip chip-red">MongoDB</span>
      <span class="chip chip-red">MySQL</span>
      <span class="chip chip-blue">RESTful APIs</span>
      <span class="chip chip-green">JavaScript</span>
      <span class="chip chip-green">HTML5</span>
      <span class="chip chip-green">CSS3</span>
      <span class="chip chip-purple">ServiceNow</span>
      <span class="chip chip-blue">Postman</span>
      <span class="chip chip-blue">GitHub</span>
      <span class="chip chip-purple">Material UI</span>
      <span class="chip chip-red">Styled Components</span>
    </div>
  </div>

  <!-- EXPERIENCE SUMMARY -->
  <div class="card">
    <h2>💼 Experience</h2>
    <ul>
      <li><strong>Salesforce</strong> — Member of Technical Staff <span style="color:var(--muted)">(Mar 2026 – Present · Bengaluru)</span></li>
      <li><strong>Informatica</strong> — Senior Software Engineer → Software Engineer <span style="color:var(--muted)">(Aug 2022 – Feb 2026 · 3 yrs 7 mo)</span></li>
      <li><strong>Deloitte USI</strong> — Associate SE / Technology Analyst <span style="color:var(--muted)">(Nov 2020 – Aug 2022 · 1 yr 10 mo)</span></li>
      <li><strong>Deloitte India</strong> — Technology Intern <span style="color:var(--muted)">(Jan 2020 – Apr 2020)</span> · Reduced case-resolving time by 40% with log-parser SDKs</li>
    </ul>
  </div>

</div>
</body>
</html>
