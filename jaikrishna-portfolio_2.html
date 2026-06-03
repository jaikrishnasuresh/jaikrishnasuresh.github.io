<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JAIKRISHNA.N // Media Operations Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;500;700&family=Bebas+Neue&family=Oxanium:wght@300;400;600;800&display=swap" rel="stylesheet">
<style>
  :root {
    --green: #00ff41;
    --green-dim: #00cc33;
    --green-dark: #003b0f;
    --cyan: #00f5ff;
    --cyan-dim: #00b8cc;
    --amber: #ffb700;
    --amber-dim: #cc9200;
    --red: #ff2244;
    --bg: #050a05;
    --bg2: #080f08;
    --bg3: #0a150a;
    --panel: #0d1a0d;
    --border: #1a3a1a;
    --text: #c8ffc8;
    --text-dim: #6a9a6a;
    --scanline: rgba(0,255,65,0.03);
    --glow-green: 0 0 10px #00ff41, 0 0 30px #00ff4133;
    --glow-cyan: 0 0 10px #00f5ff, 0 0 30px #00f5ff33;
    --glow-amber: 0 0 10px #ffb700, 0 0 30px #ffb70033;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    overflow-x: hidden;
    cursor: crosshair;
  }

  /* SCANLINES OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background: repeating-linear-gradient(0deg, transparent, transparent 2px, var(--scanline) 2px, var(--scanline) 4px);
    pointer-events: none;
    z-index: 9999;
  }

  /* NOISE */
  body::after {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9998;
    opacity: 0.4;
  }

  /* ===== BIOS SCREEN ===== */
  #bios {
    position: fixed;
    inset: 0;
    background: #000;
    z-index: 10000;
    display: flex;
    flex-direction: column;
    padding: 40px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    color: #ccc;
    overflow: hidden;
  }

  #bios-content { flex: 1; }
  #bios-content p { line-height: 1.8; }
  .bios-green { color: var(--green); }
  .bios-cyan { color: var(--cyan); }
  .bios-amber { color: var(--amber); }
  .bios-white { color: #fff; font-weight: bold; }

  #bios-bar {
    height: 20px;
    background: #333;
    margin-top: 20px;
    position: relative;
    overflow: hidden;
  }
  #bios-bar-fill {
    height: 100%;
    width: 0%;
    background: var(--green);
    box-shadow: var(--glow-green);
    transition: none;
  }
  #bios-bar-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    font-size: 11px;
    color: #000;
    font-weight: bold;
  }

  /* ===== NAVBAR ===== */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    height: 44px;
    background: rgba(5,10,5,0.95);
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    padding: 0 20px;
    z-index: 1000;
    backdrop-filter: blur(10px);
    gap: 0;
  }

  .nav-segment {
    display: flex;
    align-items: center;
    height: 100%;
    padding: 0 14px;
    border-right: 1px solid var(--border);
    font-size: 11px;
    color: var(--text-dim);
    gap: 8px;
    white-space: nowrap;
  }
  .nav-segment:first-child { border-left: 1px solid var(--border); }

  .nav-dot { width: 6px; height: 6px; border-radius: 50%; background: var(--green); box-shadow: var(--glow-green); animation: pulse 2s infinite; }
  .nav-dot.amber { background: var(--amber); box-shadow: var(--glow-amber); }
  .nav-dot.cyan { background: var(--cyan); box-shadow: var(--glow-cyan); animation-delay: 0.5s; }

  .nav-links { display: flex; margin-left: auto; gap: 0; }
  .nav-link {
    padding: 0 16px;
    height: 44px;
    display: flex;
    align-items: center;
    font-size: 11px;
    color: var(--text-dim);
    text-decoration: none;
    border-left: 1px solid var(--border);
    transition: all 0.2s;
    cursor: pointer;
    font-family: 'Oxanium', sans-serif;
    letter-spacing: 1px;
    text-transform: uppercase;
  }
  .nav-link:hover { color: var(--green); background: rgba(0,255,65,0.05); text-shadow: var(--glow-green); }

  #nav-clock { color: var(--amber); font-size: 12px; }

  /* ===== HERO ===== */
  #hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 80px 60px 40px;
    position: relative;
    overflow: hidden;
  }

  .hero-grid-bg {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(var(--border) 1px, transparent 1px),
      linear-gradient(90deg, var(--border) 1px, transparent 1px);
    background-size: 40px 40px;
    opacity: 0.4;
  }

  .hero-glow {
    position: absolute;
    width: 500px; height: 500px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(0,255,65,0.08) 0%, transparent 70%);
    top: 50%; left: 50%;
    transform: translate(-50%,-50%);
    pointer-events: none;
  }

  .hero-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    color: var(--green);
    letter-spacing: 3px;
    margin-bottom: 20px;
    text-shadow: var(--glow-green);
  }
  .hero-label::before { content: '> '; }

  .hero-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(60px, 10vw, 130px);
    line-height: 0.9;
    letter-spacing: 2px;
    color: var(--green);
    position: relative;
    text-shadow: 0 0 20px rgba(0,255,65,0.5), 0 0 60px rgba(0,255,65,0.2);
  }

  .glitch {
    position: relative;
    display: inline-block;
  }
  .glitch::before,
  .glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    height: 100%;
  }
  .glitch::before {
    color: var(--cyan);
    animation: glitch1 3s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 35%, 0 35%);
    transform: translate(-2px, 0);
  }
  .glitch::after {
    color: var(--amber);
    animation: glitch2 3s infinite;
    clip-path: polygon(0 65%, 100% 65%, 100% 100%, 0 100%);
    transform: translate(2px, 0);
  }

  @keyframes glitch1 {
    0%, 90%, 100% { transform: translate(0); opacity: 0; }
    91% { transform: translate(-3px, 1px); opacity: 1; }
    93% { transform: translate(3px, -1px); opacity: 1; }
    95% { transform: translate(-1px, 2px); opacity: 1; }
    97% { transform: translate(0); opacity: 0; }
  }
  @keyframes glitch2 {
    0%, 88%, 100% { transform: translate(0); opacity: 0; }
    89% { transform: translate(3px, -1px); opacity: 1; }
    91% { transform: translate(-3px, 1px); opacity: 1; }
    93% { transform: translate(1px, -2px); opacity: 1; }
    95% { transform: translate(0); opacity: 0; }
  }

  .hero-subtitle {
    font-family: 'Oxanium', sans-serif;
    font-size: clamp(16px, 2.5vw, 28px);
    color: var(--cyan);
    letter-spacing: 4px;
    text-transform: uppercase;
    margin-top: 10px;
    text-shadow: var(--glow-cyan);
  }

  .hero-meta {
    display: flex;
    gap: 30px;
    margin-top: 30px;
    flex-wrap: wrap;
  }
  .hero-meta-item {
    font-size: 12px;
    color: var(--text-dim);
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .hero-meta-item span { color: var(--amber); }

  /* TERMINAL BOX */
  .terminal-box {
    background: rgba(0,0,0,0.7);
    border: 1px solid var(--border);
    border-top: 2px solid var(--green);
    margin-top: 40px;
    max-width: 700px;
    position: relative;
    z-index: 1;
  }

  .terminal-header {
    background: var(--panel);
    padding: 8px 14px;
    display: flex;
    align-items: center;
    gap: 8px;
    border-bottom: 1px solid var(--border);
  }
  .t-dot { width: 10px; height: 10px; border-radius: 50%; }
  .t-dot.r { background: #ff5f57; }
  .t-dot.y { background: #ffbd2e; }
  .t-dot.g { background: var(--green); box-shadow: var(--glow-green); }
  .terminal-title { font-size: 11px; color: var(--text-dim); margin-left: 8px; }

  .terminal-body { padding: 20px; min-height: 120px; }
  .terminal-line { font-size: 13px; line-height: 2; }
  .terminal-prompt { color: var(--green); }
  .terminal-cmd { color: var(--text); }
  .terminal-out { color: var(--text-dim); }
  .terminal-out.hi { color: var(--cyan); }
  .cursor-blink {
    display: inline-block;
    width: 8px; height: 14px;
    background: var(--green);
    vertical-align: middle;
    animation: blink 1s step-end infinite;
    box-shadow: var(--glow-green);
  }
  @keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: 0; } }

  /* ===== SECTION COMMON ===== */
  section { padding: 80px 60px; position: relative; }

  .section-header {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 50px;
  }
  .section-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--text-dim);
    border: 1px solid var(--border);
    padding: 3px 8px;
    white-space: nowrap;
  }
  .section-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(32px, 5vw, 56px);
    letter-spacing: 3px;
    color: var(--text);
  }
  .section-line { flex: 1; height: 1px; background: linear-gradient(90deg, var(--border), transparent); }

  /* ===== SKILLS ===== */
  #skills { background: var(--bg2); }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 2px;
  }

  .skill-card {
    background: var(--panel);
    border: 1px solid var(--border);
    padding: 20px;
    position: relative;
    overflow: hidden;
    transition: all 0.3s;
    cursor: default;
  }
  .skill-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0;
    height: 2px;
    width: 0%;
    background: var(--green);
    box-shadow: var(--glow-green);
    transition: width 0.5s;
  }
  .skill-card:hover { background: rgba(0,255,65,0.03); border-color: var(--green-dim); }
  .skill-card:hover::before { width: 100%; }

  .skill-card.cyan::before { background: var(--cyan); box-shadow: var(--glow-cyan); }
  .skill-card.cyan:hover { border-color: var(--cyan-dim); }
  .skill-card.amber::before { background: var(--amber); box-shadow: var(--glow-amber); }
  .skill-card.amber:hover { border-color: var(--amber-dim); }

  .skill-category {
    font-family: 'Oxanium', sans-serif;
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--green);
    margin-bottom: 10px;
  }
  .skill-card.cyan .skill-category { color: var(--cyan); }
  .skill-card.amber .skill-category { color: var(--amber); }

  .skill-tags { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 10px; }
  .skill-tag {
    font-size: 10px;
    padding: 3px 8px;
    border: 1px solid var(--border);
    color: var(--text-dim);
    transition: all 0.2s;
  }
  .skill-card:hover .skill-tag { border-color: rgba(0,255,65,0.3); color: var(--text); }
  .skill-card.cyan:hover .skill-tag { border-color: rgba(0,245,255,0.3); }
  .skill-card.amber:hover .skill-tag { border-color: rgba(255,183,0,0.3); }

  /* ===== EXPERIENCE ===== */
  #experience { background: var(--bg); }

  .timeline { position: relative; padding-left: 30px; }
  .timeline::before {
    content: '';
    position: absolute;
    left: 0; top: 0; bottom: 0;
    width: 1px;
    background: linear-gradient(180deg, var(--green), var(--cyan), var(--amber));
    box-shadow: 0 0 8px var(--green-dim);
  }

  .timeline-item {
    position: relative;
    margin-bottom: 50px;
    padding: 24px;
    background: var(--panel);
    border: 1px solid var(--border);
    transition: border-color 0.3s;
  }
  .timeline-item:hover { border-color: var(--green-dim); }

  .timeline-dot {
    position: absolute;
    left: -36px;
    top: 28px;
    width: 12px; height: 12px;
    border-radius: 50%;
    background: var(--green);
    box-shadow: var(--glow-green);
    border: 2px solid var(--bg);
  }
  .timeline-item:nth-child(2) .timeline-dot { background: var(--cyan); box-shadow: var(--glow-cyan); }
  .timeline-item:nth-child(3) .timeline-dot { background: var(--amber); box-shadow: var(--glow-amber); }

  .timeline-period {
    font-size: 11px;
    color: var(--amber);
    letter-spacing: 2px;
    margin-bottom: 8px;
    font-family: 'Oxanium', sans-serif;
  }
  .timeline-company {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 28px;
    letter-spacing: 2px;
    color: var(--text);
  }
  .timeline-role {
    font-size: 12px;
    color: var(--cyan);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 16px;
    margin-top: 2px;
    font-family: 'Oxanium', sans-serif;
  }
  .timeline-bullets { list-style: none; }
  .timeline-bullets li {
    font-size: 12px;
    color: var(--text-dim);
    line-height: 1.8;
    padding: 3px 0;
    padding-left: 14px;
    position: relative;
    transition: color 0.2s;
  }
  .timeline-bullets li::before {
    content: '▸';
    position: absolute;
    left: 0;
    color: var(--green);
    font-size: 10px;
  }
  .timeline-item:hover .timeline-bullets li { color: var(--text); }

  .achievement-badge {
    display: inline-block;
    margin-top: 14px;
    padding: 4px 12px;
    border: 1px solid var(--amber);
    color: var(--amber);
    font-size: 10px;
    letter-spacing: 2px;
    font-family: 'Oxanium', sans-serif;
    text-transform: uppercase;
    box-shadow: inset 0 0 20px rgba(255,183,0,0.05);
  }

  /* ===== PROJECTS ===== */
  #projects { background: var(--bg2); }

  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 2px;
  }

  .project-card {
    background: var(--panel);
    border: 1px solid var(--border);
    padding: 24px;
    position: relative;
    overflow: hidden;
    transition: all 0.3s;
    cursor: default;
  }
  .project-card::after {
    content: '';
    position: absolute;
    bottom: 0; right: 0;
    width: 60px; height: 60px;
    background: conic-gradient(from 180deg, transparent 270deg, var(--green) 360deg);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .project-card:hover { border-color: var(--green-dim); background: rgba(0,255,65,0.02); }
  .project-card:hover::after { opacity: 0.3; }
  .project-card.c::after { background: conic-gradient(from 180deg, transparent 270deg, var(--cyan) 360deg); }
  .project-card.c:hover { border-color: var(--cyan-dim); }
  .project-card.a::after { background: conic-gradient(from 180deg, transparent 270deg, var(--amber) 360deg); }
  .project-card.a:hover { border-color: var(--amber-dim); }

  .project-id {
    font-size: 10px;
    color: var(--text-dim);
    letter-spacing: 3px;
    margin-bottom: 12px;
    font-family: 'Oxanium', sans-serif;
  }
  .project-name {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 22px;
    letter-spacing: 2px;
    color: var(--text);
    margin-bottom: 6px;
  }
  .project-platform {
    font-size: 10px;
    color: var(--green);
    letter-spacing: 1px;
    margin-bottom: 12px;
  }
  .project-card.c .project-platform { color: var(--cyan); }
  .project-card.a .project-platform { color: var(--amber); }
  .project-desc { font-size: 12px; color: var(--text-dim); line-height: 1.7; }

  /* ===== ACHIEVEMENT ===== */
  #achievement {
    background: var(--bg);
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
  }

  .achievement-panel {
    background: var(--panel);
    border: 1px solid var(--amber);
    padding: 40px;
    box-shadow: inset 0 0 60px rgba(255,183,0,0.03), 0 0 40px rgba(255,183,0,0.05);
    position: relative;
    overflow: hidden;
  }
  .achievement-panel::before {
    content: 'GUINNESS WORLD RECORD';
    position: absolute;
    top: 20px; right: 20px;
    font-family: 'Bebas Neue', sans-serif;
    font-size: 60px;
    color: rgba(255,183,0,0.04);
    letter-spacing: 4px;
    line-height: 1;
    pointer-events: none;
  }
  .ach-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(28px, 4vw, 48px);
    color: var(--amber);
    letter-spacing: 3px;
    text-shadow: var(--glow-amber);
    margin-bottom: 10px;
  }
  .ach-sub { font-size: 12px; color: var(--text-dim); letter-spacing: 2px; margin-bottom: 24px; font-family: 'Oxanium', sans-serif; }
  .ach-facts {
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 24px;
  }
  .ach-fact {
    border-left: 2px solid var(--amber);
    padding: 6px 16px;
  }
  .ach-fact-val {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 36px;
    color: var(--amber);
    line-height: 1;
  }
  .ach-fact-label { font-size: 10px; color: var(--text-dim); letter-spacing: 2px; text-transform: uppercase; }

  /* ===== CONTACT / TERMINAL ===== */
  #contact { background: var(--bg2); }

  .contact-layout { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; }

  .contact-info { display: flex; flex-direction: column; gap: 16px; }
  .contact-row {
    display: flex;
    align-items: center;
    gap: 14px;
    padding: 14px;
    border: 1px solid var(--border);
    background: var(--panel);
    transition: all 0.2s;
  }
  .contact-row:hover { border-color: var(--green-dim); background: rgba(0,255,65,0.03); }
  .contact-icon { color: var(--green); font-size: 14px; width: 20px; text-align: center; }
  .contact-label { font-size: 10px; color: var(--text-dim); letter-spacing: 2px; text-transform: uppercase; font-family: 'Oxanium', sans-serif; }
  .contact-val { font-size: 13px; color: var(--text); margin-top: 2px; }

  /* INTERACTIVE TERMINAL */
  .interactive-terminal {
    background: #000;
    border: 1px solid var(--border);
    border-top: 2px solid var(--green);
    display: flex;
    flex-direction: column;
    height: 360px;
  }
  .it-header {
    background: var(--panel);
    padding: 8px 14px;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: 11px;
    color: var(--text-dim);
  }
  .it-output {
    flex: 1;
    padding: 14px;
    overflow-y: auto;
    font-size: 12px;
    line-height: 1.9;
  }
  .it-output::-webkit-scrollbar { width: 4px; }
  .it-output::-webkit-scrollbar-track { background: #000; }
  .it-output::-webkit-scrollbar-thumb { background: var(--green-dim); }
  .it-input-row {
    display: flex;
    align-items: center;
    padding: 10px 14px;
    border-top: 1px solid var(--border);
    gap: 10px;
  }
  .it-prompt { color: var(--green); font-size: 12px; white-space: nowrap; }
  .it-input {
    flex: 1;
    background: transparent;
    border: none;
    outline: none;
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    caret-color: var(--green);
  }

  .it-line { margin: 0; }
  .it-line.cmd { color: var(--green); }
  .it-line.out { color: var(--text-dim); }
  .it-line.hi { color: var(--cyan); }
  .it-line.err { color: var(--red); }
  .it-line.amber { color: var(--amber); }

  /* ===== FOOTER ===== */
  footer {
    background: var(--bg);
    border-top: 1px solid var(--border);
    padding: 20px 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 11px;
    color: var(--text-dim);
    flex-wrap: wrap;
    gap: 10px;
  }
  footer span { color: var(--green); }

  /* ===== ANIMATIONS ===== */
  @keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.3; } }
  @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
  @keyframes slideIn { from { opacity: 0; transform: translateX(-20px); } to { opacity: 1; transform: translateX(0); } }

  .fade-in { animation: fadeIn 0.6s ease forwards; }
  .fade-in-2 { animation: fadeIn 0.6s ease 0.2s forwards; opacity: 0; }
  .fade-in-3 { animation: fadeIn 0.6s ease 0.4s forwards; opacity: 0; }

  /* SCROLLBAR */
  ::-webkit-scrollbar { width: 6px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--border); }
  ::-webkit-scrollbar-thumb:hover { background: var(--green-dim); }

  @media (max-width: 768px) {
    section { padding: 60px 20px; }
    #hero { padding: 80px 20px 40px; }
    nav { overflow-x: auto; }
    .contact-layout { grid-template-columns: 1fr; }
    footer { padding: 20px; }
  }
</style>
</head>
<body>

<!-- BIOS SCREEN -->
<div id="bios">
  <div id="bios-content">
    <p class="bios-white">JAIKRISHNA-OS v2.025 // MEDIA OPERATIONS KERNEL</p>
    <p>&nbsp;</p>
    <p class="bios-green">✓ CPU: OTT_PIPELINE_ENGINE @ 3.0GHz [READY]</p>
    <p class="bios-green">✓ RAM: 32GB KUBERNETES_CLUSTER [INITIALIZED]</p>
    <p class="bios-green">✓ DISK: GCP / AWS-S3 / AZURE [MOUNTED]</p>
    <p class="bios-cyan">✓ NET: NIFI_DATAFLOW_PROCESSOR [CONNECTED]</p>
    <p class="bios-cyan">✓ DB: MARIADB + COUCHBASE [ONLINE]</p>
    <p class="bios-cyan">✓ API: POSTMAN_GATEWAY [ACTIVE]</p>
    <p class="bios-amber">⚡ LOADING EXPERIENCE MODULES...</p>
    <p class="bios-amber">⚡ MOUNTING PROJECTS DATABASE...</p>
    <p>&nbsp;</p>
    <p id="bios-msg" class="bios-green">■ BOOTING PORTFOLIO INTERFACE...</p>
  </div>
  <div id="bios-bar">
    <div id="bios-bar-fill"></div>
    <div id="bios-bar-text">INITIALIZING...</div>
  </div>
</div>

<!-- NAVBAR -->
<nav id="navbar" style="opacity:0; pointer-events:none;">
  <div class="nav-segment">
    <div class="nav-dot"></div>
    <span>JAIKRISHNA.N</span>
  </div>
  <div class="nav-segment">
    <div class="nav-dot cyan"></div>
    <span>MEDIA_OPS_ENGINEER</span>
  </div>
  <div class="nav-segment">
    <div class="nav-dot amber"></div>
    <span id="nav-clock">00:00:00</span>
  </div>
  <div class="nav-links">
    <a class="nav-link" onclick="scrollTo('skills')">SKILLS</a>
    <a class="nav-link" onclick="scrollTo('experience')">EXP</a>
    <a class="nav-link" onclick="scrollTo('projects')">PROJECTS</a>
    <a class="nav-link" onclick="scrollTo('contact')">CONTACT</a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-grid-bg"></div>
  <div class="hero-glow"></div>

  <div class="hero-label fade-in">PORTFOLIO_SYS // ONLINE</div>

  <h1 class="hero-title fade-in-2">
    <div class="glitch" data-text="JAIKRISHNA">JAIKRISHNA</div>
    <br>
    <div class="glitch" data-text=".N" style="color: var(--cyan); text-shadow: 0 0 20px rgba(0,245,255,0.5), 0 0 60px rgba(0,245,255,0.2);">.N</div>
  </h1>

  <div class="hero-subtitle fade-in-3">Media Operations Engineer</div>

  <div class="hero-meta fade-in-3">
    <div class="hero-meta-item">📍 <span>Chennai, India</span></div>
    <div class="hero-meta-item">📞 <span>+91 9384648552</span></div>
    <div class="hero-meta-item">✉ <span>jaikrishna13012002@gmail.com</span></div>
    <div class="hero-meta-item">⏱ <span>3+ Years Experience</span></div>
  </div>

  <div class="terminal-box fade-in-3">
    <div class="terminal-header">
      <div class="t-dot r"></div>
      <div class="t-dot y"></div>
      <div class="t-dot g"></div>
      <span class="terminal-title">bash — jaikrishna@mops-station:~</span>
    </div>
    <div class="terminal-body" id="hero-terminal">
      <div class="terminal-line"><span class="terminal-prompt">jaikrishna@mops:~$ </span><span class="terminal-cmd" id="typing-cmd"></span><span class="cursor-blink" id="hero-cursor"></span></div>
      <div id="typing-output"></div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-header">
    <div class="section-num">01 // SKILLS</div>
    <h2 class="section-title">TECH STACK</h2>
    <div class="section-line"></div>
  </div>
  <div class="skills-grid">
    <div class="skill-card">
      <div class="skill-category">☁ Cloud & Infrastructure</div>
      <div class="skill-tags">
        <span class="skill-tag">AWS</span>
        <span class="skill-tag">GCP</span>
        <span class="skill-tag">Azure</span>
        <span class="skill-tag">VMware</span>
        <span class="skill-tag">Docker</span>
        <span class="skill-tag">Kubernetes</span>
        <span class="skill-tag">EC2</span>
        <span class="skill-tag">ELB</span>
        <span class="skill-tag">Auto Scaling</span>
      </div>
    </div>
    <div class="skill-card cyan">
      <div class="skill-category">🗄 Database</div>
      <div class="skill-tags">
        <span class="skill-tag">MariaDB</span>
        <span class="skill-tag">Couchbase</span>
        <span class="skill-tag">PostgreSQL</span>
        <span class="skill-tag">MongoDB</span>
        <span class="skill-tag">RDBMS</span>
        <span class="skill-tag">NoSQL</span>
        <span class="skill-tag">MAMDB</span>
      </div>
    </div>
    <div class="skill-card amber">
      <div class="skill-category">📡 Streaming Protocols</div>
      <div class="skill-tags">
        <span class="skill-tag">RTMP</span>
        <span class="skill-tag">HLS</span>
        <span class="skill-tag">DASH</span>
        <span class="skill-tag">SRT</span>
        <span class="skill-tag">RTSP</span>
        <span class="skill-tag">SFTP</span>
        <span class="skill-tag">TCP/UDP</span>
        <span class="skill-tag">HTTP/HTTPS</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="skill-category">🔧 Tools & Monitoring</div>
      <div class="skill-tags">
        <span class="skill-tag">NiFi</span>
        <span class="skill-tag">Postman</span>
        <span class="skill-tag">Grafana</span>
        <span class="skill-tag">Kibana</span>
        <span class="skill-tag">Loki</span>
        <span class="skill-tag">K9s</span>
        <span class="skill-tag">Apache JMeter</span>
        <span class="skill-tag">Wirecast</span>
      </div>
    </div>
    <div class="skill-card cyan">
      <div class="skill-category">🖥 Server & Networking</div>
      <div class="skill-tags">
        <span class="skill-tag">Nginx</span>
        <span class="skill-tag">Apache</span>
        <span class="skill-tag">IIS</span>
        <span class="skill-tag">Tomcat</span>
        <span class="skill-tag">DNS</span>
        <span class="skill-tag">SSL/TLS</span>
        <span class="skill-tag">SSH</span>
        <span class="skill-tag">SD-WAN</span>
        <span class="skill-tag">VPN</span>
      </div>
    </div>
    <div class="skill-card amber">
      <div class="skill-category">🎫 Ticketing & Collab</div>
      <div class="skill-tags">
        <span class="skill-tag">JIRA</span>
        <span class="skill-tag">Salesforce</span>
        <span class="skill-tag">Zendesk</span>
        <span class="skill-tag">Confluence</span>
        <span class="skill-tag">Slack</span>
        <span class="skill-tag">Manage Engine</span>
        <span class="skill-tag">Atlassian</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="skill-category">💻 OS & Scripting</div>
      <div class="skill-tags">
        <span class="skill-tag">Linux</span>
        <span class="skill-tag">Windows</span>
        <span class="skill-tag">macOS</span>
        <span class="skill-tag">Shell Scripting</span>
        <span class="skill-tag">HTML/CSS</span>
        <span class="skill-tag">JavaScript</span>
        <span class="skill-tag">XML</span>
      </div>
    </div>
    <div class="skill-card cyan">
      <div class="skill-category">🎥 Live Production</div>
      <div class="skill-tags">
        <span class="skill-tag">OBS</span>
        <span class="skill-tag">VMix</span>
        <span class="skill-tag">Blackmagic</span>
        <span class="skill-tag">24x7 Streaming</span>
        <span class="skill-tag">DRM</span>
        <span class="skill-tag">OTT/VOD</span>
      </div>
    </div>
    <div class="skill-card amber">
      <div class="skill-category">⚠ Incident Management</div>
      <div class="skill-tags">
        <span class="skill-tag">RCA</span>
        <span class="skill-tag">P1/P2 Support</span>
        <span class="skill-tag">Escalation</span>
        <span class="skill-tag">Log Analysis</span>
        <span class="skill-tag">KPI Dashboards</span>
        <span class="skill-tag">SLA Reports</span>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="section-header">
    <div class="section-num">02 // EXPERIENCE</div>
    <h2 class="section-title">WORK HISTORY</h2>
    <div class="section-line"></div>
  </div>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-period">JUN 2025 — PRESENT</div>
      <div class="timeline-company">QUICKPLAY MEDIA PVT LTD</div>
      <div class="timeline-role">Media Operations Engineer — MOPS</div>
      <ul class="timeline-bullets">
        <li>Managed content ingestion workflows & metadata delivery for multiple OTT platforms</li>
        <li>Operated SQL (MariaDB) & NoSQL (Couchbase) databases for ingestion pipeline management</li>
        <li>Uploaded and synced metadata across GCP, AWS S3, and Azure cloud buckets with CMS platforms</li>
        <li>Used K9s & Kubernetes to monitor ingestion pods; resolved pod failures and restart loops</li>
        <li>Handled NiFi workflows — cleared cache queues for stuck/failed ingestion sequences</li>
        <li>Used Postman for API key-based on-demand ingestion triggers and endpoint validation</li>
        <li>Produced KPI dashboards and SLA reports tracking ingestion health and failure trends</li>
        <li>Automated repetitive ingestion tasks with Engineering teams, reducing manual workload</li>
      </ul>
      <div class="achievement-badge">⚡ 30% Ingestion Efficiency Improvement</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-period">JUN 2023 — NOV 2024</div>
      <div class="timeline-company">CDTECH INNOVATIONS (LIVEBOX)</div>
      <div class="timeline-role">Technical Support Engineer</div>
      <ul class="timeline-bullets">
        <li>Built and maintained OTT websites & mobile applications for client-specific requirements</li>
        <li>Managed full network infrastructure life cycle — LAN, WAN, HDWAN, SD-WAN configuration</li>
        <li>Configured streaming server engines on Linux via CLI for both DC and client servers</li>
        <li>Secured servers with SSL/TLS custom certificates and SSH access control</li>
        <li>Integrated KYC, Razorpay, and PayPal APIs into OTT server ecosystems</li>
        <li>Set up local load balancers and failover for high-availability data center infrastructure</li>
        <li>Delivered Tier 2 ticketing support resolving issues for 100+ users via Manage Engine</li>
        <li>Configured firewalls by port rules to restrict unauthorized access and block threats</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-period">NOV 2024 — JUL 2024</div>
      <div class="timeline-company">GAVS TECHNOLOGIES</div>
      <div class="timeline-role">Service Desk Engineer</div>
      <ul class="timeline-bullets">
        <li>Provided technical support for Shutterfly platform users across call, email, and chat</li>
        <li>Resolved avg. 60 support tickets/week with 95% customer satisfaction rate</li>
        <li>Managed refund processing, account recovery, and order-related troubleshooting</li>
        <li>Tracked customer interactions and case resolutions via Salesforce CRM</li>
        <li>Identified recurring bugs and coordinated fixes with the development team</li>
      </ul>
      <div class="achievement-badge">⭐ 90% Customer Satisfaction Rating</div>
    </div>

  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="section-header">
    <div class="section-num">03 // PROJECTS</div>
    <h2 class="section-title">OTT PLATFORMS</h2>
    <div class="section-line"></div>
  </div>
  <div class="projects-grid">
    <div class="project-card">
      <div class="project-id">PRJ_001 // REGIONAL_OTT</div>
      <div class="project-name">AHA VIDEO</div>
      <div class="project-platform">Telugu & Tamil Entertainment Platform</div>
      <div class="project-desc">Managed ingestion workflows, metadata updates, and playback validation for large Telugu and Tamil media catalogs across the OTT pipeline.</div>
    </div>
    <div class="project-card c">
      <div class="project-id">PRJ_002 // PHILIPPINES_OTT</div>
      <div class="project-name">CIGNAL PLAY</div>
      <div class="project-platform">Philippines-Based OTT Platform</div>
      <div class="project-desc">Supported live event delivery, ingestion status monitoring, and DRM packaging validation for the Philippine OTT market.</div>
    </div>
    <div class="project-card a">
      <div class="project-id">PRJ_003 // SPORTS_OTT</div>
      <div class="project-name">PILIPINAS LIVE</div>
      <div class="project-platform">Sports-Focused OTT Service</div>
      <div class="project-desc">Managed ingestion sequences, API key automation via Postman, and Kubernetes pod monitoring for live sports event streams.</div>
    </div>
    <div class="project-card">
      <div class="project-id">PRJ_004 // US_NEWS_OTT</div>
      <div class="project-name">LOCAL NOW</div>
      <div class="project-platform">U.S. Local News & Entertainment</div>
      <div class="project-desc">Assisted in ingestion health monitoring, NiFi queue management, and metadata schema updates for the U.S. local streaming market.</div>
    </div>
    <div class="project-card c">
      <div class="project-id">PRJ_005 // SPANISH_OTT</div>
      <div class="project-name">CANELA TV</div>
      <div class="project-platform">Spanish-Language OTT Platform</div>
      <div class="project-desc">Media validation, AppConfig changes, and ingestion troubleshooting using Couchbase (NoSQL) and MariaDB (SQL) for Spanish content delivery.</div>
    </div>
    <div class="project-card a">
      <div class="project-id">PRJ_006 // SPORTS_ECOSYSTEM</div>
      <div class="project-name">GOTHAM SPORTS</div>
      <div class="project-platform">Sports OTT Ecosystem</div>
      <div class="project-desc">Ingestion monitoring, API validation for on-demand content, and metadata syncing across GCP, S3, and Azure cloud storage systems.</div>
    </div>
  </div>
</section>

<!-- ACHIEVEMENT -->
<section id="achievement">
  <div class="section-header">
    <div class="section-num">04 // ACHIEVEMENT</div>
    <h2 class="section-title">RECORD</h2>
    <div class="section-line"></div>
  </div>
  <div class="achievement-panel">
    <div class="ach-title">🏆 GUINNESS WORLD RECORD</div>
    <div class="ach-sub">SRM UNIVERSITY MARATHON // CHANDIGARH → CHENNAI</div>
    <p style="font-size:13px; color:var(--text-dim); line-height:1.8; max-width:700px;">
      Headed the technical operations team for a 13-day record-setting marathon event. Orchestrated and supervised <span style="color:var(--amber)">24×7 uninterrupted live streaming</span> throughout the entire event — managing backend infrastructure, server loads, and team coordination to successfully document and broadcast the Guinness World Record attempt.
    </p>
    <div class="ach-facts">
      <div class="ach-fact">
        <div class="ach-fact-val">13</div>
        <div class="ach-fact-label">Days of 24x7 Ops</div>
      </div>
      <div class="ach-fact">
        <div class="ach-fact-val">24/7</div>
        <div class="ach-fact-label">Live Stream Coverage</div>
      </div>
      <div class="ach-fact">
        <div class="ach-fact-val">GWR</div>
        <div class="ach-fact-label">World Record Certified</div>
      </div>
      <div class="ach-fact">
        <div class="ach-fact-val">∞</div>
        <div class="ach-fact-label">0 Stream Interruptions</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-header">
    <div class="section-num">05 // CONTACT</div>
    <h2 class="section-title">GET IN TOUCH</h2>
    <div class="section-line"></div>
  </div>
  <div class="contact-layout">
    <div class="contact-info">
      <div class="contact-row">
        <div class="contact-icon">✉</div>
        <div>
          <div class="contact-label">Email</div>
          <div class="contact-val">jaikrishna13012002@gmail.com</div>
        </div>
      </div>
      <div class="contact-row">
        <div class="contact-icon">📞</div>
        <div>
          <div class="contact-label">Phone</div>
          <div class="contact-val">+91 9384648552</div>
        </div>
      </div>
      <div class="contact-row">
        <div class="contact-icon">📍</div>
        <div>
          <div class="contact-label">Location</div>
          <div class="contact-val">Chennai, Tamil Nadu, India</div>
        </div>
      </div>
      <div class="contact-row">
        <div class="contact-icon">🌐</div>
        <div>
          <div class="contact-label">Languages</div>
          <div class="contact-val">English &nbsp;|&nbsp; Tamil &nbsp;|&nbsp; Telugu</div>
        </div>
      </div>
      <div class="contact-row">
        <div class="contact-icon">🎓</div>
        <div>
          <div class="contact-label">Education</div>
          <div class="contact-val">DDGD Vaishanav College, 2022 — 71%</div>
        </div>
      </div>
    </div>

    <div class="interactive-terminal">
      <div class="it-header">
        <div class="t-dot r"></div>
        <div class="t-dot y"></div>
        <div class="t-dot g"></div>
        <span style="margin-left:8px;">terminal — visitor@jaikrishna.portfolio</span>
      </div>
      <div class="it-output" id="it-output">
        <p class="it-line hi">// Interactive Terminal — type 'help' for commands</p>
        <p class="it-line out">Connecting to jaikrishna@mops-station...</p>
        <p class="it-line out">Connection established. Welcome.</p>
        <p class="it-line">&nbsp;</p>
      </div>
      <div class="it-input-row">
        <span class="it-prompt">visitor@portfolio:~$ </span>
        <input class="it-input" id="it-input" type="text" placeholder="type a command..." autocomplete="off" spellcheck="false">
      </div>
    </div>
  </div>
</section>

<footer>
  <span>JAIKRISHNA.N</span> — Media Operations Engineer // Chennai, India
  <span style="color:var(--text-dim);">Built with &lt;terminal /&gt; and neon green ink</span>
  <span id="footer-time">--:--:--</span>
</footer>

<script>
// ===== BIOS BOOT =====
(function() {
  const bar = document.getElementById('bios-bar-fill');
  const barText = document.getElementById('bios-bar-text');
  const bios = document.getElementById('bios');
  const navbar = document.getElementById('navbar');
  let progress = 0;

  const msgs = [
    [20, 'LOADING KERNEL...'],
    [45, 'MOUNTING FILESYSTEMS...'],
    [65, 'STARTING SERVICES...'],
    [80, 'LOADING UI MODULES...'],
    [95, 'FINALIZING...'],
    [100, 'BOOT COMPLETE']
  ];
  let mi = 0;

  const iv = setInterval(() => {
    progress += Math.random() * 3 + 1;
    if (progress > 100) progress = 100;
    bar.style.width = progress + '%';
    if (mi < msgs.length && progress >= msgs[mi][0]) {
      barText.textContent = msgs[mi][1];
      mi++;
    }
    if (progress >= 100) {
      clearInterval(iv);
      setTimeout(() => {
        bios.style.transition = 'opacity 0.6s';
        bios.style.opacity = '0';
        navbar.style.transition = 'opacity 0.6s';
        navbar.style.opacity = '1';
        navbar.style.pointerEvents = 'all';
        setTimeout(() => { bios.style.display = 'none'; startTyping(); }, 600);
      }, 400);
    }
  }, 40);
})();

// ===== CLOCK =====
function updateClock() {
  const now = new Date();
  const t = [now.getHours(), now.getMinutes(), now.getSeconds()]
    .map(v => String(v).padStart(2,'0')).join(':');
  const el = document.getElementById('nav-clock');
  const ft = document.getElementById('footer-time');
  if (el) el.textContent = t;
  if (ft) ft.textContent = t;
}
updateClock();
setInterval(updateClock, 1000);

// ===== SCROLL NAV =====
window.scrollTo = function(id) {
  document.getElementById(id)?.scrollIntoView({ behavior: 'smooth' });
};

// ===== HERO TYPING =====
const sequences = [
  {
    cmd: 'whoami',
    out: [
      '<span style="color:var(--green)">jaikrishna.n</span> — Media Operations Engineer @ Quickplay',
      '3+ years exp in OTT, VOD, and cloud-based ingestion workflows',
      'Based in Chennai, India 🇮🇳'
    ]
  },
  {
    cmd: 'cat skills.txt | head -3',
    out: [
      '<span style="color:var(--cyan)">→</span> Kubernetes + NiFi + Postman (ingestion ops)',
      '<span style="color:var(--cyan)">→</span> MariaDB + Couchbase (SQL + NoSQL)',
      '<span style="color:var(--cyan)">→</span> GCP + AWS S3 + Azure (multi-cloud)'
    ]
  },
  {
    cmd: 'echo $ACHIEVEMENT',
    out: [
      '<span style="color:var(--amber)">★</span> Guinness World Record — 13 days, 24x7 live streaming',
      '<span style="color:var(--amber)">★</span> 30% ingestion efficiency improvement @ Quickplay',
      '<span style="color:var(--amber)">★</span> 95% CSAT rate @ Gavs Technologies'
    ]
  }
];

let seqIdx = 0;
function startTyping() {
  const cmdEl = document.getElementById('typing-cmd');
  const outEl = document.getElementById('typing-output');
  const cursor = document.getElementById('hero-cursor');
  if (!cmdEl) return;

  const seq = sequences[seqIdx % sequences.length];
  let ci = 0;
  cmdEl.textContent = '';
  outEl.innerHTML = '';
  cursor.style.display = 'inline-block';

  const typeInterval = setInterval(() => {
    if (ci < seq.cmd.length) {
      cmdEl.textContent += seq.cmd[ci++];
    } else {
      clearInterval(typeInterval);
      cursor.style.display = 'none';
      setTimeout(() => {
        let oi = 0;
        const outInterval = setInterval(() => {
          if (oi < seq.out.length) {
            const p = document.createElement('p');
            p.className = 'terminal-line terminal-out';
            p.innerHTML = seq.out[oi++];
            outEl.appendChild(p);
          } else {
            clearInterval(outInterval);
            setTimeout(() => {
              seqIdx++;
              startTyping();
            }, 3000);
          }
        }, 300);
      }, 400);
    }
  }, 80);
}

// ===== INTERACTIVE TERMINAL =====
const itCommands = {
  help: () => [
    {cls:'hi', t:'Available commands:'},
    {cls:'out', t:'  whoami     — learn about Jaikrishna'},
    {cls:'out', t:'  skills     — list technical skills'},
    {cls:'out', t:'  experience — work history'},
    {cls:'out', t:'  projects   — OTT platforms worked on'},
    {cls:'out', t:'  contact    — get contact info'},
    {cls:'out', t:'  record     — Guinness World Record details'},
    {cls:'out', t:'  clear      — clear terminal'},
  ],
  whoami: () => [
    {cls:'hi', t:'JAIKRISHNA.N — Media Operations Engineer'},
    {cls:'out', t:'Location  : Chennai, Tamil Nadu, India'},
    {cls:'out', t:'Email     : jaikrishna13012002@gmail.com'},
    {cls:'out', t:'Phone     : +91 9384648552'},
    {cls:'out', t:'Exp       : 3+ years (OTT, VOD, Cloud Ingestion)'},
    {cls:'out', t:'Languages : English, Tamil, Telugu'},
  ],
  skills: () => [
    {cls:'hi', t:'Core Skills:'},
    {cls:'amber', t:'[CLOUD]    AWS · GCP · Azure · Docker · Kubernetes'},
    {cls:'out',   t:'[DATABASE] MariaDB · Couchbase · PostgreSQL · MongoDB'},
    {cls:'amber', t:'[STREAM]   RTMP · HLS · DASH · SRT · RTSP · HLS'},
    {cls:'out',   t:'[TOOLS]    NiFi · Postman · Grafana · Kibana · K9s'},
    {cls:'amber', t:'[OS]       Linux · Windows · macOS · Shell Scripting'},
  ],
  experience: () => [
    {cls:'hi', t:'Work History:'},
    {cls:'amber', t:'[2025–NOW] Quickplay Media — Media Ops Engineer MOPS'},
    {cls:'out',   t:'           OTT ingestion, Kubernetes, NiFi, multi-cloud'},
    {cls:'amber', t:'[2023–24]  CDTech Innovations (Livebox) — Tech Support Eng'},
    {cls:'out',   t:'           Streaming infra, OTT builds, network management'},
    {cls:'amber', t:'[2024]     Gavs Technologies — Service Desk'},
    {cls:'out',   t:'           Shutterfly support, 95% CSAT, Salesforce CRM'},
  ],
  projects: () => [
    {cls:'hi', t:'OTT Platforms:'},
    {cls:'out', t:'  AhaVideo    — Telugu/Tamil regional OTT'},
    {cls:'out', t:'  CignalPlay  — Philippines live event OTT'},
    {cls:'out', t:'  PLive       — Sports-focused OTT (Philippines)'},
    {cls:'out', t:'  LocalNow    — U.S. local news streaming'},
    {cls:'out', t:'  CanelaTV    — Spanish-language OTT'},
    {cls:'out', t:'  GothamSport — Sports OTT ecosystem'},
  ],
  contact: () => [
    {cls:'hi', t:'Contact Information:'},
    {cls:'out', t:'Email    : jaikrishna13012002@gmail.com'},
    {cls:'out', t:'Phone    : +91 9384648552'},
    {cls:'out', t:'Location : Chennai, Tamil Nadu, India'},
  ],
  record: () => [
    {cls:'amber', t:'★ GUINNESS WORLD RECORD ★'},
    {cls:'out', t:'Event    : SRM University Marathon'},
    {cls:'out', t:'Route    : Chandigarh → Chennai'},
    {cls:'out', t:'Duration : 13 Days'},
    {cls:'out', t:'Role     : Team Lead, Live Streaming Ops'},
    {cls:'out', t:'Stream   : 24x7 uninterrupted coverage'},
    {cls:'amber', t:'Status   : CERTIFIED ✓'},
  ],
  clear: () => null,
};

const itOutput = document.getElementById('it-output');
const itInput  = document.getElementById('it-input');

function itPrint(lines) {
  lines.forEach(({cls, t}) => {
    const p = document.createElement('p');
    p.className = 'it-line ' + cls;
    p.textContent = t;
    itOutput.appendChild(p);
  });
  itOutput.scrollTop = itOutput.scrollHeight;
}

itInput.addEventListener('keydown', (e) => {
  if (e.key !== 'Enter') return;
  const raw = itInput.value.trim();
  itInput.value = '';
  if (!raw) return;

  // echo command
  const cmdLine = document.createElement('p');
  cmdLine.className = 'it-line cmd';
  cmdLine.textContent = '$ ' + raw;
  itOutput.appendChild(cmdLine);

  const cmd = raw.toLowerCase().split(' ')[0];

  if (cmd === 'clear') {
    itOutput.innerHTML = '';
    return;
  }

  const handler = itCommands[cmd];
  if (handler) {
    const result = handler();
    if (result) itPrint(result);
  } else {
    itPrint([{cls: 'err', t: `command not found: ${raw}. Type 'help' for commands.`}]);
  }

  itOutput.scrollTop = itOutput.scrollHeight;
});
</script>
</body>
</html>
