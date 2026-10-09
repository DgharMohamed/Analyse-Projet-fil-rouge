---
marp: true
theme: default
paginate: true
size: 16:9
style: |
  :root {
    --bg: #07111f;
    --panel: #0e1f35;
    --panel-2: #102942;
    --text: #f8fafc;
    --muted: #b8c7da;
    --blue: #38bdf8;
    --blue-soft: #93c5fd;
    --line: #24496e;
  }

  section {
    background:
      linear-gradient(135deg, rgba(56, 189, 248, 0.16), transparent 34%),
      linear-gradient(315deg, rgba(147, 197, 253, 0.12), transparent 34%),
      var(--bg);
    color: var(--text);
    font-family: "Segoe UI", Arial, sans-serif;
    padding: 56px 68px;
    letter-spacing: 0;
  }

  h1 {
    color: var(--blue);
    font-size: 54px;
    margin: 0 0 24px;
  }

  h2 {
    color: var(--blue-soft);
    font-size: 34px;
    margin: 0 0 22px;
  }

  p, li {
    font-size: 29px;
    line-height: 1.35;
  }

  ul, ol {
    margin: 0;
    padding-left: 34px;
  }

  strong {
    color: var(--blue-soft);
  }

  code, pre {
    background: #06101c;
    color: #e2e8f0;
    border-radius: 8px;
  }

  pre {
    padding: 22px;
    border: 1px solid var(--line);
  }

  section.lead {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
  }

  section.lead h1 {
    font-size: 76px;
    text-transform: uppercase;
  }

  section.section-title {
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
  }

  section.section-title h1 {
    font-size: 72px;
  }

  .subtitle {
    color: var(--muted);
    font-size: 31px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 28px;
  }

  .grid.two {
    grid-template-columns: repeat(2, 1fr);
  }

  .card {
    background: var(--panel);
    border: 1px solid var(--line);
    border-radius: 8px;
    padding: 24px;
    min-height: 120px;
  }

  .card h3 {
    color: var(--blue-soft);
    font-size: 27px;
    margin: 0 0 10px;
  }

  .card p {
    color: var(--muted);
    font-size: 23px;
    margin: 0;
  }

  .plan {
    display: grid;
    grid-template-columns: 90px 1fr;
    gap: 16px 24px;
    align-items: center;
    margin-top: 26px;
  }

  .num {
    color: var(--blue);
    font-size: 32px;
    font-weight: 700;
  }

  .item {
    background: var(--panel);
    border-left: 5px solid var(--blue);
    border-radius: 8px;
    padding: 15px 22px;
    font-size: 29px;
  }

  .flow {
    display: flex;
    align-items: center;
    gap: 14px;
    margin-top: 34px;
  }

  .step {
    flex: 1;
    background: var(--panel-2);
    border: 1px solid var(--line);
    border-radius: 8px;
    padding: 18px;
    text-align: center;
    font-size: 24px;
  }

  .arrow {
    color: var(--blue);
    font-size: 30px;
    font-weight: 700;
  }

  footer {
    color: var(--muted);
  }
---

<!-- _class: lead -->

# VEILLETECH

<p class="subtitle">Veille Technologie</p>

---

# Plan

<div class="plan">
  <div class="num">01</div><div class="item">Veille technologique</div>
  <div class="num">02</div><div class="item">Solution alternative — AI Agent</div>
  <div class="num">03</div><div class="item">Claude Code gratuitement</div>
  <div class="num">04</div><div class="item">Skills</div>
  <div class="num">05</div><div class="item">MCP</div>
</div>

---

<!-- _class: section-title -->

# Veille technologique

---

# Définition

## Veille technologique

<div class="grid">
  <div class="card"><h3>Suivre</h3></div>
  <div class="card"><h3>Découvrir</h3></div>
  <div class="card"><h3>Progresser</h3></div>
</div>

---

# Utiliser la veille technologique

<div class="grid">
  <div class="card"><h3>Rechercher</h3></div>
  <div class="card"><h3>Suivre</h3></div>
  <div class="card"><h3>Comparer</h3></div>
  <div class="card"><h3>Tester</h3></div>
  <div class="card"><h3>Appliquer</h3></div>
  <div class="card"><h3>Exemple : PHP</h3><p>Versions · Tests · Projets</p></div>
</div>

---

<!-- _class: section-title -->

# AI Agent

---

# What is an AI agent?

<div class="flow">
  <div class="step">Goal/Task</div>
  <div class="arrow">→</div>
  <div class="step">AI Model</div>
  <div class="arrow">→</div>
  <div class="step">Application Software<br>(goal-driven-software)</div>
  <div class="arrow">→</div>
  <div class="step">Execute/complete</div>
</div>

<p class="subtitle">Fully based on AI Model</p>

---

# AI Agent Use Cases:

<div class="grid">
  <div class="card"><h3>Coding</h3></div>
  <div class="card"><h3>Research</h3></div>
  <div class="card"><h3>Everyday tasks</h3></div>
</div>

---

# AI agent Core components

<div class="grid">
  <div class="card"><h3>The Brain (LLM)</h3></div>
  <div class="card"><h3>The Tools</h3></div>
  <div class="card"><h3>The Memory</h3></div>
</div>

---

<!-- _class: section-title -->

# Top AI Agents

---

# Chosen AI Agent for Testing

<div class="card">
  <h3>Kiro</h3>
</div>

---

<!-- _class: section-title -->

# Claude Code gratuitement

---

<!-- _class: section-title -->

# skills

---

# Skills : c’est quoi ?

Une méthode spécialisée pour guider l’Agent dans une tâche précise.

<div class="grid two">
  <div class="card"><h3>PROBLÈME</h3><p>« Corrige ce bug. »<br>L’Agent doit savoir comment travailler.</p></div>
  <div class="card"><h3>SKILL</h3><p>Instructions + règles pour une tâche précise.<br>Ex. Debug</p></div>
  <div class="card"><h3>RÉSULTAT</h3><p>L’Agent suit une méthode claire et structurée.</p></div>
  <div class="card"><h3>Skills • AI Agent</h3></div>
</div>

---

# FONCTIONNEMENT

## Comment une Skill est utilisée ?

Exemple : « J’ai un bug dans le login. »

<div class="flow">
  <div class="step">1<br>Task<br>Le User donne la tâche</div>
  <div class="arrow">→</div>
  <div class="step">2<br>Comprendre<br>L’Agent identifie le besoin</div>
  <div class="arrow">→</div>
  <div class="step">3<br>Choisir<br>Debug Skill correspond</div>
  <div class="arrow">→</div>
  <div class="step">4<br>Lire<br>SKILL.md → instructions</div>
  <div class="arrow">→</div>
  <div class="step">5<br>Agir<br>Analyse → Fix → Test</div>
</div>

---

# CONSTRUCTION

## Comment construire une Skill ?

Une Skill claire = objectif + entrées + processus + règles + résultat

<div class="grid two">
  <div class="card">
    <h3>STRUCTURE</h3>
    <pre>.agent/
skills/
└── debug/
    └── SKILL.md</pre>
  </div>
  <div class="card">
    <h3>CONTENU</h3>
    <p>OBJECTIF<br>ENTRÉES<br>PROCESSUS<br>RÈGLES<br>RÉSULTAT</p>
  </div>
</div>

---

# Exemple Debug

<div class="flow">
  <div class="step">Analyser</div>
  <div class="arrow">→</div>
  <div class="step">Identifier</div>
  <div class="arrow">→</div>
  <div class="step">Corriger</div>
  <div class="arrow">→</div>
  <div class="step">Tester</div>
</div>

<p class="subtitle">Skills • AI Agent</p>

---

<!-- _class: section-title -->

# MCP

---

<!-- _class: section-title -->

# Claude Code gratuitement

---

<!-- _class: lead -->

# Thank you for

# VEILLE TECH

<p class="subtitle">Your Attention</p>
