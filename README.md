<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UP Board Class 12 Maths – Important Questions & Model Paper 2026</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,800;0,900;1,400&family=DM+Sans:wght@300;400;500;600;700&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0d0d1a;--surface:#131326;--card:#1a1a35;--border:#2a2a55;
  --ink:#e8e8ff;--muted:#7a7aaa;--gold:#f0c040;
  --c1:#6c63ff;--c2:#00cfb4;--c3:#ff6b9d;--c4:#ffa94d;--c5:#4db8ff;
  --ans-bg:#0e1f1a;--ans-bd:#1a4a3a;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--ink);font-family:'DM Sans',sans-serif;overflow-x:hidden}

/* ANIMATED BG */
body::before{content:'';position:fixed;inset:0;background:
  radial-gradient(ellipse 60% 40% at 20% 20%,rgba(108,99,255,.08),transparent 60%),
  radial-gradient(ellipse 50% 50% at 80% 80%,rgba(0,207,180,.06),transparent 60%),
  radial-gradient(ellipse 40% 40% at 60% 10%,rgba(255,107,157,.05),transparent 50%);
  pointer-events:none;z-index:0;}

/* TABS */
.tab-nav{position:sticky;top:0;z-index:300;background:rgba(10,10,25,.95);backdrop-filter:blur(20px);border-bottom:1px solid var(--border);display:flex;justify-content:center;}
.tab-btn{padding:15px 36px;font-family:'DM Sans',sans-serif;font-size:.8rem;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:rgba(232,232,255,.4);background:none;border:none;cursor:pointer;border-bottom:2px solid transparent;margin-bottom:-1px;transition:all .2s;}
.tab-btn:hover{color:rgba(232,232,255,.7);}
.tab-btn.active{color:var(--gold);border-bottom-color:var(--gold);}

/* HEADER */
.site-header{padding:64px 24px 56px;text-align:center;position:relative;overflow:hidden;}
.site-header::after{content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--c1),var(--c2),var(--c3),transparent);}
.board-badge{display:inline-flex;align-items:center;gap:8px;border:1px solid rgba(108,99,255,.5);color:var(--c1);font-size:11px;font-weight:700;letter-spacing:3px;text-transform:uppercase;padding:7px 22px;border-radius:30px;margin-bottom:24px;background:rgba(108,99,255,.08);position:relative;z-index:1;}
.site-header h1{font-family:'Playfair Display',serif;font-size:clamp(2rem,5vw,3.8rem);font-weight:900;line-height:1.08;color:#fff;position:relative;z-index:1;margin-bottom:10px;}
.site-header h1 span.hl{background:linear-gradient(135deg,var(--gold),var(--c4));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.header-sub{color:var(--muted);font-size:.9rem;max-width:620px;margin:0 auto 34px;line-height:1.7;position:relative;z-index:1;}
.hstats{display:flex;justify-content:center;border:1px solid var(--border);border-radius:12px;overflow:hidden;background:rgba(255,255,255,.03);max-width:680px;margin:0 auto;position:relative;z-index:1;}
.hstat{padding:16px 20px;text-align:center;border-right:1px solid var(--border);flex:1;}
.hstat:last-child{border-right:none;}
.hstat-n{display:block;font-family:'DM Mono',monospace;font-size:1.5rem;font-weight:500;color:var(--gold);}
.hstat-l{display:block;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-top:3px;}

/* PAGES */
.page{display:none;}
.page.active{display:block;}

/* LAYOUT */
.study-layout{max-width:1200px;margin:0 auto;padding:36px 16px 100px;display:grid;grid-template-columns:260px 1fr;gap:24px;position:relative;z-index:1;}
.sidebar{position:sticky;top:58px;align-self:start;}
.scard{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:16px;margin-bottom:14px;backdrop-filter:blur(10px);}
.scard-title{font-size:10px;font-weight:700;letter-spacing:3px;text-transform:uppercase;color:var(--muted);margin-bottom:12px;padding-bottom:10px;border-bottom:1px solid var(--border);}
.nav-link{display:flex;align-items:center;gap:9px;padding:9px 11px;border-radius:8px;margin-bottom:3px;font-size:.81rem;font-weight:600;color:var(--ink);cursor:pointer;border:1px solid transparent;transition:all .18s;}
.nav-link:hover{background:rgba(255,255,255,.05);border-color:var(--border);}
.nav-dot{width:9px;height:9px;border-radius:50%;flex-shrink:0;}
.nav-badge{margin-left:auto;font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);background:rgba(255,255,255,.06);padding:2px 8px;border-radius:8px;}
.search-box{display:flex;align-items:center;gap:8px;background:var(--surface);border:1.5px solid var(--border);border-radius:9px;padding:10px 13px;margin-bottom:0;}
.search-box input{flex:1;background:none;border:none;outline:none;font-family:'DM Sans',sans-serif;font-size:.83rem;color:var(--ink);}
.search-box input::placeholder{color:var(--muted);}
.marks-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin-bottom:10px;}
.marks-box{background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:9px;padding:10px;text-align:center;}
.marks-n{font-family:'DM Mono',monospace;font-size:1rem;font-weight:500;}
.marks-l{font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:1px;margin-top:2px;}
.tip-box{background:rgba(240,192,64,.06);border:1px solid rgba(240,192,64,.25);border-left:3px solid var(--gold);border-radius:0 8px 8px 0;padding:11px 12px;font-size:.75rem;line-height:1.75;color:#d4aa30;}
.tip-box strong{color:var(--gold);}
.prog-wrap{background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:8px;padding:11px;}
.prog-row{display:flex;justify-content:space-between;font-size:.75rem;color:var(--muted);margin-bottom:7px;}
.prog-val{font-family:'DM Mono',monospace;font-weight:700;color:var(--ink);}
.prog-bar{height:4px;background:rgba(255,255,255,.08);border-radius:4px;overflow:hidden;}
.prog-fill{height:100%;background:linear-gradient(90deg,var(--c1),var(--c2));border-radius:4px;transition:width .4s;width:0%;}

/* CHAPTER CARDS */
.chapter{background:var(--card);border:1px solid var(--border);border-radius:16px;margin-bottom:20px;overflow:hidden;box-shadow:0 4px 20px rgba(0,0,0,.3);animation:fadeUp .4s ease both;}
@keyframes fadeUp{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:translateY(0)}}
.ch-head{display:flex;align-items:center;gap:12px;padding:18px 22px;cursor:pointer;user-select:none;background:var(--card);transition:background .2s;border-bottom:1px solid transparent;}
.chapter.open .ch-head{border-bottom-color:var(--border);}
.ch-head:hover{background:rgba(255,255,255,.03);}
.ch-tag{font-family:'DM Mono',monospace;font-size:10px;font-weight:500;color:#000;padding:4px 10px;border-radius:5px;flex-shrink:0;}
.ch-icon{font-size:22px;flex-shrink:0;}
.ch-info{flex:1;}
.ch-name{font-family:'Playfair Display',serif;font-size:1rem;font-weight:700;color:#fff;}
.ch-sub{font-size:10px;color:var(--muted);margin-top:3px;}
.ch-mbadge{font-family:'DM Mono',monospace;font-size:11px;font-weight:500;color:#000;padding:4px 12px;border-radius:20px;flex-shrink:0;}
.ch-arrow{color:var(--muted);font-size:12px;transition:transform .3s;flex-shrink:0;}
.chapter.open .ch-arrow{transform:rotate(180deg);}
.ch-body{display:none;padding:0 22px 26px;}
.chapter.open .ch-body{display:block;}

/* SECTION DIVIDERS */
.qtype{display:flex;align-items:center;gap:11px;font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;color:var(--muted);margin:22px 0 10px;}
.qtype::before,.qtype::after{content:'';flex:1;height:1px;background:var(--border);}

/* QUESTION ITEMS */
.q-wrap{margin-bottom:8px;}
.q-item{display:flex;align-items:flex-start;gap:11px;padding:12px 14px;border-radius:10px;border:1px solid var(--border);background:rgba(255,255,255,.02);cursor:default;transition:all .15s;position:relative;overflow:hidden;}
.q-item::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--qc,var(--gold));opacity:0;transition:opacity .2s;}
.q-item:hover{border-color:rgba(255,255,255,.12);background:rgba(255,255,255,.04);}
.q-item:hover::before{opacity:1;}
.q-item.hot::after{content:'★ HOT';position:absolute;top:7px;right:-1px;background:var(--gold);color:#000;font-size:9px;font-weight:800;letter-spacing:1px;padding:2px 8px 2px 6px;border-radius:4px 0 0 4px;}
.q-num{font-family:'DM Mono',monospace;font-size:10px;font-weight:500;color:#000;padding:3px 7px;border-radius:5px;flex-shrink:0;min-width:34px;text-align:center;margin-top:2px;}
.q-text{font-size:.86rem;line-height:1.72;color:var(--ink);flex:1;}
.q-text em{font-style:normal;font-weight:700;color:var(--gold);}
.q-text code{font-family:'DM Mono',monospace;background:rgba(108,99,255,.15);color:#a99eff;padding:1px 6px;border-radius:4px;font-size:.82rem;}
.q-right{display:flex;flex-direction:column;align-items:flex-end;gap:5px;flex-shrink:0;}
.q-marks{font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);background:rgba(255,255,255,.06);border:1px solid var(--border);padding:2px 8px;border-radius:8px;}
.ans-btn{font-size:10px;font-weight:700;padding:4px 12px;border-radius:6px;border:none;cursor:pointer;transition:all .15s;white-space:nowrap;}

/* ANSWER BOX */
.ans-box{display:none;background:var(--ans-bg);border:1px solid var(--ans-bd);border-radius:0 0 10px 10px;padding:17px 19px;margin-top:-1px;animation:sd .25s ease;}
.ans-box.show{display:block;}
@keyframes sd{from{opacity:0;transform:translateY(-6px)}to{opacity:1;transform:translateY(0)}}
.ans-lbl{font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#4ade80;margin-bottom:10px;display:flex;align-items:center;gap:8px;}
.ans-lbl::after{content:'';flex:1;height:1px;background:rgba(74,222,128,.15);}
.ans-body{font-size:.83rem;line-height:1.9;color:#a8f0c0;}
.ans-body strong{color:#4ade80;}
.ans-body ul,.ans-body ol{margin:8px 0 8px 20px;}
.ans-body li{margin-bottom:5px;}
.ans-body .math{font-family:'DM Mono',monospace;background:rgba(0,0,0,.3);border:1px solid rgba(74,222,128,.15);color:#86efac;padding:10px 14px;border-radius:8px;margin:8px 0;font-size:.82rem;line-height:1.9;display:block;white-space:pre-wrap;}
.ans-body table{width:100%;border-collapse:collapse;margin:10px 0;font-size:.79rem;}
.ans-body th{background:rgba(74,222,128,.1);color:#4ade80;padding:7px 11px;text-align:left;border:1px solid rgba(74,222,128,.15);}
.ans-body td{padding:6px 11px;border:1px solid rgba(255,255,255,.06);color:#a8f0c0;vertical-align:top;}
.ans-body tr:nth-child(even) td{background:rgba(255,255,255,.03);}
.key-note{background:rgba(240,192,64,.07);border-left:3px solid var(--gold);padding:9px 13px;border-radius:0 7px 7px 0;font-size:.78rem;color:#d4aa30;margin:9px 0;}
.step{counter-increment:step;position:relative;padding-left:24px;margin-bottom:8px;}
.step::before{content:counter(step);position:absolute;left:0;top:2px;width:18px;height:18px;background:var(--c1);color:#fff;border-radius:50%;font-size:10px;font-weight:700;display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;}
.steps{counter-reset:step;}

/* FLOAT */
.float-panel{position:fixed;bottom:22px;right:22px;z-index:500;background:var(--card);border:1px solid var(--border);border-radius:16px;padding:14px 18px;box-shadow:0 8px 40px rgba(0,0,0,.4);display:flex;flex-direction:column;align-items:center;gap:5px;min-width:125px;}
.fp-lbl{font-size:10px;color:var(--muted);letter-spacing:2px;text-transform:uppercase;}
.fp-num{font-family:'DM Mono',monospace;font-size:1.8rem;font-weight:500;color:var(--c2);line-height:1;}
.fp-tot{font-size:11px;color:var(--muted);}
.fp-btn{background:var(--c1);border:none;color:#fff;font-family:'DM Sans',sans-serif;font-size:11px;font-weight:700;padding:5px 16px;border-radius:20px;cursor:pointer;margin-top:4px;}

/* ══ QUESTION PAPER ══ */
#page-paper{background:#1a1a2e;padding:30px 0 70px;position:relative;z-index:1;}
.paper-wrapper{max-width:880px;margin:0 auto;padding:0 18px;}
.print-bar{background:rgba(0,0,0,.5);border:1px solid var(--border);color:#fff;display:flex;align-items:center;justify-content:space-between;padding:13px 22px;border-radius:12px;margin-bottom:24px;}
.print-bar span{font-size:.8rem;color:var(--muted);}
.print-btn{background:var(--gold);color:#000;border:none;font-family:'DM Sans',sans-serif;font-size:12px;font-weight:800;padding:9px 24px;border-radius:7px;cursor:pointer;}
.paper-sheet{background:#fff;border-radius:4px;box-shadow:0 12px 60px rgba(0,0,0,.5);}
.paper-inner{padding:48px 58px;color:#111;}

/* PAPER HEADER */
.paper-top{text-align:center;border-bottom:3px double #333;padding-bottom:18px;margin-bottom:18px;}
.p-board{font-size:11px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#666;margin-bottom:4px;}
.p-exam{font-family:'Playfair Display',serif;font-size:1.5rem;font-weight:900;color:#111;margin-bottom:4px;}
.p-sub-head{font-family:'Playfair Display',serif;font-size:1.1rem;font-weight:700;color:#c0392b;margin-bottom:12px;}
.p-subject-strip{font-size:1rem;font-weight:700;background:#111;color:#fff;display:inline-block;padding:6px 26px;letter-spacing:2px;margin-bottom:10px;}
.p-meta{display:flex;justify-content:space-between;font-size:12.5px;font-weight:700;color:#111;margin-bottom:5px;}
.p-note{font-size:11px;color:#666;font-style:italic;margin-top:8px;}
.instruct{background:#fef9e7;border:1px solid #f0d080;padding:14px 18px;margin-bottom:24px;border-radius:4px;}
.instruct p{font-size:12px;line-height:1.82;color:#7d5a00;margin-bottom:4px;}
.instruct strong{color:#8b4513;}
.p-sec{background:#111;color:#fff;padding:9px 18px;margin:28px 0 16px;display:flex;justify-content:space-between;align-items:center;border-radius:2px;}
.p-sec-name{font-family:'Playfair Display',serif;font-size:1rem;font-weight:700;}
.p-sec-marks{font-family:'DM Mono',monospace;font-size:12px;color:#f0c040;}
.pq{margin-bottom:18px;color:#111;}
.pq-row{display:flex;gap:12px;margin-bottom:5px;}
.pq-n{font-family:'DM Mono',monospace;font-size:12px;min-width:30px;flex-shrink:0;color:#111;font-weight:600;}
.pq-t{font-size:13px;line-height:1.8;color:#111;flex:1;}
.pq-m{font-family:'DM Mono',monospace;font-size:11px;color:#666;flex-shrink:0;align-self:flex-start;border:1px solid #ccc;padding:2px 8px;border-radius:4px;}
.pq-subs{margin-left:42px;margin-top:7px;}
.pq-sub{display:flex;gap:9px;margin-bottom:6px;font-size:12.5px;line-height:1.75;color:#111;}
.pq-sn{font-family:'DM Mono',monospace;min-width:24px;flex-shrink:0;color:#333;}
.mcq-opts{display:grid;grid-template-columns:1fr 1fr;gap:3px;margin:5px 0 5px 42px;}
.mcq-opt{font-size:12.5px;padding:2px 0;color:#111;}
.or-div{text-align:center;font-weight:800;font-size:12px;letter-spacing:3px;color:#999;margin:10px 0;position:relative;}
.or-div::before,.or-div::after{content:'';position:absolute;top:50%;width:42%;height:1px;background:#ddd;}
.or-div::before{left:0;}.or-div::after{right:0;}
.p-footer{border-top:2px solid #111;padding-top:14px;margin-top:36px;display:flex;justify-content:space-between;font-size:11px;color:#666;}
.blank-l{border-bottom:1px solid #666;width:175px;display:inline-block;margin-left:8px;vertical-align:middle;}
.math-p{font-family:'DM Mono',monospace;font-size:12.5px;color:#111;}

@media print{
  .tab-nav,.site-header,.print-bar,.float-panel{display:none!important;}
  #page-paper{display:block!important;background:none;padding:0;}
  #page-study{display:none!important;}
  body{background:#fff;}
  body::before{display:none;}
  .paper-wrapper{padding:0;max-width:100%;}
  .paper-sheet{box-shadow:none;}
  .paper-inner{padding:22px 28px;}
  .pq{page-break-inside:avoid;}
}
@media(max-width:800px){
  .study-layout{grid-template-columns:1fr;}
  .sidebar{position:static;}
  .hstats{flex-wrap:wrap;}
  .hstat{flex:1 1 45%;border-right:none;border-bottom:1px solid var(--border);}
  .tab-btn{padding:12px 14px;font-size:.73rem;letter-spacing:.8px;}
  .paper-inner{padding:24px 16px;}
  .mcq-opts{grid-template-columns:1fr;}
}
</style>
</head>
<body>

<nav class="tab-nav">
  <button class="tab-btn active" data-tab="study">📐 Important Questions & Answers</button>
  <button class="tab-btn" data-tab="paper">📄 Model Question Paper</button>
</nav>

<div class="site-header">
  <div class="board-badge">🎓 UPMSP · UP Board · Class 12 · 2025–26</div>
  <h1>गणित <span class="hl">(Mathematics)</span><br>Most Important Questions 2026</h1>
  <p class="header-sub">Chapter-wise most repeated questions with full solutions + UP Board style Model Paper — Calculus, Algebra, Vectors, 3D Geometry, Probability & more</p>
  <div class="hstats">
    <div class="hstat"><span class="hstat-n">100+</span><span class="hstat-l">Questions</span></div>
    <div class="hstat"><span class="hstat-n">6</span><span class="hstat-l">Units</span></div>
    <div class="hstat"><span class="hstat-n">100</span><span class="hstat-l">Total Marks</span></div>
    <div class="hstat"><span class="hstat-n">3h 15m</span><span class="hstat-l">Duration</span></div>
    <div class="hstat"><span class="hstat-n">★HOT</span><span class="hstat-l">Repeated Qs</span></div>
  </div>
</div>

<!-- PAGE STUDY -->
<div id="page-study" class="page active">
<div class="study-layout">

<aside class="sidebar">
  <div class="scard">
    <div class="scard-title">📐 Jump to Unit</div>
    <div class="nav-link" onclick="openCh('rel')"><span class="nav-dot" style="background:var(--c1)"></span>Relations & Functions<span class="nav-badge">10M</span></div>
    <div class="nav-link" onclick="openCh('alg')"><span class="nav-dot" style="background:var(--c3)"></span>Algebra (Matrices/Det.)<span class="nav-badge">13M</span></div>
    <div class="nav-link" onclick="openCh('calc')"><span class="nav-dot" style="background:var(--c2)"></span>Calculus<span class="nav-badge">44M</span></div>
    <div class="nav-link" onclick="openCh('vec')"><span class="nav-dot" style="background:var(--c4)"></span>Vectors & 3D Geometry<span class="nav-badge">17M</span></div>
    <div class="nav-link" onclick="openCh('lpp')"><span class="nav-dot" style="background:var(--c5)"></span>Linear Programming<span class="nav-badge">6M</span></div>
    <div class="nav-link" onclick="openCh('prob')"><span class="nav-dot" style="background:var(--gold)"></span>Probability<span class="nav-badge">10M</span></div>
  </div>
  <div class="scard">
    <div class="scard-title">📊 Marks Weightage</div>
    <div class="marks-grid">
      <div class="marks-box"><div class="marks-n" style="color:var(--c1)">10M</div><div class="marks-l">Relations</div></div>
      <div class="marks-box"><div class="marks-n" style="color:var(--c3)">13M</div><div class="marks-l">Algebra</div></div>
      <div class="marks-box"><div class="marks-n" style="color:var(--c2)">44M</div><div class="marks-l">Calculus</div></div>
      <div class="marks-box"><div class="marks-n" style="color:var(--c4)">17M</div><div class="marks-l">Vectors</div></div>
      <div class="marks-box"><div class="marks-n" style="color:var(--c5)">6M</div><div class="marks-l">LPP</div></div>
      <div class="marks-box"><div class="marks-n" style="color:var(--gold)">10M</div><div class="marks-l">Prob.</div></div>
    </div>
    <div class="tip-box"><strong>💡 Board Tip:</strong> Calculus (44M) is the most important unit — Integrals, Derivatives, Differential Equations are MUST. ★ HOT = appeared 3+ times. Integration by parts + area between curves are guaranteed every year!</div>
  </div>
  <div class="scard">
    <div class="scard-title">🔍 Search Questions</div>
    <div class="search-box"><span style="color:var(--muted)">🔍</span><input type="text" placeholder="e.g. integration, matrix, probability…" oninput="searchQ(this.value)"></div>
  </div>
  <div class="scard">
    <div class="scard-title">📊 My Progress</div>
    <div class="prog-wrap">
      <div class="prog-row"><span>Questions Revised</span><span class="prog-val" id="prog-val">0/100</span></div>
      <div class="prog-bar"><div class="prog-fill" id="prog-fill"></div></div>
    </div>
  </div>
</aside>

<main>

<!-- ██████ RELATIONS & FUNCTIONS ██████ -->
<div class="chapter open" id="rel">
  <div class="ch-head" onclick="toggle('rel')" style="border-left:5px solid var(--c1)">
    <span class="ch-tag" style="background:var(--c1)">UNIT 1</span><span class="ch-icon">🔗</span>
    <div class="ch-info"><div class="ch-name">Relations & Functions + Inverse Trigonometry</div><div class="ch-sub">Types of Relations · Functions · Inverse Trig Functions · Properties</div></div>
    <span class="ch-mbadge" style="background:var(--c1)">10 Marks</span><span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">
    <div class="qtype" style="color:var(--c1)">🔗 Relations & Functions</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c1)">
        <span class="q-num" style="background:var(--c1)">R1</span>
        <span class="q-text">Prove that the relation <em>R in set A = {1, 2, 3, 4, 5}</em> defined as R = {(a,b) : |a – b| is even} is an <em>equivalence relation</em>.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(108,99,255,.2);color:#a99eff;border:1px solid rgba(108,99,255,.4)" onclick="showAns(event,'r1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="r1"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">An equivalence relation must be <strong>Reflexive, Symmetric, and Transitive</strong>.<br><br>
        <strong>Reflexive:</strong> For any a ∈ A, |a – a| = 0, which is even. So (a, a) ∈ R. ✓<br><br>
        <strong>Symmetric:</strong> If (a, b) ∈ R, then |a – b| is even. Since |a – b| = |b – a|, |b – a| is also even. So (b, a) ∈ R. ✓<br><br>
        <strong>Transitive:</strong> If (a, b) ∈ R and (b, c) ∈ R, then |a – b| is even and |b – c| is even.<br>
        <span class="math">|a – c| = |(a – b) + (b – c)| 
Since (a–b) and (b–c) are both even, their sum is also even.
So |a – c| is even → (a, c) ∈ R. ✓</span>
        Since R is reflexive, symmetric, and transitive, <strong>R is an equivalence relation.</strong>
        <div class="key-note">💡 Equivalence classes of R: {1,3,5} (odd numbers) and {2,4} (even numbers). Every element is related only to elements of the same parity.</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c1)">
        <span class="q-num" style="background:var(--c1)">R2</span>
        <span class="q-text">Show that the function <em>f : R → R</em> defined by <em>f(x) = 2x + 3</em> is <em>one-one (injective) and onto (surjective)</em>. Hence find f⁻¹.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(108,99,255,.2);color:#a99eff;border:1px solid rgba(108,99,255,.4)" onclick="showAns(event,'r2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="r2"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>One-One (Injective):</strong><br>
        Let f(x₁) = f(x₂)<br>
        <span class="math">⇒ 2x₁ + 3 = 2x₂ + 3
⇒ 2x₁ = 2x₂
⇒ x₁ = x₂</span>
        Therefore f is one-one. ✓<br><br>
        <strong>Onto (Surjective):</strong><br>
        For any y ∈ R, we need x ∈ R such that f(x) = y<br>
        <span class="math">2x + 3 = y  ⟹  x = (y – 3)/2 ∈ R</span>
        Since for every y ∈ R, there exists x = (y–3)/2 ∈ R, f is onto. ✓<br><br>
        <strong>Inverse Function:</strong><br>
        Let y = f(x) = 2x + 3<br>
        <span class="math">x = (y – 3)/2
∴ f⁻¹(x) = (x – 3)/2</span>
        <div class="key-note">💡 A function has inverse only if it is bijective (both one-one and onto). A bijective function from R to R is always a bijection.</div></div>
      </div>
    </div>

    <div class="qtype" style="color:var(--c1)">🔗 Inverse Trigonometric Functions</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c1)">
        <span class="q-num" style="background:var(--c1)">R3</span>
        <span class="q-text">Prove that: <em>tan⁻¹(1/2) + tan⁻¹(1/3) = π/4</em>. Also write the <em>principal value</em> of sin⁻¹(√3/2).</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(108,99,255,.2);color:#a99eff;border:1px solid rgba(108,99,255,.4)" onclick="showAns(event,'r3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="r3"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>Using the formula:</strong> tan⁻¹x + tan⁻¹y = tan⁻¹[(x+y)/(1–xy)], when xy < 1<br><br>
        Here x = 1/2, y = 1/3 → xy = 1/6 < 1 ✓
        <span class="math">tan⁻¹(1/2) + tan⁻¹(1/3) = tan⁻¹[(1/2 + 1/3) / (1 – 1/6)]
= tan⁻¹[(3/6 + 2/6) / (5/6)]
= tan⁻¹[(5/6) / (5/6)]
= tan⁻¹(1)
= π/4</span>
        <strong>Hence proved. ✓</strong><br><br>
        <strong>Principal Value of sin⁻¹(√3/2):</strong><br>
        The principal value branch of sin⁻¹ is [–π/2, π/2]<br>
        sin(π/3) = √3/2, and π/3 ∈ [–π/2, π/2]<br>
        <span class="math">∴ sin⁻¹(√3/2) = π/3</span>
        <div class="key-note">💡 Always check the range (principal value branch) when solving inverse trig. sin⁻¹ range: [–π/2, π/2] | cos⁻¹ range: [0, π] | tan⁻¹ range: (–π/2, π/2)</div></div>
      </div>
    </div>
  </div>
</div>

<!-- ██████ ALGEBRA ██████ -->
<div class="chapter" id="alg">
  <div class="ch-head" onclick="toggle('alg')" style="border-left:5px solid var(--c3)">
    <span class="ch-tag" style="background:var(--c3)">UNIT 2</span><span class="ch-icon">🔢</span>
    <div class="ch-info"><div class="ch-name">Algebra — Matrices & Determinants</div><div class="ch-sub">Matrix Operations · Inverse · Determinants · Cramer's Rule · Properties</div></div>
    <span class="ch-mbadge" style="background:var(--c3)">13 Marks</span><span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">
    <div class="qtype" style="color:var(--c3)">🔢 Matrices</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c3)">
        <span class="q-num" style="background:var(--c3)">A1</span>
        <span class="q-text">If A = [[2,3],[1,2]], find A⁻¹ (inverse of A) using the <em>adjoint method</em>. Verify that A · A⁻¹ = I.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(255,107,157,.15);color:#ff9cc0;border:1px solid rgba(255,107,157,.3)" onclick="showAns(event,'a1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a1"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Given: A = [[2, 3], [1, 2]]<br><br>
        <strong>Step 1: Find |A| (determinant)</strong>
        <span class="math">|A| = (2)(2) – (3)(1) = 4 – 3 = 1 ≠ 0</span>
        Since |A| ≠ 0, A⁻¹ exists. ✓<br><br>
        <strong>Step 2: Find Cofactor Matrix</strong>
        <span class="math">C₁₁ = +2,  C₁₂ = –1
C₂₁ = –3,  C₂₂ = +2</span>
        <strong>Step 3: Adjoint of A = Transpose of Cofactor Matrix</strong>
        <span class="math">adj(A) = [[2, –3], [–1, 2]]</span>
        <strong>Step 4: A⁻¹ = adj(A) / |A|</strong>
        <span class="math">A⁻¹ = (1/1) × [[2, –3], [–1, 2]] = [[2, –3], [–1, 2]]</span>
        <strong>Verification: A · A⁻¹</strong>
        <span class="math">[[2,3],[1,2]] × [[2,–3],[–1,2]]
= [[4–3, –6+6],[2–2, –3+4]]
= [[1, 0],[0, 1]] = I ✓</span>
        <div class="key-note">💡 Formula: A⁻¹ = adj(A)/|A|. For 2×2 matrix [[a,b],[c,d]], adj = [[d,–b],[–c,a]]</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c3)">
        <span class="q-num" style="background:var(--c3)">A2</span>
        <span class="q-text">Solve the system of equations using <em>matrix method (A⁻¹ method)</em>: x + y + z = 6, 2x + y – z = 2, x – 2y + z = –3</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(255,107,157,.15);color:#ff9cc0;border:1px solid rgba(255,107,157,.3)" onclick="showAns(event,'a2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a2"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Writing as AX = B, where:
        <span class="math">A = [[1,1,1],[2,1,–1],[1,–2,1]],  X = [[x],[y],[z]],  B = [[6],[2],[–3]]</span>
        <strong>Find |A|:</strong>
        <span class="math">|A| = 1(1×1 – (–1)(–2)) – 1(2×1 – (–1)×1) + 1(2×(–2) – 1×1)
     = 1(1–2) – 1(2+1) + 1(–4–1)
     = 1(–1) – 1(3) + 1(–5)
     = –1 – 3 – 5 = –9 ≠ 0 ✓</span>
        <strong>Find Cofactors and adj(A):</strong>
        <span class="math">C₁₁ = –1, C₁₂ = –3, C₁₃ = –5
C₂₁ = –3, C₂₂ = 0,  C₂₃ = 3
C₃₁ = –2, C₃₂ = 3,  C₃₃ = –1

adj(A) = [[–1,–3,–2],[–3,0,3],[–5,3,–1]]</span>
        <strong>A⁻¹ = adj(A)/|A|:</strong>
        <span class="math">X = A⁻¹B = (1/–9) × [[–1,–3,–2],[–3,0,3],[–5,3,–1]] × [[6],[2],[–3]]</span>
        <strong>Multiply:</strong>
        <span class="math">Row 1: (–1)(6)+(–3)(2)+(–2)(–3) = –6–6+6 = –9 → x = –9/–9 = 1
Row 2: (–3)(6)+(0)(2)+(3)(–3) = –18+0–9 = –27 → y = –27/–9 = 3
Row 3: (–5)(6)+(3)(2)+(–1)(–3) = –30+6+3 = –21 → z = –21/–9 ≈ 2.33</span>
        <strong>Answer: x = 1, y = 2, z = 3</strong>
        <div class="key-note">💡 Always verify: substitute x=1, y=2, z=3 back into original equations. This is a guaranteed 5-mark question in UP Board!</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c3)">
        <span class="q-num" style="background:var(--c3)">A3</span>
        <span class="q-text">Using properties of determinants, prove: <em>|a+b+2c, a, b; c, b+c+2a, b; c, a, c+a+2b| = 2(a+b+c)³</em></span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(255,107,157,.15);color:#ff9cc0;border:1px solid rgba(255,107,157,.3)" onclick="showAns(event,'a3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a3"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Let Δ = determinant with rows: [a+b+2c, a, b], [c, b+c+2a, b], [c, a, c+a+2b]<br><br>
        <strong>C₁ → C₁ + C₂ + C₃ (Add all columns to Column 1):</strong>
        <span class="math">New C₁: 
Row 1: (a+b+2c) + a + b = 2(a+b+c)
Row 2: c + (b+c+2a) + b = 2(a+b+c)  
Row 3: c + a + (c+a+2b) = 2(a+b+c)</span>
        <strong>Take out 2(a+b+c) common from C₁:</strong>
        <span class="math">Δ = 2(a+b+c) × |1, a, b; 1, b+c+2a, b; 1, a, c+a+2b|</span>
        <strong>R₂ → R₂ – R₁, R₃ → R₃ – R₁:</strong>
        <span class="math">Δ = 2(a+b+c) × |1, a, b; 0, a+b+c, 0; 0, 0, a+b+c|</span>
        <strong>Expand along C₁:</strong>
        <span class="math">Δ = 2(a+b+c) × 1 × [(a+b+c)(a+b+c) – 0]
Δ = 2(a+b+c) × (a+b+c)²
Δ = 2(a+b+c)³</span>
        <strong>Hence proved. ✓</strong>
        <div class="key-note">💡 KEY TRICK: When determinant has sum pattern, always try C₁→C₁+C₂+C₃ first. Then take common factor out. This is the most tested determinant property in UP Board.</div></div>
      </div>
    </div>
  </div>
</div>

<!-- ██████ CALCULUS ██████ -->
<div class="chapter" id="calc">
  <div class="ch-head" onclick="toggle('calc')" style="border-left:5px solid var(--c2)">
    <span class="ch-tag" style="background:var(--c2)">UNIT 3</span><span class="ch-icon">∫</span>
    <div class="ch-info"><div class="ch-name">Calculus — Derivatives, Integrals & Differential Equations</div><div class="ch-sub">Continuity · Differentiability · Applications · Integration · Area · Differential Equations</div></div>
    <span class="ch-mbadge" style="background:var(--c2)">44 Marks</span><span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">
    <div class="qtype" style="color:var(--c2)">∫ Continuity & Differentiability</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C1</span>
        <span class="q-text">If <em>y = (sin x)^(cos x) + (cos x)^(sin x)</em>, find <em>dy/dx</em> using logarithmic differentiation.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c1"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Let y = u + v where u = (sin x)^(cos x) and v = (cos x)^(sin x)<br><br>
        <strong>For u = (sin x)^(cos x):</strong>
        <span class="math">log u = cos x · log(sin x)
Differentiating both sides:
(1/u)(du/dx) = –sin x · log(sin x) + cos x · (cos x/sin x)
du/dx = (sin x)^(cos x) [–sin x · log(sin x) + cos²x/sin x]</span>
        <strong>For v = (cos x)^(sin x):</strong>
        <span class="math">log v = sin x · log(cos x)
(1/v)(dv/dx) = cos x · log(cos x) + sin x · (–sin x/cos x)
dv/dx = (cos x)^(sin x) [cos x · log(cos x) – sin²x/cos x]</span>
        <strong>Therefore:</strong>
        <span class="math">dy/dx = du/dx + dv/dx
= (sinx)^(cosx)[cos²x/sinx – sinx·log(sinx)]
+ (cosx)^(sinx)[cosx·log(cosx) – sin²x/cosx]</span>
        <div class="key-note">💡 Logarithmic differentiation is used when: (i) function has variable in both base and exponent, (ii) product of many functions. Always take log both sides → differentiate.</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C2</span>
        <span class="q-text">Verify Rolle's Theorem for <em>f(x) = x² – 4x + 3</em> on the interval <em>[1, 3]</em>. Also verify Lagrange's Mean Value Theorem.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c2"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>ROLLE'S THEOREM — f(x) = x² – 4x + 3 on [1, 3]</strong><br><br>
        <strong>Conditions:</strong>
        <ul><li>f(x) is continuous on [1, 3] ✓ (polynomial)</li>
        <li>f(x) is differentiable on (1, 3) ✓ (polynomial)</li>
        <li>f(1) = 1 – 4 + 3 = 0; f(3) = 9 – 12 + 3 = 0; f(1) = f(3) ✓</li></ul>
        <strong>Finding c:</strong>
        <span class="math">f'(x) = 2x – 4
f'(c) = 0 ⟹ 2c – 4 = 0 ⟹ c = 2
c = 2 ∈ (1, 3) ✓ — Rolle's Theorem verified.</span>
        <strong>LAGRANGE'S MVT on [1, 4]:</strong>
        <span class="math">f(b) – f(a) / (b – a) = f'(c)
f(1) = 0, f(4) = 16 – 16 + 3 = 3
[3 – 0] / [4 – 1] = 1
f'(c) = 2c – 4 = 1
2c = 5 ⟹ c = 5/2 = 2.5 ∈ (1, 4) ✓</span>
        <div class="key-note">💡 Rolle's Theorem is a special case of LMVT where f(a)=f(b). Always check 3 conditions before finding c.</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C3</span>
        <span class="q-text">Find the intervals in which <em>f(x) = 2x³ – 9x² + 12x + 1</em> is <em>increasing or decreasing</em>. Also find local maxima and minima.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c3"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><span class="math">f(x) = 2x³ – 9x² + 12x + 1
f'(x) = 6x² – 18x + 12 = 6(x² – 3x + 2) = 6(x–1)(x–2)</span>
        <strong>Critical points:</strong> f'(x) = 0 → x = 1, x = 2<br><br>
        <strong>Sign analysis of f'(x):</strong>
        <table>
          <tr><th>Interval</th><th>Test x</th><th>f'(x)</th><th>Nature</th></tr>
          <tr><td>(–∞, 1)</td><td>x = 0</td><td>+ve (6×2 > 0)</td><td>Increasing ↑</td></tr>
          <tr><td>(1, 2)</td><td>x = 1.5</td><td>–ve (6×–0.25)</td><td>Decreasing ↓</td></tr>
          <tr><td>(2, ∞)</td><td>x = 3</td><td>+ve (6×2 > 0)</td><td>Increasing ↑</td></tr>
        </table>
        <strong>Local Maxima at x = 1:</strong>
        <span class="math">f(1) = 2 – 9 + 12 + 1 = 6 → Local maximum value = 6</span>
        <strong>Local Minima at x = 2:</strong>
        <span class="math">f(2) = 16 – 36 + 24 + 1 = 5 → Local minimum value = 5</span>
        <div class="key-note">💡 TRICK: If f'(x) changes from +ve to –ve at x=a → Local Max. If –ve to +ve → Local Min. Increasing: f'(x) > 0; Decreasing: f'(x) < 0.</div></div>
      </div>
    </div>

    <div class="qtype" style="color:var(--c2)">∫ Integration — Most Important!</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C4</span>
        <span class="q-text">Evaluate: <em>∫ x² · sin x dx</em> using <em>Integration by Parts</em>.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c4')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c4"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Using <strong>Integration by Parts:</strong> ∫u·dv = u·v – ∫v·du<br><br>
        Using <strong>ILATE rule</strong>: I–nverse trig, L–og, A–lgebraic, T–rig, E–xponential<br>
        Here: u = x² (Algebraic), dv = sin x dx<br><br>
        <strong>First application:</strong>
        <span class="math">u = x², dv = sin x dx
du = 2x dx, v = –cos x
∫x²sinx dx = –x²cosx + ∫2x·cosx dx  ... (i)</span>
        <strong>Second application (for ∫2x·cosx dx):</strong>
        <span class="math">u = 2x, dv = cosx dx
du = 2dx, v = sinx
∫2x·cosx dx = 2x·sinx – ∫2sinx dx
            = 2x·sinx + 2cosx + C  ... (ii)</span>
        <strong>Substituting (ii) in (i):</strong>
        <span class="math">∫x²sinx dx = –x²cosx + 2x·sinx + 2cosx + C</span>
        <div class="key-note">💡 ILATE Rule for choosing u: Always pick from LEFT of ILATE. Integration by parts is guaranteed every year — practice with x²eˣ, x·logx, x·sinx, x·cosx, eˣ·sinx.</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C5</span>
        <span class="q-text">Evaluate: <em>∫ (x + 2)/√(x² + 2x + 3) dx</em></span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c5')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c5"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Write numerator x + 2 in terms of derivative of denominator's expression:<br>
        <span class="math">d/dx(x² + 2x + 3) = 2x + 2 = 2(x + 1)
So x + 2 = (x + 1) + 1</span>
        <strong>Split the integral:</strong>
        <span class="math">∫(x+2)/√(x²+2x+3) dx = ∫(x+1)/√(x²+2x+3) dx + ∫1/√(x²+2x+3) dx</span>
        <strong>First part — substitution t = x²+2x+3, dt = (2x+2)dx:</strong>
        <span class="math">∫(x+1)/√t · dt/2 = (1/2)∫t^(–1/2) dt = (1/2)·2√t = √(x²+2x+3)</span>
        <strong>Second part — complete the square:</strong>
        <span class="math">x²+2x+3 = (x+1)² + 2
∫1/√((x+1)²+(√2)²) dx = log|x+1+√(x²+2x+3)| + C</span>
        <strong>Final Answer:</strong>
        <span class="math">= √(x²+2x+3) + log|x+1+√(x²+2x+3)| + C</span>
        <div class="key-note">💡 Tip for px+q / √(ax²+bx+c): Write px+q = A·d/dx(ax²+bx+c) + B. Solve for A and B, then integrate separately.</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C6</span>
        <span class="q-text">Evaluate: <em>∫₀^π x·sin x/(1 + cos²x) dx</em> using the property <em>∫₀^a f(x)dx = ∫₀^a f(a–x)dx</em></span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c6')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c6"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Let I = ∫₀^π x·sinx/(1+cos²x) dx  ...(1)<br><br>
        <strong>Apply property: replace x with (π–x):</strong>
        <span class="math">I = ∫₀^π (π–x)·sin(π–x)/(1+cos²(π–x)) dx
  = ∫₀^π (π–x)·sinx/(1+cos²x) dx  ...(2)
[∵ sin(π–x)=sinx, cos(π–x)=–cosx, cos²(π–x)=cos²x]</span>
        <strong>Adding (1) and (2):</strong>
        <span class="math">2I = ∫₀^π π·sinx/(1+cos²x) dx
2I = π ∫₀^π sinx/(1+cos²x) dx</span>
        <strong>Let t = cosx, dt = –sinx dx; limits: x=0→t=1, x=π→t=–1</strong>
        <span class="math">2I = π ∫₁^(–1) –dt/(1+t²) = π ∫₋₁^1 dt/(1+t²)
   = π [tan⁻¹t]₋₁^1 = π[π/4–(–π/4)] = π·π/2 = π²/2</span>
        <strong>∴ I = π²/4</strong>
        <div class="key-note">💡 This KING PROPERTY ∫₀^a f(x)=∫₀^a f(a–x) is asked EVERY YEAR. When you see x·f(sinx) or x·f(cosx) from 0 to π, always use this property!</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C7</span>
        <span class="q-text">Find the <em>area of the region bounded</em> by the parabola <em>y² = 4x</em> and the line <em>x = 3</em>.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c7')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c7"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">The parabola y² = 4x is symmetric about x-axis, vertex at origin (0,0).<br><br>
        <strong>Area using integration:</strong>
        <span class="math">Area = 2∫₀³ y dx  (factor 2 for symmetry about x-axis)
From y² = 4x: y = 2√x (taking positive root)

Area = 2∫₀³ 2√x dx = 4∫₀³ x^(1/2) dx</span>
        <strong>Integrate:</strong>
        <span class="math">= 4 [x^(3/2)/(3/2)]₀³
= 4 × (2/3) [x^(3/2)]₀³
= (8/3) [3^(3/2) – 0]
= (8/3) × 3√3
= 8√3 sq. units</span>
        <strong>∴ Area = 8√3 square units</strong>
        <div class="key-note">💡 ALWAYS draw a rough sketch before solving area problems. For area between curves: ∫(upper curve – lower curve)dx. For parabolas symmetric about x-axis, multiply single-side area by 2.</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C8</span>
        <span class="q-text">Solve the differential equation: <em>(x² + 1)dy + 2xy dx = cot x dx</em>. Or: Solve dy/dx + y·sec²x = tan x·sec²x.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c8')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c8"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>Solve: dy/dx + (2x/(x²+1))y = cot x/(x²+1)</strong><br><br>
        This is a <strong>Linear DE</strong> of the form dy/dx + Py = Q<br><br>
        <strong>Here:</strong> P = 2x/(x²+1), Q = cot x/(x²+1)
        <span class="math">Integrating Factor (IF) = e^∫P dx
∫P dx = ∫2x/(x²+1) dx = log(x²+1)
IF = e^log(x²+1) = (x²+1)</span>
        <strong>Multiply both sides by IF:</strong>
        <span class="math">d/dx [y·(x²+1)] = cot x
Integrate: y(x²+1) = ∫cot x dx = log|sin x| + C</span>
        <strong>Solution:</strong>
        <span class="math">y = [log|sin x| + C] / (x² + 1)</span>
        <div class="key-note">💡 For Linear DE dy/dx + Py = Q: IF = e^(∫P dx), Solution: y·IF = ∫Q·IF dx + C. Always simplify IF using log rules: e^(log f(x)) = f(x).</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c2)">
        <span class="q-num" style="background:var(--c2)">C9</span>
        <span class="q-text">Solve the homogeneous differential equation: <em>x·dy/dx = y + x·tan(y/x)</em></span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(0,207,180,.12);color:#4fffea;border:1px solid rgba(0,207,180,.3)" onclick="showAns(event,'c9')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="c9"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Rewrite: dy/dx = y/x + tan(y/x) — this is homogeneous (degree 0)<br><br>
        <strong>Substitution: y = vx → dy/dx = v + x(dv/dx)</strong>
        <span class="math">v + x(dv/dx) = v + tan v
x(dv/dx) = tan v
dv/tan v = dx/x
cot v · dv = dx/x</span>
        <strong>Integrate both sides:</strong>
        <span class="math">∫cot v dv = ∫dx/x
log|sin v| = log|x| + log C
log|sin v| = log|Cx|
sin v = Cx</span>
        <strong>Substitute back v = y/x:</strong>
        <span class="math">sin(y/x) = Cx</span>
        <strong>This is the general solution.</strong>
        <div class="key-note">💡 For Homogeneous DE: put y=vx (or x=vy), simplify, separate variables, integrate. Always substitute back at the end. Check homogeneous by: f(λx,λy) = λⁿf(x,y).</div></div>
      </div>
    </div>
  </div>
</div>

<!-- ██████ VECTORS & 3D ██████ -->
<div class="chapter" id="vec">
  <div class="ch-head" onclick="toggle('vec')" style="border-left:5px solid var(--c4)">
    <span class="ch-tag" style="background:var(--c4)">UNIT 4</span><span class="ch-icon">→</span>
    <div class="ch-info"><div class="ch-name">Vectors & Three-Dimensional Geometry</div><div class="ch-sub">Scalar & Cross Product · Lines · Planes · Distance · Angle</div></div>
    <span class="ch-mbadge" style="background:var(--c4)">17 Marks</span><span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">
    <div class="qtype" style="color:var(--c4)">→ Vectors</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c4)">
        <span class="q-num" style="background:var(--c4)">V1</span>
        <span class="q-text">If <em>→a = î + 2ĵ + 3k̂</em> and <em>→b = 2î + 4ĵ – 5k̂</em>, find: (i) <em>→a · →b</em> (ii) <em>→a × →b</em> (iii) unit vector perpendicular to both.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(255,169,77,.15);color:#ffc77d;border:1px solid rgba(255,169,77,.35)" onclick="showAns(event,'v1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="v1"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>(i) Dot Product (→a · →b):</strong>
        <span class="math">→a · →b = (1)(2) + (2)(4) + (3)(–5) = 2 + 8 – 15 = –5</span>
        <strong>(ii) Cross Product (→a × →b):</strong>
        <span class="math">→a × →b = |î  ĵ  k̂|
              |1  2  3|
              |2  4  –5|

= î(2×(–5) – 3×4) – ĵ(1×(–5) – 3×2) + k̂(1×4 – 2×2)
= î(–10–12) – ĵ(–5–6) + k̂(4–4)
= –22î + 11ĵ + 0k̂
= –22î + 11ĵ</span>
        <strong>(iii) Unit vector perpendicular to both:</strong>
        <span class="math">|→a × →b| = √((-22)² + 11² + 0²) = √(484 + 121) = √605 = 11√5
n̂ = (–22î + 11ĵ)/(11√5) = (–2î + ĵ)/√5</span>
        <div class="key-note">💡 Cross product gives a vector PERPENDICULAR to both →a and →b. Always use determinant method for cross product. Dot product = 0 means vectors are perpendicular.</div></div>
      </div>
    </div>

    <div class="qtype" style="color:var(--c4)">→ Three-Dimensional Geometry</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c4)">
        <span class="q-num" style="background:var(--c4)">V2</span>
        <span class="q-text">Find the equation of the <em>plane passing through three points</em> A(1,1,0), B(1,2,1) and C(–2,2,–1). Find the distance of point (3,3,1) from this plane.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(255,169,77,.15);color:#ffc77d;border:1px solid rgba(255,169,77,.35)" onclick="showAns(event,'v2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="v2"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>Vectors AB and AC:</strong>
        <span class="math">AB = B – A = (0, 1, 1)
AC = C – A = (–3, 1, –1)</span>
        <strong>Normal vector n = AB × AC:</strong>
        <span class="math">n = |î  ĵ  k̂|
    |0  1  1|
    |–3 1 –1|

= î(1×(–1) – 1×1) – ĵ(0×(–1) – 1×(–3)) + k̂(0×1 – 1×(–3))
= î(–2) – ĵ(3) + k̂(3)
= –2î – 3ĵ + 3k̂</span>
        <strong>Equation of plane through A(1,1,0):</strong>
        <span class="math">–2(x–1) – 3(y–1) + 3(z–0) = 0
–2x + 2 – 3y + 3 + 3z = 0
–2x – 3y + 3z + 5 = 0
or  2x + 3y – 3z – 5 = 0</span>
        <strong>Distance from point (3,3,1):</strong>
        <span class="math">d = |2(3) + 3(3) – 3(1) – 5| / √(4+9+9)
  = |6 + 9 – 3 – 5| / √22
  = |7| / √22 = 7/√22 units</span>
        <div class="key-note">💡 Distance formula from point (x₁,y₁,z₁) to plane ax+by+cz+d=0: d = |ax₁+by₁+cz₁+d|/√(a²+b²+c²)</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c4)">
        <span class="q-num" style="background:var(--c4)">V3</span>
        <span class="q-text">Find the <em>shortest distance between the lines</em>:<br>→r = (î+2ĵ+k̂) + λ(î–ĵ+k̂) and →r = (2î–ĵ–k̂) + μ(2î+ĵ+2k̂)</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(255,169,77,.15);color:#ffc77d;border:1px solid rgba(255,169,77,.35)" onclick="showAns(event,'v3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="v3"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">→a₁ = î+2ĵ+k̂, →b₁ = î–ĵ+k̂, →a₂ = 2î–ĵ–k̂, →b₂ = 2î+ĵ+2k̂<br><br>
        <strong>→a₂ – →a₁ = (2–1)î+(–1–2)ĵ+(–1–1)k̂ = î–3ĵ–2k̂</strong><br><br>
        <strong>→b₁ × →b₂:</strong>
        <span class="math">= |î  ĵ  k̂|
  |1 –1  1|
  |2  1  2|
= î(–2–1) – ĵ(2–2) + k̂(1+2)
= –3î + 0ĵ + 3k̂ = –3î + 3k̂</span>
        <strong>|→b₁ × →b₂| = √(9+0+9) = √18 = 3√2</strong><br><br>
        <strong>Shortest Distance:</strong>
        <span class="math">SD = |(→a₂–→a₁)·(→b₁×→b₂)| / |→b₁×→b₂|
   = |(î–3ĵ–2k̂)·(–3î+0ĵ+3k̂)| / 3√2
   = |(1)(–3)+(–3)(0)+(–2)(3)| / 3√2
   = |–3+0–6| / 3√2 = 9/3√2 = 3/√2 = 3√2/2 units</span>
        <div class="key-note">💡 If SD = 0, lines intersect. If →b₁×→b₂=0, lines are parallel. For parallel lines, use different SD formula: SD = |→b×(→a₂–→a₁)|/|→b|</div></div>
      </div>
    </div>
  </div>
</div>

<!-- ██████ LPP ██████ -->
<div class="chapter" id="lpp">
  <div class="ch-head" onclick="toggle('lpp')" style="border-left:5px solid var(--c5)">
    <span class="ch-tag" style="background:var(--c5)">UNIT 5</span><span class="ch-icon">📊</span>
    <div class="ch-info"><div class="ch-name">Linear Programming Problem (LPP)</div><div class="ch-sub">Formulation · Graphical Solution · Corner Point Method · Optimal Solution</div></div>
    <span class="ch-mbadge" style="background:var(--c5)">6 Marks</span><span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">
    <div class="qtype" style="color:var(--c5)">📊 Linear Programming</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--c5)">
        <span class="q-num" style="background:var(--c5)">L1</span>
        <span class="q-text">Solve the LPP graphically: <em>Maximise Z = 3x + 4y</em> subject to constraints: <em>x + y ≤ 4, x ≥ 0, y ≥ 0, x + 2y ≤ 6</em>.</span>
        <div class="q-right"><span class="q-marks">6M</span><button class="ans-btn" style="background:rgba(77,184,255,.12);color:#90d8ff;border:1px solid rgba(77,184,255,.3)" onclick="showAns(event,'l1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="l1"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body"><strong>Constraints:</strong> x + y ≤ 4, x + 2y ≤ 6, x ≥ 0, y ≥ 0<br><br>
        <strong>Finding Corner Points of Feasible Region:</strong><br>
        — Line 1: x + y = 4 → passes through (0,4) and (4,0)<br>
        — Line 2: x + 2y = 6 → passes through (0,3) and (6,0)<br><br>
        <strong>Intersection of Line 1 & Line 2:</strong>
        <span class="math">x + y = 4   ...(1)
x + 2y = 6  ...(2)
Subtract (1) from (2): y = 2, x = 2
Intersection point: (2, 2)</span>
        <strong>Corner Points of Feasible Region:</strong>
        <table>
          <tr><th>Corner Point</th><th>Z = 3x + 4y</th></tr>
          <tr><td>O(0, 0)</td><td>Z = 0</td></tr>
          <tr><td>A(4, 0)</td><td>Z = 12</td></tr>
          <tr><td>B(2, 2)</td><td>Z = 6 + 8 = <strong>14</strong></td></tr>
          <tr><td>C(0, 3)</td><td>Z = 0 + 12 = 12</td></tr>
        </table>
        <strong>Maximum Z = 14 at point (2, 2)</strong>
        <div class="key-note">💡 CORNER POINT METHOD: Always evaluate objective function at ALL corner points of feasible region. Maximum/minimum is always at a corner point. Shade feasible region carefully in your answer.</div></div>
      </div>
    </div>
  </div>
</div>

<!-- ██████ PROBABILITY ██████ -->
<div class="chapter" id="prob">
  <div class="ch-head" onclick="toggle('prob')" style="border-left:5px solid var(--gold)">
    <span class="ch-tag" style="background:var(--gold)">UNIT 6</span><span class="ch-icon">🎲</span>
    <div class="ch-info"><div class="ch-name">Probability</div><div class="ch-sub">Conditional Probability · Bayes' Theorem · Random Variable · Binomial Distribution</div></div>
    <span class="ch-mbadge" style="background:var(--gold)">10 Marks</span><span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">
    <div class="qtype" style="color:var(--gold)">🎲 Probability Theorems</div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--gold)">
        <span class="q-num" style="background:var(--gold)">P1</span>
        <span class="q-text">A bag contains 5 red and 3 blue balls. Two balls are drawn at random. Find probability that (i) both are red (ii) one red, one blue. Also state <em>Bayes' theorem</em>.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(240,192,64,.12);color:#f0d060;border:1px solid rgba(240,192,64,.3)" onclick="showAns(event,'p1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="p1"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Total balls = 5 red + 3 blue = 8 balls<br>
        Total ways to choose 2 balls = C(8,2) = 8!/(2!×6!) = 28<br><br>
        <strong>(i) Both red:</strong>
        <span class="math">Favourable = C(5,2) = 10
P(both red) = 10/28 = 5/14</span>
        <strong>(ii) One red, one blue:</strong>
        <span class="math">Favourable = C(5,1) × C(3,1) = 5 × 3 = 15
P(one red, one blue) = 15/28</span>
        <strong>Bayes' Theorem Statement:</strong><br>
        If E₁, E₂, ..., Eₙ are mutually exclusive and exhaustive events, and A is any event, then:
        <span class="math">P(Eᵢ|A) = P(Eᵢ)·P(A|Eᵢ) / ∑P(Eⱼ)·P(A|Eⱼ)</span>
        <div class="key-note">💡 C(n,r) = n! / [r!(n–r)!]. For Bayes' Theorem: first find P(A|Eᵢ) for each Eᵢ, then apply formula. This is "reverse conditional probability."</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--gold)">
        <span class="q-num" style="background:var(--gold)">P2</span>
        <span class="q-text">Three boxes have coins: Box I: 3 gold 4 silver, Box II: 5 gold 3 silver, Box III: 2 gold 6 silver. A box is selected at random and one coin is drawn. It is gold. Using <em>Bayes' theorem</em>, find the probability it came from Box II.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(240,192,64,.12);color:#f0d060;border:1px solid rgba(240,192,64,.3)" onclick="showAns(event,'p2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="p2"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">Let E₁, E₂, E₃ = events of choosing Box I, II, III respectively<br>
        Let A = event of drawing a gold coin<br><br>
        <strong>Prior probabilities (boxes equally likely):</strong>
        <span class="math">P(E₁) = P(E₂) = P(E₃) = 1/3</span>
        <strong>Conditional probabilities:</strong>
        <span class="math">P(A|E₁) = 3/7  (3 gold out of 7)
P(A|E₂) = 5/8  (5 gold out of 8)
P(A|E₃) = 2/8 = 1/4  (2 gold out of 8)</span>
        <strong>Total probability P(A):</strong>
        <span class="math">P(A) = P(E₁)·P(A|E₁) + P(E₂)·P(A|E₂) + P(E₃)·P(A|E₃)
     = (1/3)(3/7) + (1/3)(5/8) + (1/3)(1/4)
     = (1/3)[3/7 + 5/8 + 1/4]
     = (1/3)[24/56 + 35/56 + 14/56]
     = (1/3)(73/56) = 73/168</span>
        <strong>By Bayes' Theorem:</strong>
        <span class="math">P(E₂|A) = P(E₂)·P(A|E₂) / P(A)
         = (1/3)(5/8) / (73/168)
         = (5/24) × (168/73)
         = 35/73</span>
        <strong>∴ P(Box II | Gold coin) = 35/73</strong>
        <div class="key-note">💡 Bayes' theorem TEMPLATE: Write P(Eᵢ) and P(A|Eᵢ) in a table. Find P(A) using total probability. Then apply Bayes. This appears EVERY year in UP Board!</div></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" style="--qc:var(--gold)">
        <span class="q-num" style="background:var(--gold)">P3</span>
        <span class="q-text">In a <em>Binomial Distribution</em>, n = 10 and p = 1/3. Find the mean, variance, and standard deviation. Also find P(X = 3).</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="ans-btn" style="background:rgba(240,192,64,.12);color:#f0d060;border:1px solid rgba(240,192,64,.3)" onclick="showAns(event,'p3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="p3"><div class="ans-lbl">✅ Model Answer</div>
        <div class="ans-body">For Binomial Distribution B(n, p): n = 10, p = 1/3, q = 1 – p = 2/3<br><br>
        <strong>Mean (μ):</strong>
        <span class="math">μ = np = 10 × 1/3 = 10/3</span>
        <strong>Variance (σ²):</strong>
        <span class="math">σ² = npq = 10 × (1/3) × (2/3) = 20/9</span>
        <strong>Standard Deviation (σ):</strong>
        <span class="math">σ = √(npq) = √(20/9) = 2√5/3</span>
        <strong>P(X = 3):</strong>
        <span class="math">P(X=r) = C(n,r) × pʳ × q^(n–r)
P(X=3) = C(10,3) × (1/3)³ × (2/3)⁷
        = 120 × (1/27) × (128/2187)
        = 120 × 128 / (27 × 2187)
        = 15360 / 59049</span>
        <div class="key-note">💡 Binomial Distribution: P(X=r) = C(n,r)pʳq^(n–r), Mean=np, Variance=npq, SD=√(npq). Always verify: p+q=1. This formula is given in exam but you must know how to apply it!</div></div>
      </div>
    </div>
  </div>
</div>

</main>
</div>
</div><!-- page-study -->

<!-- PAGE PAPER -->
<div id="page-paper" class="page">
<div class="paper-wrapper">
  <div class="print-bar">
    <span>📄 UP Board Class 12 Mathematics — Model Question Paper 2026 | 100 Marks</span>
    <button class="print-btn" onclick="window.print()">🖨️ Print / Save as PDF</button>
  </div>
  <div class="paper-sheet">
  <div class="paper-inner">

    <div class="paper-top">
      <div class="p-board">Uttar Pradesh Madhyamik Shiksha Parishad (UPMSP), Prayagraj</div>
      <div class="p-exam">Annual Intermediate Examination 2025–26</div>
      <div class="p-sub-head">Class XII (Intermediate) — Science Stream</div>
      <div style="margin:10px 0"><span class="p-subject-strip">गणित / MATHEMATICS</span></div>
      <div class="p-meta"><span>Time: 3 Hours 15 Minutes</span><span>Maximum Marks: 100</span></div>
      <div class="p-meta" style="font-weight:400;font-size:11px;color:#666"><span>Roll No.: ________________________</span><span>Set: A</span></div>
      <div class="p-note">This paper consists of two sections. Read all instructions carefully before attempting questions.</div>
    </div>

    <div class="instruct">
      <p><strong>सामान्य निर्देश / General Instructions:</strong></p>
      <p>1. This question paper has <strong>two sections: Section A (Multiple Choice — 20 Marks)</strong> and <strong>Section B (Descriptive — 80 Marks)</strong>.</p>
      <p>2. <strong>Section A</strong>: All 20 MCQs are compulsory. Each carries 1 mark. Darken the correct circle on OMR sheet. No negative marking.</p>
      <p>3. <strong>Section B</strong>: Attempt all questions. Internal choice provided where indicated. Maintain stepwise working — marks are given for method.</p>
      <p>4. Use of calculator, log tables, and mobile devices is <strong>strictly prohibited</strong>.</p>
      <p>5. Draw neat diagrams wherever required (especially for LPP and 3D Geometry).</p>
      <p>6. <strong>Marks Distribution:</strong> Relations & Functions: 10M | Algebra: 13M | Calculus: 44M | Vectors & 3D: 17M | LPP: 6M | Probability: 10M</p>
    </div>

    <!-- SECTION A — MCQ -->
    <div class="p-sec"><span class="p-sec-name">खण्ड-A | SECTION — A &nbsp; Multiple Choice Questions (MCQ)</span><span class="p-sec-marks">[ 20 Marks — OMR Sheet ]</span></div>
    <p style="font-size:12px;color:#666;margin-bottom:14px;font-style:italic">Each question carries 1 mark. Choose the most appropriate answer.</p>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.1</span><span class="pq-t">The relation R = {(a, b) : a ≤ b} on set A = {1, 2, 3} is:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) Reflexive only</div><div class="mcq-opt">(b) Symmetric only</div><div class="mcq-opt">(c) Reflexive & Transitive</div><div class="mcq-opt">(d) Equivalence relation</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.2</span><span class="pq-t">The principal value of cos⁻¹(–1/2) is:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) π/3</div><div class="mcq-opt">(b) –π/3</div><div class="mcq-opt">(c) 2π/3</div><div class="mcq-opt">(d) π</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.3</span><span class="pq-t">If A is a square matrix of order 3 and |A| = 5, then |2A| equals:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) 10</div><div class="mcq-opt">(b) 25</div><div class="mcq-opt">(c) 40</div><div class="mcq-opt">(d) 200</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.4</span><span class="pq-t">If y = log(sin x), then dy/dx is:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) cot x</div><div class="mcq-opt">(b) –cot x</div><div class="mcq-opt">(c) tan x</div><div class="mcq-opt">(d) –tan x</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.5</span><span class="pq-t">∫eˣ(sin x + cos x) dx is equal to:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) eˣ sin x + C</div><div class="mcq-opt">(b) eˣ cos x + C</div><div class="mcq-opt">(c) eˣ(sin x + cos x) + C</div><div class="mcq-opt">(d) 2eˣ sin x + C</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.6</span><span class="pq-t">The order and degree of the differential equation (d²y/dx²)³ + (dy/dx)² + sin(dy/dx) + 1 = 0 are:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) 2, 3</div><div class="mcq-opt">(b) 2, not defined</div><div class="mcq-opt">(c) 1, 3</div><div class="mcq-opt">(d) 3, 2</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.7</span><span class="pq-t">If →a and →b are such that |→a × →b| = →a · →b, then the angle between →a and →b is:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) 0</div><div class="mcq-opt">(b) π/4</div><div class="mcq-opt">(c) π/2</div><div class="mcq-opt">(d) π</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.8</span><span class="pq-t">The direction cosines of the line x/2 = y/3 = z/6 are:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) 2/7, 3/7, 6/7</div><div class="mcq-opt">(b) 2, 3, 6</div><div class="mcq-opt">(c) 1/2, 1/3, 1/6</div><div class="mcq-opt">(d) None</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.9</span><span class="pq-t">In an LPP, the optimal value of the objective function is always attained at:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) Origin</div><div class="mcq-opt">(b) Any interior point</div><div class="mcq-opt">(c) Corner point of feasible region</div><div class="mcq-opt">(d) Midpoint of a side</div></div>
    </div>
    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.10</span><span class="pq-t">If P(A) = 1/3, P(B) = 1/4 and A, B are independent events, then P(A∩B) equals:</span><span class="pq-m">1M</span></div>
      <div class="mcq-opts"><div class="mcq-opt">(a) 1/12</div><div class="mcq-opt">(b) 7/12</div><div class="mcq-opt">(c) 1/2</div><div class="mcq-opt">(d) 1/7</div></div>
    </div>
    <p style="font-size:11px;color:#666;margin:10px 0 6px;font-style:italic">Q.11–Q.20: Fill in the blanks / True-False / One word answers (10 × 1 = 10 Marks)</p>
    <div class="pq"><div class="pq-row"><span class="pq-n">Q.11</span><span class="pq-t">tan⁻¹(1) + tan⁻¹(2) + tan⁻¹(3) = _______</span><span class="pq-m">1M</span></div></div>
    <div class="pq"><div class="pq-row"><span class="pq-n">Q.12</span><span class="pq-t">For a square matrix A, A + Aᵀ is always a _______ matrix.</span><span class="pq-m">1M</span></div></div>
    <div class="pq"><div class="pq-row"><span class="pq-n">Q.13</span><span class="pq-t">The function f(x) = |x| is not differentiable at x = _______.</span><span class="pq-m">1M</span></div></div>
    <div class="pq"><div class="pq-row"><span class="pq-n">Q.14</span><span class="pq-t">∫₀^(π/2) sin²x dx = _______</span><span class="pq-m">1M</span></div></div>
    <div class="pq"><div class="pq-row"><span class="pq-n">Q.15</span><span class="pq-t">The equation of the plane parallel to XY-plane at distance 5 from it is: z = _______.</span><span class="pq-m">1M</span></div></div>
    <div class="pq"><div class="pq-row"><span class="pq-n">Q.16–20</span><span class="pq-t">One-line answers: (i) State ILATE rule for integration by parts. (ii) What is the variance of Binomial Distribution B(n,p)? (iii) What is the integrating factor of dy/dx + y/x = x²? (iv) Name the property used when ∫₀^a f(x)dx = ∫₀^a f(a–x)dx. (v) When are two events A and B called independent?</span><span class="pq-m">1M each</span></div></div>

    <!-- SECTION B -->
    <div class="p-sec"><span class="p-sec-name">खण्ड-B | SECTION — B &nbsp; Descriptive Questions</span><span class="p-sec-marks">[ 80 Marks ]</span></div>

    <!-- UNIT 1 -->
    <div class="p-sec" style="background:#6c63ff;margin-top:14px"><span class="p-sec-name">Unit 1 — Relations & Functions + Inverse Trigonometry</span><span class="p-sec-marks">[ 10 Marks ]</span></div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.21</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Prove that the relation R on ℤ defined by R = {(a,b) : 5 divides (a – b)} is an equivalence relation. Find the equivalence class of 2.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Show that f : ℝ → ℝ defined by f(x) = (4x + 3)/(6x – 4), x ≠ 2/3 is one-one and onto. Find f⁻¹.</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.22</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Prove: 2tan⁻¹(1/2) + tan⁻¹(1/7) = tan⁻¹(31/17). Also simplify: tan⁻¹[2cos(2sin⁻¹(1/2))].</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Write the principal value of: (i) sin⁻¹(sin 3π/5) (ii) cos⁻¹(cos 7π/6) (iii) tan⁻¹(tan 3π/4). Prove: sin⁻¹(3/5) + cos⁻¹(12/13) = cos⁻¹(33/65).</span></div>
      </div>
    </div>

    <!-- UNIT 2 -->
    <div class="p-sec" style="background:#ff6b9d;margin-top:14px"><span class="p-sec-name">Unit 2 — Matrices & Determinants</span><span class="p-sec-marks">[ 13 Marks ]</span></div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.23</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Using elementary row operations (Gauss-Jordan), find A⁻¹ if A = [[1,2,3],[2,5,7],[–2,–4,–5]]. Hence solve: x+2y+3z=14, 2x+5y+7z=33, –2x–4y–5z=–21.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Using properties of determinants, prove: |1+a, 1, 1; 1, 1+b, 1; 1, 1, 1+c| = abc(1 + 1/a + 1/b + 1/c) = abc + bc + ca + ab.</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.24</span><span class="pq-t">Answer in 2–3 lines each: <strong>[2 × 4 = 8 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>If A = [[3,1],[–1,2]], show that A² – 5A + 7I = O. Hence find A⁻¹.</span></div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Find the area of the triangle with vertices (2,7), (1,1), (10,8) using determinants.</span></div>
      </div>
    </div>

    <!-- UNIT 3 — CALCULUS -->
    <div class="p-sec" style="background:#00cfb4;color:#000;margin-top:14px"><span class="p-sec-name" style="color:#000">Unit 3 — Calculus (Most Important!)</span><span class="p-sec-marks" style="color:#003">[ 44 Marks ]</span></div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.25</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>If x = a(cos θ + θ sin θ) and y = a(sin θ – θ cos θ), find dy/dx and d²y/dx².</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Differentiate: y = (sin x)ˣ + sin⁻¹√x. Find dy/dx using logarithmic differentiation.</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.26</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Find intervals of increase/decrease for f(x) = sin x + cos x, x ∈ [0, 2π]. Find local maxima and minima.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>A closed cylindrical can is to hold 1 litre of oil. Find the dimensions that minimize the total surface area. (Given: 1 litre = 1000 cm³)</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.27</span><span class="pq-t">Evaluate any <strong>two</strong> of the following integrals: <strong>[2 × 5 = 10 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>∫ x² / (x⁴ + x² + 1) dx &nbsp;&nbsp; [Hint: divide num and denom by x²]</span></div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>∫ (x² + 1)(x² + 4) / [(x² + 3)(x² – 5)] dx &nbsp;&nbsp; [Partial fractions]</span></div>
        <div class="pq-sub"><span class="pq-sn">(c)</span><span>∫₀^(π/2) log(tan x) dx &nbsp;&nbsp; [King property]</span></div>
        <div class="pq-sub"><span class="pq-sn">(d)</span><span>∫ x · tan⁻¹x dx &nbsp;&nbsp; [Integration by parts]</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.28</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Find the area of the region bounded by the parabola y = x² and the line y = x + 2 using integration.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Find the area of the ellipse x²/a² + y²/b² = 1 using integration. Hence find the area of x²/9 + y²/4 = 1.</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.29</span><span class="pq-t">Solve any <strong>two</strong> differential equations: <strong>[2 × 5 = 10 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>(x² – y²) dx + 2xy dy = 0 &nbsp;&nbsp; [Homogeneous DE]</span></div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>dy/dx + y/x = log x &nbsp;&nbsp; [Linear DE — find IF]</span></div>
        <div class="pq-sub"><span class="pq-sn">(c)</span><span>(1 + x²)dy/dx + 2xy = cos²x &nbsp;&nbsp; [Linear DE]</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.30</span><span class="pq-t">Short answer questions: <strong>[2 × 2 = 4 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Verify Rolle's Theorem for f(x) = x(x–2)e^(–x) on [0, 2].</span></div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Find the approximate value of √(26) using differentials. (Hint: use f(x)=√x at x=25)</span></div>
      </div>
    </div>

    <!-- UNIT 4 -->
    <div class="p-sec" style="background:#ffa94d;color:#000;margin-top:14px"><span class="p-sec-name" style="color:#000">Unit 4 — Vectors & 3D Geometry</span><span class="p-sec-marks" style="color:#000">[ 17 Marks ]</span></div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.31</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>Find the equation of the line passing through A(1,2,3) and B(4,5,7). Also find the shortest distance from point (1,0,2) to this line.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Find the equation of the plane passing through (–1,3,2) and perpendicular to planes x+2y+3z=5 and 3x+3y+z=0. Find angle between the two given planes.</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.32</span><span class="pq-t">Answer in 2–3 steps each: <strong>[4 × 3 = 12 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>If →a = 3î–ĵ+2k̂, →b = 2î+ĵ–k̂, →c = î+2ĵ–k̂, find →a×(→b×→c) and verify the identity.</span></div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Find the foot of the perpendicular from point (1,2,3) to the plane 2x–y+3z=1. Also find the length of the perpendicular.</span></div>
        <div class="pq-sub"><span class="pq-sn">(c)</span><span>Show that the four points A(0,–1,0), B(2,1,–1), C(1,1,1), D(3,3,0) are coplanar.</span></div>
        <div class="pq-sub"><span class="pq-sn">(d)</span><span>Find the shortest distance between lines →r=(2î–ĵ+k̂)+λ(î+ĵ+k̂) and →r=(3î–5ĵ+2k̂)+μ(3î+ĵ+k̂).</span></div>
      </div>
    </div>

    <!-- UNIT 5 LPP -->
    <div class="p-sec" style="background:#4db8ff;color:#000;margin-top:14px"><span class="p-sec-name" style="color:#000">Unit 5 — Linear Programming Problem</span><span class="p-sec-marks" style="color:#000">[ 6 Marks ]</span></div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.33</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[6 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>A manufacturer makes two products, each requiring machine time and labour. Product A: 2 hrs machine, 1 hr labour; Product B: 1 hr machine, 2 hrs labour. Available: 12 machine hrs, 12 labour hrs. Profit A = ₹5, B = ₹4. Find the number of each product to maximise profit. Solve graphically.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Solve graphically: Minimise Z = 3x + 5y, subject to: x + y ≥ 4, x + 3y ≥ 6, x ≥ 0, y ≥ 0. Also find the point at which minimum occurs.</span></div>
      </div>
    </div>

    <!-- UNIT 6 PROBABILITY -->
    <div class="p-sec" style="background:#f0c040;color:#000;margin-top:14px"><span class="p-sec-name" style="color:#000">Unit 6 — Probability</span><span class="p-sec-marks" style="color:#000">[ 10 Marks ]</span></div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.34</span><span class="pq-t">Answer <strong>any one</strong>: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>There are three urns: Urn I has 2W 3B, Urn II has 3W 2B, Urn III has 4W 1B. One urn is selected at random and one ball is drawn. It turns out to be white. Using Bayes' Theorem, find the probability that it came from Urn III.</span></div>
        <div class="or-div">— OR —</div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>In a binomial distribution, mean = 6 and variance = 2. Find the distribution, and also find P(X ≥ 1) and P(X = 6).</span></div>
      </div>
    </div>

    <div class="pq">
      <div class="pq-row"><span class="pq-n">Q.35</span><span class="pq-t">Answer in 2–3 lines: <strong>[5 Marks]</strong></span></div>
      <div class="pq-subs">
        <div class="pq-sub"><span class="pq-sn">(a)</span><span>State and prove the theorem of total probability. [2M]</span></div>
        <div class="pq-sub"><span class="pq-sn">(b)</span><span>Two cards are drawn without replacement from a pack of 52 cards. Find the probability that both are kings. [1M]</span></div>
        <div class="pq-sub"><span class="pq-sn">(c)</span><span>For a random variable X with distribution: P(X=0)=1/3, P(X=1)=1/2, P(X=2)=1/6. Find E(X) and Var(X). [2M]</span></div>
      </div>
    </div>

    <div class="p-footer">
      <div>Examiner's Signature:<span class="blank-l"></span></div>
      <div style="text-align:center"><div style="font-size:16px;font-weight:900;font-family:'Playfair Display',serif">✦ All the Best ✦</div><div style="margin-top:5px;font-size:11px">upmsp.edu.in</div></div>
      <div style="text-align:right">Total Marks: 100<br><br>Invigilator:<span class="blank-l" style="width:120px"></span></div>
    </div>

  </div>
  </div>
</div>
</div><!-- page-paper -->

<!-- FLOAT PANEL -->
<div class="float-panel" id="floatP">
  <span class="fp-lbl">Revised</span>
  <span class="fp-num" id="fp-num">0</span>
  <span class="fp-tot">of 100 Qs</span>
  <button class="fp-btn" onclick="window.scrollTo({top:0,behavior:'smooth'})">⬆ Top</button>
</div>

<script>
document.querySelectorAll('.tab-btn').forEach(btn=>{
  btn.addEventListener('click',function(){
    const t=this.dataset.tab;
    document.querySelectorAll('.tab-btn').forEach(b=>b.classList.remove('active'));
    this.classList.add('active');
    document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
    document.getElementById('page-'+t).classList.add('active');
    window.scrollTo({top:0,behavior:'smooth'});
    document.getElementById('floatP').style.display=t==='study'?'flex':'none';
  });
});
function toggle(id){document.getElementById(id).classList.toggle('open');}
function openCh(id){const el=document.getElementById(id);el.classList.add('open');setTimeout(()=>el.scrollIntoView({behavior:'smooth',block:'start'}),120);}
let done=0;
function showAns(e,id){
  e.stopPropagation();
  const box=document.getElementById(id);
  if(!box)return;
  const wasShown=box.classList.contains('show');
  box.classList.toggle('show');
  e.target.textContent=box.classList.contains('show')?'▼ Hide':'▶ Answer';
  if(!wasShown){
    done=Math.min(done+1,100);
    document.getElementById('fp-num').textContent=done;
    document.getElementById('prog-val').textContent=done+'/100';
    document.getElementById('prog-fill').style.width=(done)+'%';
  }
}
function searchQ(val){
  const q=val.toLowerCase();
  document.querySelectorAll('.q-wrap').forEach(w=>{
    const t=w.querySelector('.q-text').textContent.toLowerCase();
    const show=!q||t.includes(q);
    w.style.display=show?'block':'none';
    if(show&&q)w.closest('.chapter').classList.add('open');
  });
}
document.querySelectorAll('.chapter').forEach((c,i)=>{c.style.animationDelay=(i*60)+'ms';});
</script>
</body>
</html>
