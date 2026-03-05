---
theme: default
title: "The Invisible Partner"
info: |
  ## The Invisible Partner
  How AI Is Becoming Every Small Business's Best Hire
  Antonio Alejo Combarro — Cofounder, Pragmatic Labs AI
highlighter: shiki
lineNumbers: false
transition: fade
mdc: true
fonts:
  sans: "DM Sans"
  weights: "300,400,500,600,700,800,900"
  provider: google
---
<!-- SLIDES: lean text · big visuals · image placeholders -->

<!-- ─── SLIDE 1 — TITLE ─────────────────────────────────── -->
<div class="s1">
  <div class="ai-words-bg" aria-hidden="true">
    <span style="top:6%;left:3%;font-size:0.8rem">neural</span>
    <span style="top:14%;left:18%;font-size:1.3rem">LLM</span>
    <span style="top:4%;left:38%;font-size:0.7rem">embedding</span>
    <span style="top:9%;left:58%;font-size:1.1rem">transformer</span>
    <span style="top:3%;left:80%;font-size:0.9rem">inference</span>
    <span style="top:22%;left:7%;font-size:1rem">prompt</span>
    <span style="top:28%;left:88%;font-size:0.75rem">agent</span>
    <span style="top:35%;left:2%;font-size:0.65rem">token</span>
    <span style="top:38%;left:92%;font-size:1.1rem">rag</span>
    <span style="top:45%;left:12%;font-size:0.8rem">context</span>
    <span style="top:52%;left:82%;font-size:0.9rem">vector</span>
    <span style="top:58%;left:4%;font-size:1rem">attention</span>
    <span style="top:64%;left:72%;font-size:0.7rem">encoder</span>
    <span style="top:68%;left:16%;font-size:0.75rem">decoder</span>
    <span style="top:74%;left:86%;font-size:0.8rem">weights</span>
    <span style="top:78%;left:6%;font-size:0.65rem">gradient</span>
    <span style="top:82%;left:62%;font-size:1rem">pipeline</span>
    <span style="top:86%;left:30%;font-size:0.8rem">latent</span>
    <span style="top:90%;left:78%;font-size:0.9rem">fine-tune</span>
    <span style="top:88%;left:8%;font-size:0.7rem">epoch</span>
    <span style="top:18%;left:48%;font-size:0.7rem">multimodal</span>
    <span style="top:72%;left:44%;font-size:0.65rem">semantic</span>
    <span style="top:50%;left:56%;font-size:0.75rem">retrieval</span>
    <span style="top:42%;left:34%;font-size:0.8rem">generative</span>
    <span style="top:60%;left:26%;font-size:0.65rem">api</span>
    <span style="top:30%;left:72%;font-size:0.7rem">dataset</span>
  </div>
  <div class="title-content">
    <div class="s1-label">THE INVISIBLE PARTNER</div>
    <h1 class="s1-h1">How <span class="s1-blue">AI</span> Is Becoming<br>Every Small Business's<br><span class="s1-blue">Best Hire</span></h1>
    <div class="s1-rule"></div>
    <div class="s1-bio">
      <span class="s1-name">Antonio Alejo Combarro</span>
      <span class="s1-sep">·</span>
      <span class="s1-role">Cofounder, Pragmatic Labs AI</span>
      <span class="s1-sep">|</span>
      <span class="s1-role">AI Team Lead @ Spinview</span>
      <span class="s1-sep">·</span>
      <span class="s1-date">March 2026</span>
    </div>
  </div>
</div>

<style>
.s1 { position: relative; height: 100%; display: flex; align-items: center; justify-content: center; background: #080b0f; overflow: hidden; }
.ai-words-bg { position: absolute; inset: 0; pointer-events: none; }
.ai-words-bg span { position: absolute; font-family: 'JetBrains Mono', 'DM Mono', monospace; font-weight: 600; color: #1752e8; opacity: 0.07; text-transform: lowercase; letter-spacing: 0.04em; user-select: none; white-space: nowrap; }
.title-content { position: relative; z-index: 10; text-align: center; padding: 0 80px; }
.s1-label { font-family: 'DM Sans', sans-serif; font-size: 0.95rem; letter-spacing: 0.38em; color: #4a82f0; font-weight: 700; margin-bottom: 32px; text-transform: uppercase; }
.s1-h1 { font-family: 'Space Grotesk', sans-serif; font-size: 5.2rem; font-weight: 700; line-height: 1.08; color: #dce4ed; margin: 0 0 36px; letter-spacing: -0.02em; }
.s1-blue { color: #1752e8; }
.s1-rule { width: 48px; height: 3px; background: #1752e8; margin: 0 auto 32px; border-radius: 2px; }
.s1-bio { font-size: 0.95rem; color: #5a6a7a; display: flex; gap: 10px; align-items: center; justify-content: center; flex-wrap: wrap; }
.s1-name { color: #dce4ed; font-weight: 700; }
.s1-sep { color: #1752e8; }
.s1-role { color: #7a8ea0; }
.s1-date { color: #3a4a5a; }
</style>

<!--
**Speaker notes (≤30 sec)**

"I'm Antonio. Day job: I lead an AI team at Spinview. Side mission: Pragmatic Labs AI, where we help small businesses put AI to work — not the Silicon Valley hype version, the actually-useful version."

"I promise this won't be a talk where someone tells you AI is going to replace all your jobs. Well. Not all of them." [beat]

"Today: where AI actually is in France and Europe right now, why most businesses aren't capturing the benefit, and what a genuinely different approach looks like. Let's go."

**Timing: ~0:25**
-->

---
transition: fade
---

<div class="slide-2">
  <div class="hero-number">26%</div>
  <div class="sub-text">
    of French TPE/PME use AI — up from <strong>13%</strong> in 2024 <sup class="source">[8]</sup>
  </div>
  <div class="catch-line"><strong>But there's a catch.</strong></div>
</div>

<style>
.slide-2 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; gap: 0; }
@keyframes breathe { 0%, 100% { text-shadow: 0 0 80px rgba(23,82,232,0.3), 0 0 160px rgba(23,82,232,0.1); } 50% { text-shadow: 0 0 120px rgba(23,82,232,0.7), 0 0 260px rgba(23,82,232,0.3), 0 0 400px rgba(23,82,232,0.12); } }
.hero-number { font-family: 'Space Grotesk', sans-serif; font-size: 17rem; font-weight: 700; color: #1752e8; line-height: 1; letter-spacing: -0.04em; animation: breathe 3.5s ease-in-out infinite; }
.sub-text { font-size: 1.55rem; color: #9baebf; text-align: center; margin-top: 4px; font-weight: 400; }
.sub-text strong { color: #dce4ed; font-weight: 800; }
.catch-line { margin-top: 32px; font-size: 1.4rem; color: #5a6a7a; }
</style>

<!--
**Speaker notes (~1:00)**

"Let me start with one number. France Num surveyed over 11,000 small and medium businesses last year. 26% say they use AI. A year earlier it was 13%. It *doubled*."

"Which, depending on how you define 'use AI'... might just mean someone's nephew showed them ChatGPT at Christmas." [beat, smile]

"But either way — real momentum. And I want you to hold onto that 26% — because I'm going to come back to it with a twist."

**Transition:** "First, the bigger picture."

**Timing: ~1:00**
-->

---
transition: fade
---

<div class="slide-3">
  <h2 class="s3-title">The Global AI Race</h2>
  <div class="s3-blocks">
    <div class="s3-block">
      <div class="s3-flag"><span class="fi fi-us"></span></div>
      <div class="s3-amount s3-lead">$109B</div>
      <div class="s3-desc">private AI investment</div>
    </div>
    <div class="s3-divider"></div>
    <div class="s3-block s3-block-center">
      <div class="s3-flag"><span class="fi fi-eu"></span></div>
      <div class="s3-amount s3-low">$8B</div>
      <div class="s3-desc s3-positive">+30% AI talent per capita</div>
    </div>
    <div class="s3-divider"></div>
    <div class="s3-block">
      <div class="s3-flag"><span class="fi fi-cn"></span></div>
      <div class="s3-amount s3-lead">$9.3B</div>
      <div class="s3-desc">private AI investment</div>
    </div>
  </div>
  <div class="s3-contrast">
    Europe has the people. The money went elsewhere.<span class="source">[4][6]</span>
  </div>
  <div class="footnote">* Stanford AI Index 2025 · Euronews Jan 2026 · 2024–2025 data</div>
</div>

<style>
.slide-3 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 0 60px; gap: 0; }
.s3-title { font-family: 'DM Sans', sans-serif; font-size: 1rem; font-weight: 700; letter-spacing: 0.28em; text-transform: uppercase; color: #3a4a5a; margin-bottom: 56px; }
.s3-blocks { display: flex; align-items: center; justify-content: center; width: 100%; gap: 0; }
.s3-block { flex: 1; text-align: center; padding: 0 40px; }
.s3-block-center { border-left: 1px solid #1c2535; border-right: 1px solid #1c2535; }
.s3-divider { width: 1px; height: 160px; background: #1c2535; flex-shrink: 0; }
.s3-flag { font-size: 2.8rem; margin-bottom: 20px; }
.s3-amount { font-family: 'Space Grotesk', sans-serif; font-size: clamp(3.8rem, 6vw, 6rem); font-weight: 700; line-height: 1; letter-spacing: -0.02em; white-space: nowrap; }
.s3-lead { color: #dce4ed; }
.s3-low { color: #f73356; text-shadow: 0 0 40px rgba(247,51,86,0.2); }
.s3-desc { font-size: 0.92rem; color: #5a6a7a; margin-top: 14px; font-weight: 500; white-space: nowrap; }
.s3-positive { color: #dce4ed !important; font-weight: 700; }
.s3-contrast { margin-top: 52px; font-size: 1.4rem; color: #5a6a7a; text-align: center; font-weight: 500; }
</style>

<!--
**Speaker notes (~2:00) — OPTIONAL SLIDE — cut if running to time**

"Here's the global picture. And I want to be honest — the numbers are stark."

"$109 billion of private AI investment went to the US last year. Europe attracted $8 billion. The US produced 40 notable AI foundation models. Europe produced 3."

"The compute gap is even wider. The US has 17 times Europe's AI supercomputing capacity. And 72% of the European cloud market runs on US infrastructure."

"But here's what nobody talks about: Europe has 30% more AI professionals per capita than the US. Three out of four European AI PhD graduates who go to the US stay there for at least five years. The talent is here. It's leaving — or it's not being activated."

**Transition:** "So are businesses in Europe actually keeping up?"

**→ If skipping this slide:** say verbally during Slide 2: "The US attracted $109 billion in AI investment last year. Europe: $8 billion. But Europe has 30% more AI professionals per capita. The gap isn't talent. It's adoption." Then move to Slide 4.

**Timing: ~2:00**
-->

---
transition: fade
---

<div class="slide-4">
  <h2 class="s4-title">Small Business AI Adoption — 2025</h2>
  <div class="s4-rows">
    <div class="s4-row">
      <div class="s4-label"><span class="fi fi-us"></span> <span>US</span></div>
      <div class="s4-track">
        <div class="s4-fill s4-us"></div>
      </div>
      <div class="s4-num">58%</div>
    </div>
    <div class="s4-row">
      <div class="s4-label"><span class="fi fi-dk"></span> <span>Denmark</span></div>
      <div class="s4-track">
        <div class="s4-fill s4-dk"></div>
      </div>
      <div class="s4-num">42%</div>
    </div>
    <div class="s4-row">
      <div class="s4-label"><span class="fi fi-gb"></span> <span>UK</span></div>
      <div class="s4-track">
        <div class="s4-fill s4-uk"></div>
      </div>
      <div class="s4-num">35%</div>
    </div>
    <div class="s4-row">
      <div class="s4-label"><span class="fi fi-fr"></span> <span>France</span></div>
      <div class="s4-track">
        <div class="s4-fill s4-fr"></div>
      </div>
      <div class="s4-num">26%</div>
    </div>
    <div class="s4-row">
      <div class="s4-label"><span class="fi fi-eu"></span> <span>EU</span></div>
      <div class="s4-track">
        <div class="s4-fill s4-eu"></div>
      </div>
      <div class="s4-num s4-num-dim">17%</div>
    </div>
  </div>
  <div class="s4-tagline">Using AI. But using ≠ integrated.</div>
  <div class="footnote">* 2024–2025 data; [12][5][11][8]</div>
</div>

<style>
.slide-4 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 24px 96px 40px; }
.s4-title { font-size: 1rem; font-weight: 700; letter-spacing: 0.28em; text-transform: uppercase; color: #3a4a5a; margin-bottom: 52px; }
.s4-rows { display: flex; flex-direction: column; gap: 20px; width: 100%; }
.s4-row { display: grid; grid-template-columns: 200px 1fr 100px; align-items: center; gap: 20px; }
.s4-label { font-size: 2.2rem; font-weight: 600; color: #9baebf; display: flex; align-items: center; gap: 12px; white-space: nowrap; }
.s4-label span { font-size: 1.25rem; color: #dce4ed; }
.s4-track { height: 12px; background: #0d1117; border-radius: 6px; border: 1px solid #1c2535; position: relative; }
.s4-fill { height: 100%; border-radius: 6px; position: absolute; left: 0; top: 0; }
.s4-us { width: 58%; background: linear-gradient(90deg, #1040b8, #4a82f0); }
.s4-dk { width: 42%; background: linear-gradient(90deg, #1040b8, #4a82f0); }
.s4-uk { width: 35%; background: linear-gradient(90deg, #1040b8, #4a82f0); }
.s4-fr { width: 26%; background: linear-gradient(90deg, #1040b8, #1752e8); }
.s4-eu { width: 17%; background: linear-gradient(90deg, #1040b8, #7aaaf5); }
.s4-num { font-family: 'Space Grotesk', sans-serif; font-size: 2.2rem; font-weight: 700; color: #dce4ed; letter-spacing: -0.02em; text-align: right; }
.s4-num-dim { color: #7aaaf5; }
.s4-tagline { margin-top: 24px; font-size: 1.5rem; color: #5a6a7a; font-weight: 600; }
</style>

<!--
**Speaker notes (~2:00)**

"Let's look at the numbers. US: 58%. Denmark: 42% — they've been running national digital infrastructure programmes since 2016. They had a head start. Also they drink a lot of coffee. I'm not saying it's the coffee... but I'm not ruling it out." [beat] "UK: 35%. France went from 13% to 26% in just one year. EU average: 17%."

"These numbers look like momentum. And they are — this is a real trend."

"But there's one word in all these surveys we need to pay attention to: *using*. As in, someone on your team opened ChatGPT this month."

"Adoption is real. But using AI and getting results from AI — not the same thing."

**Transition:** "Let me show you what the results actually look like."

**Timing: ~2:00**
-->

---
transition: fade
---

<div class="slide-5">
  <h2 class="s5-title">What AI-assisted work delivers — documented</h2>
  <div class="s5-panels">
    <div class="s5-panel">
      <div class="s5-flag"><span class="fi fi-gb"></span> UK Gov</div>
      <div class="s5-hero">8,600<span class="s5-unit"> hrs/day</span></div>
      <div class="s5-sub">of admin time freed</div>
      <div class="s5-calc">26 min saved × 20,000 civil servants</div>
      <div class="s5-note">Admin time reclaimed. Every day.</div>
      <div class="s5-src">[2] UK DSIT Trial, Jun 2025</div>
    </div>
    <div class="s5-vline"></div>
    <div class="s5-panel s5-panel-right">
      <div class="s5-flag">🌍 Salesforce — 3,350 SMBs</div>
      <div class="s5-hero">86<span class="s5-unit">%</span></div>
      <div class="s5-sub">of AI-integrated SMBs report<br>improved margins</div>
      <div class="s5-calc">3,350 SMB leaders across 4 regions</div>
      <div class="s5-note">Not just efficiency. Better business.</div>
      <div class="s5-src">[1] Salesforce SMB Trends, 2025</div>
    </div>
  </div>
  <div class="footnote">* 2024–2025 data</div>
</div>

<style>
.slide-5 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 0 60px; gap: 32px; }
.s5-title { font-size: 1rem; font-weight: 700; letter-spacing: 0.28em; text-transform: uppercase; color: #3a4a5a; }
.s5-panels { display: flex; align-items: stretch; width: 100%; gap: 0; }
.s5-panel { flex: 1; display: flex; flex-direction: column; gap: 14px; padding: 0 56px; }
.s5-panel-right { border: none; }
.s5-vline { width: 1px; background: #1c2535; flex-shrink: 0; align-self: stretch; margin: 0; }
.s5-flag { font-size: 0.85rem; font-weight: 700; color: #4a82f0; letter-spacing: 0.05em; }
.s5-hero { font-family: 'Space Grotesk', sans-serif; font-size: 5.5rem; font-weight: 700; color: #1752e8; line-height: 1; letter-spacing: -0.04em; text-shadow: 0 0 60px rgba(23,82,232,0.3); white-space: nowrap; }
.s5-unit { font-size: 2.2rem; font-weight: 700; color: #1752e8; letter-spacing: -0.02em; }
.s5-sub { font-size: 1.1rem; color: #dce4ed; font-weight: 600; line-height: 1.4; min-height: 3.1rem; }
.s5-calc { font-size: 0.9rem; color: #4a5a6a; font-weight: 400; }
.s5-note { font-size: 0.9rem; color: #2a3a4a; font-weight: 600; font-style: normal; margin-top: 4px; }
.s5-src { display: none; }
</style>

<!--
**Speaker notes (~2:00)**

"The UK Government ran a Copilot pilot with 20,000 civil servants — drafting, summarising, reporting. Average saving: 26 minutes per person per day."

"Do the maths. 26 minutes times 20,000 people. That's 8,600 hours freed up. Every. Single. Day." [pause] "That's like having 1,000 extra full-time staff just for admin. In a government department." [beat] "If they can do it, what's your excuse?" [smile]

"Salesforce surveyed 3,350 SMB leaders globally. 86% of those with AI integration report improved margins. Not just time saved — the business itself performs better."

**Transition:** "The data is real. So what's the catch?"

**Timing: ~2:00**
-->

---
transition: fade
---

<div class="slide-6">
  <div class="s6-visual">
    <div class="s6-side">
      <div class="s6-label">use AI</div>
      <div class="s6-num s6-blue">26%</div>
      <div class="s6-src">[14] France Num</div>
    </div>
    <div class="s6-arrow">→</div>
    <div class="s6-side">
      <div class="s6-label">integrated</div>
      <div class="s6-num s6-white">10%</div>
      <div class="s6-src">[15] INSEE</div>
    </div>
  </div>
  <div class="s6-tagline"><strong>That's the catch.</strong></div>
</div>

<style>
.slide-6 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 24px 60px; gap: 44px; }
.s6-visual { display: flex; align-items: center; gap: 56px; }
.s6-side { display: flex; flex-direction: column; align-items: center; gap: 14px; }
.s6-label { font-size: 1.1rem; font-weight: 700; color: #5a6a7a; letter-spacing: 0.1em; text-transform: uppercase; }
.s6-num { font-family: 'Space Grotesk', sans-serif; font-size: 10rem; font-weight: 700; line-height: 1; letter-spacing: -0.04em; }
.s6-blue { color: #1752e8; text-shadow: 0 0 60px rgba(23,82,232,0.25); }
.s6-white { color: #dce4ed; text-shadow: 0 0 60px rgba(220,228,237,0.15); }
.s6-arrow { font-size: 3.5rem; color: #3a4a5a; font-weight: 300; }
.s6-src { font-size: 0.6rem; color: #283040; font-weight: 500; }
.s6-tagline { font-size: 1.5rem; color: #5a6a7a; }
</style>

<!--
**Speaker notes (~1:30)**

"Remember that 26% from the beginning? France Num: 26% of small businesses say they use AI."

"INSEE asked a harder question. Same country. Not 'have you opened ChatGPT' — has AI been *formally integrated* into how the business runs? Repeatable workflows. Connected to business data. Built in."

"10%. One in ten." [pause. let it land.]

"That's the catch. 26% say they use AI. 10% have actually integrated it. That 16-point gap is people copying and pasting into ChatGPT when they remember to."

"Quick show of hands: who here has typed something into ChatGPT, thought 'that's almost right,' and spent 20 minutes editing it?" [pause] "Yeah. That's what 16 points looks like."

**Transition:** "So what does that gap actually look like day to day?"

**Timing: ~1:30**
-->

---
transition: fade
---

<div class="slide-7">
  <h2 class="s7-title">Two Businesses. Same Market. Different Trajectories.</h2>
  <div class="s7-compare">
    <div class="s7-side s7-bad">
      <div class="s7-header">Not Integrated</div>
      <ul class="s7-list">
        <li class="s7-item s7-item-bad">Different result every time</li>
        <li class="s7-item s7-item-bad">Knowledge in one person's head</li>
        <li class="s7-item s7-item-bad">AI spend, unclear ROI</li>
      </ul>
    </div>
    <div class="s7-mid">
      <div class="s7-vs-line"></div>
      <div class="s7-vs">VS</div>
      <div class="s7-vs-line"></div>
    </div>
    <div class="s7-side s7-good">
      <div class="s7-header s7-header-green">Integrated</div>
      <ul class="s7-list">
        <li class="s7-item s7-item-good">Same quality, every time</li>
        <li class="s7-item s7-item-good">Any team member delivers</li>
        <li class="s7-item s7-item-good">91% say AI boosts revenue <span class="s7-src">[1]</span></li>
      </ul>
    </div>
  </div>
  <div class="s7-compound">
    The gap compounds. Every quarter.
  </div>
</div>

<style>
.slide-7 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 28px 60px; gap: 32px; }
.s7-title { font-size: 1rem; font-weight: 700; letter-spacing: 0.2em; text-transform: uppercase; color: #3a4a5a; text-align: center; }
.s7-compare { display: flex; align-items: stretch; width: 100%; gap: 0; }
.s7-side { flex: 1; padding: 32px 36px; }
.s7-bad { background: none; border: none; }
.s7-good { background: none; border: none; }
.s7-header { font-family: 'Space Grotesk', sans-serif; font-size: 1.55rem; font-weight: 700; margin-bottom: 24px; letter-spacing: -0.01em; color: #f73356; text-align: center; }
.s7-header-green { color: #10d97a; }
.s7-list { list-style: none; padding: 0; margin: 0; display: flex; flex-direction: column; gap: 14px; }
.s7-item { font-size: 1.3rem; padding-left: 0; position: relative; white-space: nowrap; }
.s7-item::before { content: '•'; margin-right: 10px; font-size: 1.1rem; position: static; }
.s7-item-bad { color: #7a6068; }
.s7-item-bad::before { color: #f73356; }
.s7-item-good { color: #9baebf; }
.s7-item-good::before { color: #10d97a; }
.s7-loss { color: #f73356; font-style: normal; font-weight: 700; }
.s7-gain { color: #10d97a; font-style: normal; font-weight: 700; }
.s7-src { font-size: 0.6rem; color: #3a4a5a; vertical-align: super; }
.s7-mid { display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 0 24px; gap: 8px; }
.s7-vs-line { width: 1px; flex: 1; background: #1c2535; }
.s7-vs { font-size: 0.72rem; font-weight: 800; color: #3a4a5a; letter-spacing: 0.15em; }
.s7-compound { font-size: 1.2rem; color: #5a6a7a; font-weight: 600; text-align: center; }
</style>

<!--
**Speaker notes (~2:00)**

"Let me paint a picture. Two businesses in the same market in Lille. Same size. Same quality of service."

Walk through each row: "One is using AI but not integrated — ChatGPT on their phone, different prompt every time, no business context. The other has AI tools built around their actual business — connected to their products, their client history, their templates."

"Knowledge lives in whoever remembers it. That's a single point of failure. The integrated business has that knowledge in the tools — new hire? Up and running in an afternoon."

"The not-integrated business does have great conversations with ChatGPT about their strategy though. The strategy never gets executed, but the conversation — genuinely good." [beat]

"Salesforce surveyed 3,350 SMB leaders globally. 91% of those with AI integration say it boosts their revenue. Not headcount cuts — revenue up. Survey data, grain of salt. But 91% is a very loud grain of salt." [beat]

"In France, formal AI integration is at 10% — well below the EU average. Every month that passes, the businesses that have built systems are further ahead. The gap doesn't stay the same size. It grows."

**Transition:** "So what's the right way to build this system? This is where I want to push back on something everyone takes for granted."

**Timing: ~2:00**
-->

---
transition: fade
---

<div class="slide-8">
  <img class="slide-8-image" src="./images/gap_smbs_ai.png" alt="The wall between business users and AI with UX and integration barriers" />
</div>

<style>
.slide-8 { height: 100%; width: 100%; display: flex; align-items: center; justify-content: center; background: #080b0f; padding: 0; margin: 0; }
.slide-8-image { width: 100%; height: 100%; object-fit: contain; }
</style>

<!--
**Speaker notes (~2:00)**

"Here's why most businesses fail to capture value from AI — even when they try."

"You open ChatGPT. There's a blank text box. That's Layer 1 — the UX problem. There's no structure, no business context, no guidance. You don't know what to type. Your team doesn't know what to type. Every person types something different, gets a different result, and half the time it's not usable."

"But it goes deeper. Because even if you can fill that box, there's Layer 2 underneath. To get AI to actually work for your business — consistently, reliably, at scale — you need to engineer your prompts, manage context windows, chain agents together, pick the right LLM for the right task. That is specialist knowledge. Most businesses don't have it."

"So there's a wall. A UX wall and an integration wall, stacked on top of each other. And most businesses bounce off the first layer and never get near the second."

"So what do you do? You can try to figure it out yourself — learn prompt engineering, experiment with different models, build your own system from scratch. Some businesses do. It takes months and a lot of trial and error."

"Or — you work with someone who's already solved both layers."

**Transition:** "That's what we built."

**Timing: ~2:00**
-->

---
transition: fade
---

<div class="slide-9">
  <img class="s9-image" src="./images/pragmatic_labs_bridge.png" alt="Pragmatic Labs AI translation layer connecting your team to AI outputs" />
</div>

<style>
.slide-9 { height: 100%; width: 100%; display: flex; align-items: center; justify-content: center; background: #080b0f; padding: 0; margin: 0; }
.s9-image { width: 100%; height: 100%; object-fit: contain; }
</style>

<!--
**Speaker notes (~3:00)**

"This is Pragmatic Labs AI. And I want to be clear about what makes us different — because it's not the technology. It's how we work."

**The platform exists:** "First — we've already built the platform. This isn't custom development that starts from zero for every client. The infrastructure is there: the AI routing, the knowledge base integration, the form engine, the agent orchestration. All of it. What changes per client is the *configuration* — your tools, your knowledge, your workflows. That's what keeps it fast and affordable."

**Pillar 1 — Human first:** "But we don't just hand you a login. We start with a conversation — human to human. We learn your business. Your workflows. Your pain points. Where does AI actually help *you*? That conversation happens before a single tool gets configured."

**Pillar 2 — Specialized tools, right models:** "Then we configure your tools on the platform. Not one chatbot for everything — specialized tools, one per use case. Customer support gets one tool. Proposals get another. Each one uses the AI model that's best for that specific task — Claude for writing, GPT-4o for analysis, whatever produces stable, high-quality results. Your team doesn't need to know which model is running. They don't need to know if it's Claude, GPT-4, or a very fast intern." [beat] "Unlike the intern, the tool doesn't call in sick."

**Pillar 3 — Beyond chat:** "And here's where we really break from the ChatGPT approach. Your team doesn't face a blank chat box. They get a form. Structured input fields — client name, product type, budget, tone. The form enforces the right data upfront. Clean input in, consistent output out. Every time. Same form, same quality, any team member."

**Admin setup:** "I configure the tool once — connect it to your knowledge base, set the template, define the output format. Then the whole team uses it. Forever. I can go on holiday. The tool keeps working."

**Transition:** "We've done this across industries. Let me give you three real examples."

**Timing: ~3:00**
-->

---
transition: fade
---

<div class="slide-10">
  <h2 class="s10-title">Three Organizations. Real Problems. Real Tools.</h2>
  <div class="s10-tiles">
    <div class="s10-tile">
      <div class="s10-icon">🎓</div>
      <div class="s10-org">Coaching org</div>
      <div class="s10-result">Students get answers at 9PM.<br>Coaches focus on what matters.</div>
    </div>
    <div class="s10-vline"></div>
    <div class="s10-tile">
      <div class="s10-icon">⚖️</div>
      <div class="s10-org">Law firm</div>
      <div class="s10-result">Client intake → research memo.<br>Hours → minutes.</div>
    </div>
    <div class="s10-vline"></div>
    <div class="s10-tile">
      <div class="s10-icon">🏥</div>
      <div class="s10-org">Care org</div>
      <div class="s10-result">Group travel for special needs.<br>Weeks → minutes.</div>
    </div>
  </div>
  <div class="s10-tagline">Same platform. Different tools. Real results.</div>
</div>

<style>
.slide-10 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 28px 60px; gap: 40px; }
.s10-title { font-family: 'Space Grotesk', sans-serif; font-size: 1.8rem; font-weight: 700; color: #dce4ed; letter-spacing: -0.01em; text-align: center; }
.s10-tiles { display: flex; align-items: stretch; width: 100%; gap: 0; }
.s10-tile { flex: 1; display: flex; flex-direction: column; align-items: center; gap: 14px; padding: 0 32px; }
.s10-vline { width: 1px; background: #1c2535; flex-shrink: 0; }
.s10-icon { font-size: 3.5rem; }
.s10-org { font-family: 'Space Grotesk', sans-serif; font-size: 1.5rem; font-weight: 700; color: #dce4ed; }
.s10-result { font-size: 1.1rem; color: #9baebf; text-align: center; line-height: 1.5; }
.s10-tagline { font-size: 1.2rem; color: #1752e8; font-weight: 700; }
</style>

<!--
**Speaker notes (~2:30)**

"A coaching organization came to us with a scaling problem. They didn't have enough coaches. Students had questions at 9 in the evening and nobody to ask. So we built a library of tools on the platform — assessment explainers, goal planners, even a conversation practice tool with roleplay. Now a student at 9PM can clarify their Grit Scale results, practice a difficult conversation, or build a growth plan — without waiting for a coach. The coach is freed up for the work that actually needs a human."

"A family law firm. Their bottleneck was research memos — take client facts, apply jurisdiction-specific law, produce a structured memorandum with next steps. Hours of work per case. We built one tool: structured intake form in, legal research memo out. Same quality, every time."

"A care organization for people with special needs. Group travel planning — accessibility requirements, medical needs, dietary needs, transport logistics. This used to take *weeks* to draft. Now it takes minutes. And the form makes sure nothing gets missed — because when you're planning travel for people with special needs, nothing *can* be missed."

"Three different industries. Three completely different problems. Same platform, same approach."

**Transition:** "Let me show you two of these live."

**Timing: ~2:30**
-->

---
transition: fade
layout: center
---

<div class="slide-11">
  <div class="s11-label">LIVE DEMO</div>
  <div class="s11-tools">
    <span class="s11-tool">🏥 Group Travel Planner</span>
    <span class="s11-sep">·</span>
    <span class="s11-tool">⚖️ Case Researcher</span>
  </div>
  <div class="s11-screenshot">
    <div class="s11-sc-note">🖼️ SCREENSHOT PLACEHOLDERS<br>Travel Planner form + output &nbsp;|&nbsp; Case Researcher form + output<br><span class="s11-warn">Replace before Friday — use as backup if wifi fails</span></div>
  </div>
</div>

<style>
.slide-11 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; text-align: center; gap: 24px; }
.s11-label { font-size: 0.7rem; font-weight: 800; letter-spacing: 0.36em; text-transform: uppercase; color: #1752e8; border: 1px solid #1338a0; border-radius: 20px; padding: 6px 22px; }
.s11-tools { display: flex; align-items: center; gap: 20px; }
.s11-tool { font-family: 'Space Grotesk', sans-serif; font-size: 2.4rem; font-weight: 700; color: #dce4ed; }
.s11-sep { font-size: 2rem; color: #3a4a5a; }
.s11-screenshot { width: 85%; max-width: 700px; height: 150px; border: 1px dashed #1c2535; border-radius: 10px; background: #0d1117; display: flex; align-items: center; justify-content: center; }
.s11-sc-note { font-size: 0.62rem; color: #3a4a5a; line-height: 1.9; }
.s11-warn { color: #f59e0b; }
</style>

<!--
**Speaker notes (~2:00 — live demo)**

"I tested these before the talk. They worked." [beat] "Let's find out if they still do." [open browser]

[Open the Travel Planner tool]

"This is the group travel planner from the care organization. The form captures everything — number of travelers, special needs, accessibility requirements, dietary restrictions, dates, budget. I fill in what's specific to *this* trip."

[Fill in form, submit — show structured output: itinerary with accessibility notes, transport options, accommodation with requirements, cost breakdown]

"There it is. Complete travel plan with every special requirement addressed. Try doing that with ChatGPT and see how many things get missed."

[Switch to Case Researcher tool]

"And this is the family law case researcher. Client facts in — jurisdiction, issues, parties involved — research memorandum out. With applicable law, analysis, and practical next steps for the attorney."

[Fill in form, submit — show structured memo output]

"Same platform. Different tool. Different model behind it. Same pattern: structured input, high-quality output."

**Tech fallback:** "The wifi has opinions about AI apparently." [switch to screenshots] Walk them. Keep energy up.

**Timing: ~2:00**
-->

---
transition: fade
layout: center
---

<div class="slide-12">
  <div class="s12-lines">
    <div class="s12-line"><span class="s12-white">Europe</span> has the talent.</div>
    <div class="s12-line"><span class="s12-white">Your business</span> has the knowledge.</div>
    <div class="s12-line s12-accent">AI is the bridge.</div>
  </div>
  <div class="s12-sub">
    Stop winging it. Start building your invisible partner.
  </div>
  <div class="s12-contact">
    <div class="s12-left">
      <div class="s12-wordmark">Pragmatic Labs AI</div>
      <div class="s12-name">Antonio Alejo Combarro &mdash; Cofounder</div>
      <div class="s12-url">pragmaticlabs.ai</div>
    </div>
    <div class="s12-qr">
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=mailto%3Atony%40pragmaticlabs.ai&margin=6&color=dce4ed&bgcolor=0d1117" width="112" height="112" style="border-radius:4px;display:block;" alt="tony@pragmaticlabs.ai" />
    </div>
  </div>
</div>

<style>
.slide-12 { height: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; background: #080b0f; padding: 28px 80px; gap: 24px; text-align: center; }
.s12-lines { display: flex; flex-direction: column; gap: 2px; }
.s12-line { font-family: 'Space Grotesk', sans-serif; font-size: 3.4rem; font-weight: 700; color: #9baebf; line-height: 1.18; }
.s12-white { color: #dce4ed; }
.s12-accent { color: #1752e8; }
.s12-sub { font-size: 1.2rem; color: #5a6a7a; font-weight: 600; }
.s12-contact { display: flex; align-items: center; gap: 44px; background: #0d1117; border: 1px solid #1c2535; border-radius: 12px; padding: 28px 36px; }
.s12-left { display: flex; flex-direction: column; gap: 6px; text-align: left; }
.s12-wordmark { font-family: 'Space Grotesk', sans-serif; font-size: 1.6rem; font-weight: 700; letter-spacing: -0.01em; color: #dce4ed; }
.s12-name { font-size: 0.95rem; color: #5a6a7a; font-weight: 500; margin-top: 2px; }
.s12-url { font-size: 1.1rem; color: #4a82f0; font-weight: 700; margin-top: 4px; }
.s12-qr { width: 112px; height: 112px; border-radius: 6px; flex-shrink: 0; overflow: hidden; }
</style>

<!--
**Speaker notes (~1:00 + Q&A)**

Slow down. Let it land.

"Europe has more AI professionals per capita than anywhere else. Your business has knowledge that no generic AI tool can replicate — your clients, your products, your way of doing things."

"The bridge is not complicated. It's not expensive. And it's not just for big companies. It's AI that knows your business, delivered through tools your team can actually use."

"And if you only remember one thing from today: stop asking ChatGPT to 'write me a professional email.' It doesn't know what professional means in your business. You do. Give it the right tool, and it will." [smile]

**Q&A opener if silence:** "Let me ask you — what's the most repetitive task in your business that you'd love to never do manually again?"

**Fallback prompts:**
- "Who here has tried ChatGPT? What actually happened?"
- "What would you do with an extra 26 minutes every day?"
- "Does anyone feel like AI isn't relevant to your type of business? — that's actually the most interesting answer."

Also offer: "I have a case researcher and a few other tools on the platform — happy to show you after."

**Timing: ~1:00 + Q&A**
-->
---

<!-- ─── SLIDE 13 — SOURCES ──────────────────────────────── -->
<div class="s-sources">
  <div class="ss-header">Sources &amp; References</div>
  <div class="ss-grid">
    <div class="ss-row">
      <span class="ss-id">[1]</span>
      <div class="ss-body">
        <span class="ss-org">Salesforce</span>
        <a class="ss-title" href="https://www.salesforce.com/news/stories/smbs-ai-trends-2025/">SMB AI Trends 2025</a>
        <span class="ss-meta">3,350 SMB leaders · Aug–Sep 2024</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[2]</span>
      <div class="ss-body">
        <span class="ss-org">UK DSIT</span>
        <a class="ss-title" href="https://www.gov.uk/government/news/landmark-government-trial-shows-ai-could-save-civil-servants-nearly-2-weeks-a-year">Landmark Government Copilot Trial</a>
        <span class="ss-meta">20,000 civil servants · pub. Jun 2025</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[3]</span>
      <div class="ss-body">
        <span class="ss-org">OECD</span>
        <a class="ss-title" href="https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/11/generative-ai-and-the-sme-workforce_83bafdfb/2d08b99d-en.pdf">Generative AI and the SME Workforce</a>
        <span class="ss-meta">5,000+ SMEs · 7 countries · Nov 2025</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[4]</span>
      <div class="ss-body">
        <span class="ss-org">Euronews</span>
        <a class="ss-title" href="https://www.euronews.com/my-europe/2026/01/27/the-ai-race-can-europe-catch-up-to-the-us-and-china">The AI Race — Can Europe Catch Up?</a>
        <span class="ss-meta">Secondary aggregation · Jan 2026</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[5]</span>
      <div class="ss-body">
        <span class="ss-org">Eurostat</span>
        <a class="ss-title" href="https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20251211-2">20% of EU enterprises use AI</a>
        <span class="ss-meta">EU-wide, 10+ employees · pub. Dec 2025</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[6]</span>
      <div class="ss-body">
        <span class="ss-org">Stanford HAI</span>
        <a class="ss-title" href="https://hai.stanford.edu/ai-index/2025-ai-index-report">AI Index Report 2025</a>
        <span class="ss-meta">Annual global AI report · 2025</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[8]</span>
      <div class="ss-body">
        <span class="ss-org">France Num / DGE</span>
        <a class="ss-title" href="https://www.francenum.gouv.fr/guides-et-conseils/strategie-numerique/comprendre-le-numerique/barometre-france-num-2025-le">Baromètre France Num 2025</a>
        <span class="ss-meta">11,021 TPE/PME · Mar–Apr 2025</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[9]</span>
      <div class="ss-body">
        <span class="ss-org">INSEE</span>
        <a class="ss-title" href="https://www.insee.fr/fr/statistiques/8616837?sommaire=8616883">Enquête TIC Entreprises 2024</a>
        <span class="ss-meta">French firms 10+ employees · 2024</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[10]</span>
      <div class="ss-body">
        <span class="ss-org">European Parliament</span>
        <a class="ss-title" href="https://www.europarl.europa.eu/topics/en/article/20230601STO93804/eu-ai-act-first-regulation-on-artificial-intelligence">EU AI Act Overview</a>
        <span class="ss-meta">Official legislative timeline · 2025</span>
      </div>
    </div>
    <div class="ss-row">
      <span class="ss-id">[11]</span>
      <div class="ss-body">
        <span class="ss-org">BCC + Intuit</span>
        <a class="ss-title" href="https://www.britishchambers.org.uk/wp-content/uploads/2025/09/The-Turning-Point-for-SMEs-Unlocking-the-next-level-of-AI.pdf">Turning Point for SMEs</a>
        <span class="ss-meta">1,500 UK SME leaders · Sep 2025</span>
      </div>
    </div>
  </div>
</div>

<style>
.s-sources { height: 100%; display: flex; flex-direction: column; background: #080b0f; padding: 40px 64px 32px; gap: 24px; }
.ss-header { font-size: 0.68rem; letter-spacing: 0.32em; text-transform: uppercase; color: #1752e8; font-weight: 800; }
.ss-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px 48px; align-content: start; }
.ss-row { display: flex; gap: 16px; align-items: baseline; }
.ss-id { font-family: 'JetBrains Mono', monospace; font-size: 0.62rem; font-weight: 700; color: #4a82f0; min-width: 28px; flex-shrink: 0; }
.ss-body { display: flex; flex-direction: column; gap: 2px; }
.ss-org { font-size: 0.52rem; text-transform: uppercase; letter-spacing: 0.14em; color: #3a4a5a; font-weight: 700; }
.ss-title { font-size: 0.72rem; color: #7a8ea0; text-decoration: none; font-weight: 500; }
.ss-title:hover { color: #4a82f0; }
.ss-meta { font-size: 0.52rem; color: #283040; font-weight: 400; }
</style>

<!--
**Sources slide — no speaker notes needed. Shown during Q&A or if audience asks for references.**
-->
