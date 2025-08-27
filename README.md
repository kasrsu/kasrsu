# <div align="center">

<!-- Inline SVG: GLITCH BANNER (paste as‑is in README) -->

<svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="KASR — Data Science • AI • Graphs">
  <defs>
    <filter id="glitch">
      <feTurbulence type="fractalNoise" baseFrequency="0.012" numOctaves="2" seed="8" result="noise"/>
      <feDisplacementMap in="SourceGraphic" in2="noise" scale="6" xChannelSelector="R" yChannelSelector="G"/>
    </filter>
    <linearGradient id="grad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="50%" stop-color="#7C4DFF"/>
      <stop offset="100%" stop-color="#FF3D7F"/>
    </linearGradient>
    <style>
      @keyframes rgbSplit {
        0% { transform: translate(0,0); filter: url(#glitch); opacity: 1; }
        20% { transform: translate(-2px,1px); }
        40% { transform: translate(2px,-1px); }
        60% { transform: translate(-1px,1px); }
        80% { transform: translate(1px,-1px); }
        100% { transform: translate(0,0); }
      }
      @keyframes scan {
        0% { opacity: 0.1; }
        50% { opacity: 0.35; }
        100% { opacity: 0.1; }
      }
      .title { font: 900 88px/1.05 "Inter", system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, "Noto Sans", "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji"; paint-order: stroke; stroke: #000; stroke-width: 8; }
      .stroke { fill: none; stroke: url(#grad); stroke-width: 4; stroke-linecap: round; stroke-dasharray: 12 12; animation: scan 3.2s infinite ease-in-out; }
      .layer { animation: rgbSplit 2.4s infinite steps(1); }
      .r { fill: #ff004d; mix-blend-mode: screen; }
      .g { fill: #00e5ff; mix-blend-mode: screen; }
      .b { fill: #7c4dff; mix-blend-mode: screen; }
      .main { fill: url(#grad); filter: url(#glitch); }
      .tag  { font: 600 20px/1.4 "Inter", system-ui; letter-spacing: 2px; text-transform: uppercase; fill: #b3b3b3; }
    </style>
  </defs>

  <rect width="100%" height="100%" fill="#0a0a0a" rx="20"/>

  <!-- scan line accent -->

  <path class="stroke" d="M40 150 H1160"/>

  <!-- GLITCHED LAYERS -->

  <g transform="translate(40,55)">
    <text x="0" y="0" class="title r layer">KASR</text>
    <text x="0" y="0" class="title g layer">KASR</text>
    <text x="0" y="0" class="title b layer">KASR</text>
    <text x="0" y="0" class="title main">KASR</text>
  </g>

<text x="40" y="165" class="tag">Data Science • AI • Graphs • ZAARA Labs</text> </svg>

</div>

<p align="center">
  <b>Ship fast. Break patterns. Measure impact.</b><br/>I build AI/DS products that don’t just look smart — they hit metrics.
</p>

<p align="center">
  <a href="#featured">Featured</a> •
  <a href="#stack">Tech Stack</a> •
  <a href="#status">Now</a> •
  <a href="#stats">Stats</a> •
  <a href="#contact">Contact</a>
</p>

---

## <span id="featured">🚀 Featured

> Zero fluff. Real work. If it doesn’t demo in 60s, it doesn’t ship.

* **MENTO — AI Education Mentor (Neo4j + LLM)**
  Graph-powered guidance for Sri Lankan students after A/Ls. Personalized paths, module maps, tech‑news recommendations.

  * Backend: Neo4j, FastAPI, local LLM (Mistral/CodeLlama via Ollama)
  * Frontend: React Native (mobile), chat-first UX
  * Extras: News clustering + progress-aware recs
  * Demo: `link-here`

* **AI → Human Converter (ZAARA Labs)**
  Turns AI‑sounding text into clean human voice & style. Your content, not robotic filler.

  * Use cases: Upwork proposals, landing copy, emails
  * Demo: `link-here`

* **Tech Updates Engine**
  Pulls tech news (Dev.to, daily.dev, Google News), clusters to student modules, and recommends what actually matters.

  * Demo: `link-here`

* **NLP Converter Tool**
  Classifies & style‑transforms text with guardrails.

  * Demo: `link-here`

---

## <span id="stack">🧰 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" />
  <img src="https://img.shields.io/badge/Neo4j-018BFF?logo=neo4j&logoColor=fff" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=fff" />
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=fff" />
  <img src="https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=fff" />
  <img src="https://img.shields.io/badge/Mistral_AI-FF5C83?logo=mistral&logoColor=fff" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff" />
</p>

---

## <span id="status">📡 Now — what I’m actively pushing

* Shipping **MENTO** rec engine to prod (progress-aware + clustering)
* Hardening local LLM stack (8GB RAM budget)
* Standing up servers for real‑time fetch + APIs
* Road to **professor**: open‑source course materials & demos

---

## <span id="stats">📊 Stats (because receipts matter)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KASR-username&show_icons=true&hide_title=true" alt="GitHub stats" />
  <img src="https://streak-stats.demolab.com?user=KASR-username" alt="Streak" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=KASR-username" alt="Activity Graph" />
</p>

> Replace `KASR-username` with your actual GitHub handle.

---

## <span id="contact">🤝 Let’s build

* Email: `your-email@domain`
* X / Twitter: `@yourhandle`
* Upwork / Fiverr: `links-here`

---

### Bonus: Inline animated name tag (SVG)

Paste this anywhere in the README (or save as `assets/kasr-name.svg` and `<img src="assets/kasr-name.svg" width="420">`).

```html
<svg width="420" height="100" viewBox="0 0 420 100" xmlns="http://www.w3.org/2000/svg" aria-label="KASR tag">
  <defs>
    <linearGradient id="g" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="50%" stop-color="#7C4DFF"/>
      <stop offset="100%" stop-color="#FF3D7F"/>
    </linearGradient>
    <style>
      @keyframes dash { to { stroke-dashoffset: -1000; } }
      @keyframes pop { 0%{ transform: scale(1); } 50%{ transform: scale(1.04);} 100%{ transform: scale(1);} }
      text { font: 800 52px/1.1 Inter, system-ui; letter-spacing: 2px; }
      .outline { fill: none; stroke: url(#g); stroke-width: 3; stroke-dasharray: 14 10; animation: dash 6s linear infinite; }
      .fill { fill: url(#g); }
      .wrap { transform-origin: 50% 50%; animation: pop 2.8s ease-in-out infinite; }
    </style>
  </defs>
  <rect width="100%" height="100%" rx="16" fill="#0a0a0a"/>
  <g class="wrap">
    <text x="24" y="64" class="fill">KASR</text>
    <rect x="12" y="18" width="396" height="64" rx="14" class="outline"/>
  </g>
</svg>
```

---

### Pro tip: Make the README your repo homepage

* Put this as `README.md` in your profile repo named **`<your-username>`** (exact match).
* Keep the SVGs inline (best) or save them in `/assets` and reference with `<img src="assets/..svg">`.
* No scripts, no external CSS — everything here renders on GitHub as‑is.

---

### Replace‑me checklist

* [ ] Swap `KASR-username` with your GitHub handle
* [ ] Add demo links for each project
* [ ] Add contact links
* [ ] Commit and pin repos to your profile

> If you want different colorways or effects (scanlines, CRT, matrix rain, neon tube), ping me — I’ll drop alternate SVGs.
