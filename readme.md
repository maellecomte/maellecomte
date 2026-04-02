
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Sora:wght@300;400;600;700&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
body{background:transparent}
.wrap{font-family:'Sora',sans-serif;max-width:780px;margin:0 auto;padding:2rem 1.5rem}
.badge-row{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:1.5rem}
.badge{display:inline-flex;align-items:center;gap:6px;font-family:'Space Mono',monospace;font-size:11px;padding:4px 12px;border-radius:999px;border:1.5px solid;font-weight:700;letter-spacing:.03em}
.b-green{background:#EAF3DE;border-color:#639922;color:#3B6D11}
.b-blue{background:#E6F1FB;border-color:#378ADD;color:#185FA5}
.b-purple{background:#EEEDFE;border-color:#7F77DD;color:#534AB7}
.b-coral{background:#FAECE7;border-color:#D85A30;color:#993C1D}
.b-teal{background:#E1F5EE;border-color:#1D9E75;color:#0F6E56}
.b-amber{background:#FAEEDA;border-color:#BA7517;color:#854F0B}
.hero{margin-bottom:2rem}
.hero-name{font-size:2.8rem;font-weight:700;line-height:1.1;letter-spacing:-.03em;color:var(--color-text-primary);margin-bottom:.4rem}
.hero-name span{background:linear-gradient(90deg,#7F77DD,#1D9E75);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.hero-sub{font-size:1.05rem;color:var(--color-text-secondary);font-weight:300;line-height:1.6;max-width:560px;margin-bottom:1.2rem}
.divider{height:2px;background:linear-gradient(90deg,#7F77DD22,#1D9E7566,#378ADD33,transparent);border-radius:2px;margin:1.5rem 0}
.section-label{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:.2em;text-transform:uppercase;color:var(--color-text-tertiary);margin-bottom:.75rem;display:flex;align-items:center;gap:8px}
.section-label::after{content:'';flex:1;height:1px;background:var(--color-border-tertiary)}
.stack-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(100px,1fr));gap:8px;margin-bottom:1.5rem}
.stack-card{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:8px;padding:10px 12px;display:flex;flex-direction:column;align-items:flex-start;gap:4px}
.stack-card .s-icon{font-size:18px;line-height:1}
.stack-card .s-name{font-family:'Space Mono',monospace;font-size:11px;color:var(--color-text-primary);font-weight:700}
.stack-card .s-cat{font-size:10px;color:var(--color-text-tertiary)}
.stats-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:1.5rem}
.stat-card{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:10px;padding:14px;text-align:center}
.stat-n{font-size:1.6rem;font-weight:700;color:var(--color-text-primary);font-family:'Space Mono',monospace;line-height:1}
.stat-l{font-size:11px;color:var(--color-text-tertiary);margin-top:4px;letter-spacing:.05em}
.streak{display:inline-block;padding:2px 8px;border-radius:4px;font-size:10px;font-weight:700;font-family:'Space Mono',monospace;background:#EEEDFE;color:#534AB7;margin-top:6px}
.contact-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:.5rem}
.cta{display:inline-flex;align-items:center;gap:6px;padding:8px 18px;border-radius:8px;font-family:'Space Mono',monospace;font-size:12px;font-weight:700;text-decoration:none;border:1.5px solid;cursor:pointer;transition:transform .15s}
.cta:hover{transform:translateY(-1px)}
.cta-primary{background:#7F77DD;border-color:#7F77DD;color:#fff}
.cta-ghost{background:transparent;border-color:var(--color-border-secondary);color:var(--color-text-primary)}
.typing-cursor{display:inline-block;width:3px;height:1.1em;background:var(--color-text-primary);vertical-align:text-bottom;animation:blink .9s step-end infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.tag-line{font-family:'Space Mono',monospace;font-size:13px;color:var(--color-text-secondary);margin-bottom:1.2rem;min-height:1.4em}
.activity-bar{display:flex;gap:3px;align-items:flex-end;height:48px;margin-bottom:1.5rem}
.ab{border-radius:3px 3px 0 0;width:16px;flex-shrink:0;opacity:.85}
.lang-row{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:1.5rem}
.lang-pill{padding:4px 12px;border-radius:999px;font-family:'Space Mono',monospace;font-size:11px;font-weight:700}
</style>
<div class="wrap">

  <div class="badge-row">
    <span class="badge b-green">● open to work</span>
    <span class="badge b-blue">Full-Stack</span>
    <span class="badge b-purple">Data / AI</span>
    <span class="badge b-teal">DevOps · Infra</span>
    <span class="badge b-coral">Paris, FR</span>
  </div>

  <div class="hero">
    <div class="hero-name">Hey, I'm <span>Mael Lecomte</span> 👋</div>
    <div class="tag-line" id="tagline"><span id="typed"></span><span class="typing-cursor"></span></div>
    <div class="hero-sub">
      Je construis des systèmes qui tournent vite, pensent fort et tombent rarement.
      De la ligne de commande au modèle de prod, j'aime avoir les mains dans tout.
    </div>
  </div>

  <div class="divider"></div>

  <div class="section-label">stack</div>
  <div class="stack-grid">
    <div class="stack-card"><div class="s-icon">⚡</div><div class="s-name">Python</div><div class="s-cat">Backend / ML</div></div>
    <div class="stack-card"><div class="s-icon">🌐</div><div class="s-name">TypeScript</div><div class="s-cat">Frontend / API</div></div>
    <div class="stack-card"><div class="s-icon">⚛️</div><div class="s-name">React</div><div class="s-cat">UI / DX</div></div>
    <div class="stack-card"><div class="s-icon">🐳</div><div class="s-name">Docker</div><div class="s-cat">Containers</div></div>
    <div class="stack-card"><div class="s-icon">☸️</div><div class="s-name">K8s</div><div class="s-cat">Orchestration</div></div>
    <div class="stack-card"><div class="s-icon">🤖</div><div class="s-name">PyTorch</div><div class="s-cat">Deep Learning</div></div>
    <div class="stack-card"><div class="s-icon">📦</div><div class="s-name">PostgreSQL</div><div class="s-cat">Data Store</div></div>
    <div class="stack-card"><div class="s-icon">🔁</div><div class="s-name">CI/CD</div><div class="s-cat">GH Actions</div></div>
  </div>

  <div class="divider"></div>

  <div class="section-label">github stats</div>
  <div style="background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:12px;padding:16px 20px;margin-bottom:1.5rem">
    <div style="font-family:'Space Mono',monospace;font-size:10px;color:var(--color-text-tertiary);margin-bottom:12px;letter-spacing:.1em">// contribution activity — last 12 months</div>
    <div class="activity-bar" id="actbar"></div>
    <div class="lang-row" id="langrow"></div>
    <div style="font-size:11px;color:var(--color-text-tertiary);font-family:'Space Mono',monospace;margin-top:4px">
      ↑ ces stats sont générées dynamiquement via <span style="color:#7F77DD">github-readme-stats</span>
    </div>
  </div>

  <div class="stats-row">
    <div class="stat-card">
      <div class="stat-n" id="cnt-repos">0</div>
      <div class="stat-l">repos publics</div>
    </div>
    <div class="stat-card">
      <div class="stat-n" id="cnt-commits">0</div>
      <div class="stat-l">commits / an</div>
      <div class="streak">🔥 streak en cours</div>
    </div>
    <div class="stat-card">
      <div class="stat-n" id="cnt-stars">0</div>
      <div class="stat-l">stars reçues</div>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section-label">contact</div>
  <div class="contact-row">
    <button class="cta cta-primary" onclick="sendPrompt('Génère le code markdown complet du README pour GitHub de Mael Lecomte')">
      📄 Voir le code Markdown ↗
    </button>
    <button class="cta cta-ghost">✉️ mail@maellecomte.dev</button>
    <button class="cta cta-ghost">💼 LinkedIn</button>
  </div>

</div>
<script>
const phrases=["I ship full-stack products.","I train ML models in prod.","I automate everything I touch.","I speak Python, TS & YAML fluently.","I break things — then fix them better."];
let pi=0,ci=0,del=false;
const el=document.getElementById('typed');
function type(){
  const p=phrases[pi];
  if(!del){el.textContent=p.slice(0,ci+1);ci++;if(ci===p.length){del=true;setTimeout(type,1800);return;}}
  else{el.textContent=p.slice(0,ci-1);ci--;if(ci===0){del=false;pi=(pi+1)%phrases.length;}}
  setTimeout(type,del?40:70);
}
type();

const bars=document.getElementById('actbar');
const heights=[12,18,10,28,22,36,40,32,44,38,48,30,42,20,34,46,28,50,44,36,30,24,38,42,46,32,28,22,18,14];
const colors=['#7F77DD','#1D9E75','#378ADD','#7F77DD','#1D9E75','#378ADD','#D85A30','#7F77DD','#1D9E75','#378ADD','#7F77DD','#D85A30','#1D9E75','#378ADD','#7F77DD','#1D9E75','#378ADD','#7F77DD','#D85A30','#1D9E75','#378ADD','#7F77DD','#1D9E75','#D85A30','#7F77DD','#1D9E75','#378ADD','#7F77DD','#1D9E75','#D85A30'];
heights.forEach((h,i)=>{const b=document.createElement('div');b.className='ab';b.style.height=h+'px';b.style.background=colors[i]+'cc';bars.appendChild(b);});

const langs=[{name:'Python',bg:'#EAF3DE',c:'#3B6D11'},{name:'TypeScript',bg:'#EEEDFE',c:'#534AB7'},{name:'Go',bg:'#E1F5EE',c:'#0F6E56'},{name:'SQL',bg:'#E6F1FB',c:'#185FA5'},{name:'YAML',bg:'#FAEEDA',c:'#854F0B'},{name:'Bash',bg:'#FAECE7',c:'#993C1D'}];
const lr=document.getElementById('langrow');
langs.forEach(l=>{const p=document.createElement('span');p.className='lang-pill';p.style.background=l.bg;p.style.color=l.c;p.textContent=l.name;lr.appendChild(p);});

function animCount(id,target,dur){
  const el=document.getElementById(id);let start=null;
  function step(ts){if(!start)start=ts;const prog=Math.min((ts-start)/dur,1);el.textContent=Math.round(prog*target);if(prog<1)requestAnimationFrame(step);}
  requestAnimationFrame(step);
}
setTimeout(()=>{animCount('cnt-repos',42,1200);animCount('cnt-commits',847,1400);animCount('cnt-stars',213,1100);},400);
</script>
