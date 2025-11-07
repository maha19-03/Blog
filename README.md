<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About Me — Mahathi Senthilkumar</title>
  <meta name="description" content="Personal About Me page for Mahathi Senthilkumar, 1st year Cyber Security student at SRM Valliammai." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --muted:#94a3b8;
      --accent:#60a5fa;
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg,var(--bg) 0%, #071023 100%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
      padding:32px;
    }
    .container{
      max-width:1100px;
      margin:0 auto;
      display:grid;
      grid-template-columns:320px 1fr;
      gap:28px;
      align-items:start;
    }
    /* Sidebar */
    aside{
      background:linear-gradient(180deg,var(--card), rgba(11,18,32,0.9));
      padding:22px;
      border-radius:var(--radius);
      box-shadow:0 8px 30px rgba(2,6,23,0.6);
      position:sticky; top:32px;
      height:fit-content;
    }
    .avatar{
      width:84px;height:84px;border-radius:14px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:20px;color:var(--accent);margin-bottom:14px
    }
    .name{font-weight:700;font-size:18px;margin:0}
    .meta{color:var(--muted);font-size:13px;margin-top:4px}
    .quick-list{margin-top:18px}
    .quick-list li{font-size:14px;color:var(--muted);margin:8px 0}
    /* Main */
    main{background:rgba(255,255,255,0.02);padding:26px;border-radius:18px;box-shadow:0 12px 30px rgba(2,6,23,0.6)}
    header{display:flex;gap:18px;align-items:center;margin-bottom:12px}
    h1{margin:0;font-size:22px}
    .subtitle{color:var(--muted);font-size:14px}
    section{margin-top:18px;padding-top:8px;border-top:1px dashed rgba(255,255,255,0.03)}
    section h2{font-size:16px;margin:0 0 10px 0;color:var(--accent)}
    section p{margin:6px 0;color:rgba(230,238,248,0.95);font-size:15px}
    ul.strengths{display:grid;grid-template-columns:repeat(2, minmax(0,1fr));gap:10px;padding:0;margin:8px 0;list-style:none}
    ul.strengths li{background:rgba(255,255,255,0.02);padding:10px;border-radius:10px;font-size:14px;color:var(--muted)}
    /* Responsive */
    @media (max-width:880px){
      .container{grid-template-columns:1fr; padding:0 8px}
      aside{position:relative;top:0}
    }
    .cta-row{display:flex;gap:12px;margin-top:18px}
    .btn{border-radius:12px;padding:10px 14px;font-weight:600;border:none;background:linear-gradient(90deg,var(--accent),#3b82f6);color:#04263b;cursor:pointer}
    .btn.ghost{background:transparent;color:var(--accent);border:1px solid rgba(96,165,250,0.15)}
    footer{margin-top:18px;color:var(--muted);font-size:13px}
  </style>
</head>
<body>
  <div class="container">
    <aside aria-labelledby="profile-name">
      <div class="avatar" aria-hidden="true">MS</div>
      <h3 id="profile-name" class="name">Mahathi Senthilkumar</h3>
      <div class="meta">1st Year — Cyber Security<br>SRM Valliammai Engineering College</div>

      <ul class="quick-list" aria-label="Quick info">
        <li><strong>Thinking:</strong> Deep, analytical, curious</li>
        <li><strong>Work-style:</strong> Slow & steady, consistent</li>
        <li><strong>Environment:</strong> Calm, organized, respectful</li>
        <li><strong>Team:</strong> Comfortable alone or in groups</li>
      </ul>

      <div class="cta-row">
        <button class="btn">Download CV</button>
        <button class="btn ghost">Contact</button>
      </div>

      <footer>
        <div>Passionate about ethical hacking, network defense, and data protection.</div>
      </footer>
    </aside>

    <main>
      <header>
        <div>
          <h1>About Me</h1>
          <div class="subtitle">Hi! I'm Mahathi — stepping into the digital world with curiosity and determination.</div>
        </div>
      </header>

      <section id="way-of-thinking">
        <h2>My Way of Thinking</h2>
        <p>I have a naturally deep and analytical mindset. I like to observe, question, and understand things from the core. Whether it is a new concept in class or a real-world situation, I take time to analyze it thoroughly. I believe that understanding deeply, rather than memorizing quickly, helps build stronger knowledge and confidence.</p>
      </section>

      <section id="work-style">
        <h2>My Work Style</h2>
        <p>I believe in being slow and steady, because real learning takes time. I prefer to work patiently and consistently rather than rushing for quick results. Every small step I take helps me grow, and I see progress as a process, not a race.</p>
      </section>

      <section id="environment-values">
        <h2>My Environment &amp; Values</h2>
        <p>I strongly value a peaceful environment and organized workspace. Calm surroundings help me focus better and bring clarity to my thoughts. I believe that respect, discipline, and positivity in one’s environment create the foundation for success.</p>
      </section>

      <section id="alone-or-group">
        <h2>Working Alone and in Groups</h2>
        <p>I can comfortably work alone, where I can focus deeply, or be part of a group, where ideas and creativity flow collectively. I adapt easily to both situations. For me, independence builds focus, and teamwork builds perspective — both are equally important.</p>
      </section>

      <section id="balance">
        <h2>Balance Between Work and Fun</h2>
        <p>When I work, I love silence and focus, but when it is time to relax, I bring energy, laughter, and liveliness. I believe that life needs both calm and excitement — silence for concentration, and a little "violence" of fun for joy. This balance keeps me refreshed and motivated.</p>
      </section>

      <section id="why-cyber">
        <h2>Why I Chose Cyber Security</h2>
        <p>Cyber Security inspires me because it combines logic, creativity, and responsibility. It is a field where every problem has a challenge hidden inside, waiting to be solved. I enjoy learning how systems work, how data can be protected, and how every click in the digital world matters. I aspire to build strong technical skills and become someone who can make a real difference in creating safer online spaces.</p>
      </section>

      <section id="strengths">
        <h2>Personal Strengths</h2>
        <ul class="strengths">
          <li>Deep analytical thinking &amp; observation</li>
          <li>Patience, persistence, consistency</li>
          <li>Adaptable — solo or team work</li>
          <li>Respectful, structured, value-driven</li>
          <li>Calm during work, lively in fun</li>
          <li>Positive &amp; curious attitude to learn</li>
        </ul>
      </section>

      <section id="vision">
        <h2>My Future Vision</h2>
        <p>In the years ahead, I want to strengthen my technical foundation, gain practical exposure through real-time projects, and explore areas like ethical hacking, network defense, and data protection. My dream is to grow into a skilled, responsible Cyber Security professional who contributes to a safer digital world.</p>
      </section>

    </main>
  </div>
</body>
</html>
