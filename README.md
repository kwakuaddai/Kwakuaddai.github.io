<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Yo | Mining Technical Services, Ghana</title>
<meta name="description" content="Portfolio of Yo, technical services and mining operations, Ayanfuri, Ghana.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@600;700&family=Barlow:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --stone:#e8ebe7; --paper:#f6f7f4; --shale:#1d2a2f; --slate:#46585e;
  --hivis:#e5c100; --line:#c9d0cb;
  --head:"Barlow Condensed","Arial Narrow",sans-serif;
  --body:"Barlow",system-ui,sans-serif;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font:18px/1.6 var(--body);color:var(--shale);background:var(--paper)}
a{color:inherit}
:focus-visible{outline:3px solid var(--hivis);outline-offset:3px}
.wrap{max-width:960px;margin:0 auto;padding:0 24px}

header.top{position:sticky;top:0;background:var(--paper);border-bottom:1px solid var(--line);z-index:5}
header.top .wrap{display:flex;justify-content:space-between;align-items:center;height:56px}
.mark{font:700 24px var(--head);text-decoration:none;letter-spacing:.02em}
nav a{margin-left:20px;text-decoration:none;font-weight:500;font-size:16px}
nav a:hover{text-decoration:underline;text-decoration-color:var(--hivis);text-decoration-thickness:3px;text-underline-offset:5px}

.hero{background:var(--shale);color:var(--paper);position:relative;overflow:hidden;padding:88px 0 150px}
.hero h1{font:700 clamp(56px,11vw,120px)/.92 var(--head);margin:0 0 20px;letter-spacing:.01em}
.hero p{max-width:34ch;font-size:clamp(20px,3vw,26px);line-height:1.35;margin:0 0 28px;color:#d5dcd8}
.btn{display:inline-block;background:var(--hivis);color:var(--shale);font-weight:500;padding:12px 22px;text-decoration:none;border-radius:2px}
.btn:hover{background:#f2d21a}
.btn.ghost{background:none;color:var(--paper);border:1px solid #6b7c82;margin-left:10px}
.btn.ghost:hover{border-color:var(--paper)}
.pit{position:absolute;left:0;right:0;bottom:0;height:120px;background:var(--paper);
  clip-path:polygon(0 100%,0 62%,12% 62%,12% 46%,24% 46%,24% 30%,36% 30%,36% 14%,50% 14%,50% 14%,64% 14%,64% 30%,76% 30%,76% 46%,88% 46%,88% 62%,100% 62%,100% 100%)}
.pit::after{content:"";position:absolute;inset:0;background:var(--hivis);
  clip-path:polygon(36% 14%,64% 14%,64% 17%,36% 17%)}

section{padding:64px 0}
section.alt{background:var(--stone)}
h2{font:700 clamp(36px,6vw,52px)/1 var(--head);margin:0 0 28px}
h3{font:600 26px/1.1 var(--head);margin:0 0 6px}
.about{display:grid;gap:24px;grid-template-columns:1fr}
.about p{margin:0;max-width:62ch}
.facts{list-style:none;margin:0;padding:0;border-left:4px solid var(--hivis);padding-left:18px}
.facts li{padding:4px 0}
.facts b{font-weight:500;color:var(--slate)}

.skills{display:grid;gap:28px;grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}
.skills p{margin:0;color:var(--slate)}

.timeline{border-left:2px solid var(--shale);margin:0;padding:0 0 0 24px;list-style:none}
.timeline li{position:relative;padding-bottom:32px}
.timeline li::before{content:"";position:absolute;left:-32px;top:8px;width:14px;height:14px;background:var(--hivis);border:2px solid var(--shale);border-radius:50%}
.timeline .when{color:var(--slate);font-size:16px}
.timeline p{margin:6px 0 0;max-width:60ch}

.projects{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(270px,1fr))}
.proj{background:var(--paper);border-top:4px solid var(--shale);padding:20px 22px}
.proj p{margin:0;color:var(--slate)}
.proj span{display:block;margin-top:12px;font-size:15px;color:var(--slate)}

.contact{background:var(--shale);color:var(--paper)}
.contact p{max-width:46ch;color:#d5dcd8}
.contact a.mail{font:700 clamp(26px,5vw,44px) var(--head);color:var(--hivis)}
footer{padding:20px 0;font-size:15px;color:var(--slate)}

@media (min-width:760px){.about{grid-template-columns:1.6fr 1fr}}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
@media (max-width:560px){nav a{margin-left:12px}.btn.ghost{margin:10px 10px 0 0}}
</style>
</head>
<body>

<header class="top">
  <div class="wrap">
    <a class="mark" href="#top">Yo</a>
    <nav aria-label="Main">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<main id="top">
  <div class="hero">
    <div class="wrap">
      <h1>Yo</h1>
      <p>Technical services and mining operations, on site in Ghana.</p>
      <a class="btn" href="#projects">See my work</a>
      <a class="btn ghost" href="#contact">Get in touch</a>
      <a class="btn ghost" href="cv.pdf" download="Yo-CV.pdf">Download CV</a>
    </div>
    <div class="pit" aria-hidden="true"></div>
  </div>

  <section id="about">
    <div class="wrap about">
      <div>
        <h2>About</h2>
        <p>I work in the Technical Service Department at Rocksure International Limited, on the Perseus Mine site in Ayanfuri. My days are shift handovers, hazard reports, fleet planning calculations and equipment productivity analysis. I have also worked with the blasting crew, stemming holes and loading emulsion, so I know how the numbers on paper turn into work on the bench.</p>
      </div>
      <ul class="facts">
        <li><b>Based in</b><br>Ayanfuri, Ghana</li>
        <li><b>Department</b><br>Technical Service</li>
        <li><b>Site</b><br>Perseus Mine</li>
        <li><b>Also codes in</b><br>Python</li>
      </ul>
    </div>
  </section>

  <section class="alt">
    <div class="wrap">
      <h2>What I do</h2>
      <div class="skills">
        <div><h3>Safety reporting</h3><p>Spotting hazards, writing them up clearly and logging them in the site hazard report book.</p></div>
        <div><h3>Fleet planning</h3><p>Working out how many trucks and loaders a shift needs to hit its targets.</p></div>
        <div><h3>Productivity analysis</h3><p>Turning shift data into figures that show how equipment is performing.</p></div>
        <div><h3>Shift handover</h3><p>Passing on equipment status, open issues and risks so the next crew starts informed.</p></div>
      </div>
    </div>
  </section>

  <section id="experience">
    <div class="wrap">
      <h2>Experience</h2>
      <ol class="timeline">
        <li>
          <h3>National Service, Technical Service Department</h3>
          <div class="when">Rocksure International Limited, Perseus Mine, Ayanfuri</div>
          <p>Supporting day-to-day technical work: handover notes, hazard reports, fleet calculations and equipment productivity analysis.</p>
        </li>
        <li>
          <h3>Blasting crew support</h3>
          <div class="when">Perseus Mine, Ayanfuri</div>
          <p>Assisted the blasting crew with stemming and loading emulsion.</p>
        </li>
      </ol>
    </div>
  </section>

  <section id="projects" class="alt">
    <div class="wrap">
      <h2>Projects</h2>
      <div class="projects">
        <div class="proj">
          <h3>Hazard reporting tracker</h3>
          <p>An Excel tracker built alongside the site hazard report book to log and follow up reported hazards.</p>
          <span>Excel</span>
        </div>
        <div class="proj">
          <h3>Fleet planning calculations</h3>
          <p>Calculations that match truck and loader numbers to shift targets and haul conditions.</p>
          <span>Excel, mine planning</span>
        </div>
        <div class="proj">
          <h3>Equipment productivity analysis</h3>
          <p>Shift-by-shift analysis of how equipment is performing against plan.</p>
          <span>Data analysis</span>
        </div>
        <div class="proj">
          <h3>Automated trading bot</h3>
          <p>A personal Python project that trades automatically from a set of rules.</p>
          <span>Python</span>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="wrap">
      <h2>Contact</h2>
      <p>Open to technical service and mining operations roles. Send me a message.</p>
      <a class="mail" href="mailto:your.email@example.com">your.email@example.com</a>
      <p><a class="btn" href="cv.pdf" download="Yo-CV.pdf">Download CV</a></p>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">© <span id="yr">2026</span> Yo. Ayanfuri, Ghana.</div>
</footer>

<script>document.getElementById("yr").textContent=new Date().getFullYear();</script>
</body>
</html>
