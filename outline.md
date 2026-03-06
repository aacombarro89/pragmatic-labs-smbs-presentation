# The Invisible Partner: How AI Is Becoming Every Small Business's Best Hire
## Slide Deck Outline — Final Merged Version (France/EU, 15–20 min)

---

## Full Context (for AI review or collaborator onboarding)

### Speaker
**Antonio Alejo Combarro** is an AI Team Lead at Spinview (Valencia, Spain) and the cofounder of **Pragmatic Labs AI**, an AI tool platform built specifically for small and medium businesses. He builds production-grade AI systems professionally (agentic RAG frameworks, computer vision pipelines, executive reporting engines) and has direct hands-on experience helping SMBs adopt AI. He is not a native English speaker — the talk is delivered in English to a French audience.

### Event
- **Audience:** ~15 people, business owners and entrepreneurs, Lille, France. English-speaking but mixed backgrounds — not all French, not all SMBs. Expect expats, international founders, freelancers, and people from different industries and countries. Some may run larger businesses or work in corporate roles. The French SMB data is the backbone of the talk, but framing should feel inclusive — "businesses like yours" rather than "French SMBs like yours."
- **Duration:** 15–20 minutes + Q&A
- **Format:** Slide-based, dark-themed deck. Small, friendly room — closer to a fireside chat than a keynote.
- **Delivery:** Friday. Practice session Wednesday afternoon.

### Presentation Title
**"The Invisible Partner: How AI Is Becoming Every Small Business's Best Hire"**

### Core Argument (what the talk must prove)
Most businesses — in France, across Europe, and likely in this room — are aware of AI and increasingly using it (26% of French TPE/PME, doubled in a year), but almost none have actually *integrated* it (only 10% formal adoption, below EU average). The root cause is not cost, not technology — it's that generic chatbots are the wrong interface for business work. The post-chat era means specialized AI tools built around the business's own knowledge and specific use cases, deployable by any team member without prompt engineering skills. That is what Pragmatic Labs AI builds: a platform where organizations configure purpose-built AI tools once, and their entire team uses them forever.

### Framework
**SPIN:** Situation → Problem → Implication → Need

### Pragmatic Labs AI — what it is

**Four pillars — this is how we work with every client:**

1. **Platform already built.** The infrastructure exists — AI routing, knowledge base integration, form engine, agent orchestration. What changes per client is the *configuration*: your tools, your knowledge, your workflows. That's what keeps it fast and affordable.

2. **Human consultancy first.** We don't throw you a sign-up page or a generic tutorial. We sit down with you — human to human — to understand your business, your workflows, and where AI can provide a real improvement. That conversation comes before any tool gets configured.

3. **Specialized tools, best-fit models.** We configure purpose-built AI tools for each use case — not one chatbot for everything. Each tool uses the AI model that's best for that specific task (Claude for writing, GPT-5 for analysis, etc.), producing stable, high-quality results.

4. **Beyond chat — form-based interfaces.** Your team doesn't face a blank chat box. They get structured forms that enforce well-formatted, correct input data. The AI gets clean input every time, so the output is consistent every time.

**How we deliver (architecture):**
- Each **organization** is a fully isolated tenant with: a dedicated Knowledge Base (fed by document storage), a library of use-case-specific AI tools organized into categories, its own AI agents and LLM provider configuration, and role-based team access control
- Each **AI tool** targets a specific business task (e.g., "draft a product proposal", "respond to a customer complaint") and operates in one of two interface modes:
  1. **Chat mode** — conversational interface, AI draws from the organization's knowledge base
  2. **Prompt Builder mode** — a structured form interface; team members fill guided fields, the platform renders inputs into AI prompts via templates, and outputs are returned as structured documents ready for immediate use
- **Admins configure tools once.** Team members just fill forms — no AI knowledge required.
- **LLM routing** selects the best-fit model per tool (OpenAI, Anthropic, Azure, Ollama) with per-organization cost attribution
- **AI Agents** (RAG agent, retriever-synthesizer, direct tool call) are assigned per tool for different retrieval and reasoning strategies

**The core positioning: "We start with your business. We build the tools. Your team just uses them."**

### Tone
- **Funny and self-aware** — this is a small room, not a TED stage. Jokes land better here than polished corporate delivery. Antonio should sound like a smart friend sharing what he's learned over drinks, not a consultant pitching. Self-deprecating humor (non-native English, builder who codes at midnight, "I tested this before the talk — let's see if it still works") keeps the room warm.
- **Confident but approachable** — a practitioner sharing practical knowledge, not lecturing. The humor earns the right to deliver harder truths (the 10% stat, the compounding gap).
- **Empowering, not fear-mongering** — the Implications section motivates action, doesn't panic. Jokes soften the urgency without diluting it.
- **Inclusive framing** — France/EU data is the evidence base, but the message applies to any business in the room regardless of country or size. Say "businesses like yours" not "French SMBs." Audience should feel spoken *with*, not spoken *about*.
- **Slides support the speaker, not replace them** — minimal text, visual-heavy. The speech carries narrative, context, and all the humor. Slides are billboards.

### What a reviewer should look for
1. Does every stat have a source ID that traces to the Verified Sources table?
2. Do the speaker notes give Antonio enough to say without reading off the slide?
3. Is the framing inclusive? France/EU data is the evidence, but the message should land for any business owner in the room — not just French SMBs.
4. Does the SPIN arc land cleanly — does each section earn the next?
5. Is the post-chat vision (Pragmatic Labs AI's core differentiator) explained clearly enough for a non-technical audience?
6. Is the total timing within 15–19 minutes? (11 slides, Slide 3 optional)

---

## Data Verification Summary

Every stat is annotated with `[Source ID]` — see the **Verified Sources** table at the end.

**Strength ratings:**
- **A** = Primary source, verified methodology and sample size
- **B** = Credible institutional source, limited by self-reporting or secondary aggregation

**Key scope notes (all sources are 2024–2025 data — stated on each slide):**
- France Num `[8]`: ALL TPE/PME including <10 employees; broad AI definition (any tool, incl. ChatGPT). 11,021 companies, Crédoc, Mar–Apr 2025.
- INSEE `[9]`: 10+ employee firms only; stricter "formally integrated AI" definition. 2024 survey data.
- Eurostat `[5]`: 10+ employee firms, EU-wide. 2025 data, pub. Dec 2025.
- BCC/Intuit `[11]`: UK SME leaders; "actively using" vs "customised to internal operations." Sep 2025.
- These sources are complementary — they measure different scopes and countries. The `_* 2024–2025 data_` footnote on applicable slides covers all of them.

---

## Slide 1 — Title

**Visual:** Dark background, bold title, subtle abstract AI node graphic (connections/network). Clean and modern. **No horizontal divider lines between content blocks** — use vertical spacing only. Divider rules are a common AI-generated slide tell. **QR code** bottom-right corner linking to `https://aacombarro89.github.io/pragmatic-labs-smbs-presentation/1` with "Follow along" label.

**On-screen text:**
> **The Invisible Partner**
> How AI Is Becoming Every Small Business's Best Hire
>
> Antonio Alejo Combarro — Cofounder, Pragmatic Labs AI | AI Team Lead @ Spinview
> March 2026

**Speaker notes (≤30 sec):**
- "I'm Antonio. Day job: I lead an AI team at Spinview building production AI systems. Side mission: Pragmatic Labs AI, where I help small businesses put AI to work — not the Silicon Valley hype version, the actually-useful version."
- "I promise this won't be a talk where someone tells you AI is going to replace all your jobs. Well. Not all of them." [beat]
- "Today: where AI actually is in France and Europe right now, why most businesses aren't capturing the benefit, and what a genuinely different approach looks like. Let's go."

**Timing:** ~0:25

---

## Slide 2 — Hook: France Is Moving Fast

**Visual:** Single enormous number dominating the slide — **`26%`** should be 200pt+ hero text, centered, electric blue on dark background. Two short lines of supporting text only, small below. Nothing else. The number must read from the back of the room.

**On-screen text:**
> **26%**
> of French TPE/PME say they use AI — up from **13% in 2024** **[8]**
>
> _But there's a catch._

**Speaker notes (~1:00):**
- "Let me start with one number. France Num surveyed over 11,000 small and medium businesses last year. 26% say they use AI. A year earlier it was 13%. It *doubled*."
- "Which, depending on how you define 'use AI'... might just mean someone's nephew showed them ChatGPT at Christmas." [beat, smile]
- "But either way — real momentum. And I want you to hold onto that 26% — because I'm going to come back to it with a twist."
- **Transition:** "First, the bigger picture."

**Timing:** ~1:00

**Data:** `[8]` France Num 2025 — **A**

---

## Slide 3 — Situation: The Global AI Race _(Optional — cut by default if running to time)_

**Visual:** Three hero number blocks side by side — one per country, no table. Big flag emoji above each block. Each block shows ONE key number (the most striking stat for that country). Below the three blocks: a single stark contrast line. **No table, no rows, no column headers — pure hero numbers.**

> **🇺🇸 $109B** private AI investment
> **🇪🇺 $8B** — but **+30%** AI talent vs US
> **🇨🇳 $9.3B**
>
> _Europe has the people. The money went elsewhere._
> **[4] [6]**

**Speaker notes (~2:00):**
> _If skipping this slide: mention one number verbally during Slide 2 — "The US attracted $109 billion in AI investment last year. Europe: $8 billion. But Europe has 30% more AI professionals per capita. The gap isn't talent. It's adoption." Then move straight to Slide 4._

- "Here's the global picture. And I want to be honest — the numbers are stark."
- "$109 billion of private AI investment went to the US last year. Europe attracted $8 billion. The US produced 40 notable AI foundation models. Europe produced 3."
- "The compute gap is even wider. The US has 17 times Europe's AI supercomputing capacity. And 72% of the European cloud market runs on US infrastructure."
- "But here's what nobody talks about: Europe has 30% more AI professionals per capita than the US. Three out of four European AI PhD graduates who go to the US stay there for at least five years. The talent is here. It's leaving — or it's not being activated."
- "For small businesses in France, this is the big picture context: the tools, the expertise, the capability — it's all accessible in Europe. The gap isn't technology. It's adoption and application."
- **Transition:** "So are businesses in Europe actually keeping up?"

**Timing:** ~2:00

**Data:** `[4]` Euronews (secondary, citing Stanford/State of AI) — **B**; `[6]` Stanford AI Index 2025 — **A**

---

## Slide 4 — Situation: AI Adoption Is Spreading — France, UK, EU

**Visual:** Three large bars side by side, labelled 🇫🇷 France / 🇬🇧 UK / 🇪🇺 EU avg. These are **usage/adoption numbers** — the surface-level momentum picture. Bars should be LARGE and fill most of the slide. Numbers only inside or above each bar. One caption line at bottom. No legends.

**On-screen text:**
> **Small Business AI Adoption — 2025**
>
> 🇺🇸 **58%** &nbsp;&nbsp;&nbsp; 🇩🇰 **42%** &nbsp;&nbsp;&nbsp; 🇬🇧 **35%** &nbsp;&nbsp;&nbsp; 🇫🇷 **26%** &nbsp;&nbsp;&nbsp; 🇪🇺 **17%**
>
> _Using AI. But using ≠ integrated._
> _* 2024–2025 data; [12][5][11][8]_

**Speaker notes (~1:30):**
- "Let's look at the numbers. US: 58%. Denmark: 42% — they've been running national digital infrastructure programmes since 2016. They had a head start. Also they drink a lot of coffee. I'm not saying it's the coffee... but I'm not ruling it out." [beat] "UK: 35%. France went from 13% to 26% in just one year. EU average: 17%."
- "These numbers look like momentum. And they are."
- "But there's a word in all these surveys we need to pay attention to: *using*. As in, someone on your team opened ChatGPT this month."
- "Adoption is real. But using AI and getting results from AI — not the same thing."
- **Transition:** "Let me show you what the results actually look like."

**Timing:** ~1:30

**Data:** `[12]` US Chamber of Commerce "Empowering Small Business" Jun 2025 — **A**; `[5]` Eurostat Dec 2025 — **A** (includes Denmark country breakdown); `[11]` BCC/Intuit Sep 2025 — **A**; `[8]` France Num 2025 — **A**

---

## Slide 5 — Situation (→ Problem Bridge): The Productivity Case

**Visual:** Two hero stat cards, side by side, each half the slide. Numbers enormous — **`26 min`** → **`8,600 hrs/day`** dominate the left card (the multiplication written large, like an equation); **`46%`** dominates the right card. One short context line below each number. Nothing else. Think billboard. No bullet lists, no parenthetical lines — those go in speaker notes.

**On-screen text:**
> **What AI-assisted work actually delivers**
>
> **🇬🇧 UK Gov [2]**
> **26 min** × 20,000 people = **8,600 hrs/day**
> _Admin time reclaimed. Every day._
>
> **🌍 OECD — 7 countries [3]**
> **46%** of SMEs using AI report better employee performance
> _Not cost cuts. Better work._
>
> _* 2024–2025 data_

**Speaker notes (~2:00):**
- "The UK Government ran a Copilot pilot with 20,000 civil servants — drafting, summarising, reporting. Average saving: 26 minutes per person per day."
- "Do the maths. 26 minutes times 20,000 people. That's 8,600 hours freed up. Every. Single. Day." [pause] "That's like having 1,000 extra full-time staff just for admin. In a government department." [beat] "If they can do it, what's your excuse?" [smile]
- "OECD surveyed 5,000 SMEs across seven countries. 46% of those using AI say their employees perform better. Not headcount cuts — better work from the same people."
- **Transition:** "The data is real. So what's the catch?"

**Timing:** ~2:00

**Data:** `[2]` UK Gov/DSIT pub. Jun 2025 — **B** (self-reported); `[3]` OECD Dec 2025 — **A**

---

## Slide 6 — Problem: The Gap

**Visual:** Pure billboard. Two giant numbers side by side — **26%** on the left (blue), **10%** on the right (white/bright), connected by an arrow or dash. A single label above each: "use AI" / "integrated." The 16-point gap between them is the entire visual story. Below: one tagline. Nothing else. This is the Slide 2 payoff — "there's a catch" — and it must land like a punch.

**On-screen text:**
> **26%** use AI **[14]** &nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp; **10%** integrated **[15]**
>
> _That's the catch._

**Speaker notes (~1:30):**
- "Remember that 26% from the beginning? France Num: 26% of small businesses say they use AI."
- "INSEE asked a harder question. Same country. Not 'have you opened ChatGPT' — has AI been *formally integrated* into how the business runs? Repeatable workflows. Connected to business data. Built in."
- "10%. One in ten." [pause. let it land.]
- "That's the catch. 26% say they use AI. 10% have actually integrated it. That 16-point gap is people copying and pasting into ChatGPT when they remember to — and calling it a strategy."
- **Transition:** "So what does that gap actually look like day to day?"

**Timing:** ~1:30

**Data:** `[14]` France Num — **A**; `[15]` INSEE — **A**

---

## Slide 7 — Implication: The Gap Compounds

**Visual:** Split "Not Integrated" vs "Integrated" contrast table. Left side muted grey, right side vibrant accent. Bottom: one key stat from Salesforce (labeled as survey-based).

**On-screen text:**
> **Two Businesses. Same Market. Different Trajectories.**
>
> | Not Integrated | Integrated |
> |---|---|
> | Different result every time | Same quality, every time |
> | Knowledge in one person's head | Any team member delivers |
> | AI spend, unclear ROI | 91% say AI boosts revenue **[1]** |
>
> _The gap compounds. Every quarter._

**Speaker notes (~2:00):**
- "Let me paint a picture. Two businesses in the same market in Lille. Same size. Same quality of service."
- Walk through each row: "One is using AI but not integrated — ChatGPT on their phone, different prompt every time, no business context. The other has AI tools built around their actual business — connected to their products, their client history, their templates."
- "Knowledge lives in whoever remembers it. That's a single point of failure. The integrated business has that knowledge in the tools — new hire? Up and running in an afternoon."
- "The not-integrated business does have great conversations with ChatGPT about their strategy though. The strategy never gets executed, but the conversation — genuinely good." [beat]
- "Salesforce surveyed 3,350 SMB leaders globally. 91% of those with AI integration say it boosts their revenue. Not headcount cuts — revenue up. Survey data, grain of salt. But 91% is a very loud grain of salt." [beat]
- **Transition:** "So why aren't more businesses on the right side of that table?"

**Timing:** ~2:00

**Data:** `[1]` Salesforce SMB Trends 2025 — **A**

---

## Slide 8 — Need (Root Cause): The Wall Between Your Business and AI

**Visual:** Full-size image only (no slide title, no extra overlay text). Use the wall metaphor artwork showing the business user on the left, AI complexity on the right, and the two stacked barriers in the center (**Layer 1** in amber, **Layer 2** in red).

**On-screen text:**
> _(None — image only)_

**Speaker notes (~2:00):**
- "Here's why most businesses fail to capture value from AI — even when they try."
- "You open ChatGPT. There's a blank text box. That's Layer 1 — the UX problem. There's no structure, no business context, no guidance. You don't know what to type. Your team doesn't know what to type. Every person types something different, gets a different result, and half the time it's not usable."
- "But it goes deeper. Because even if you can fill that box, there's Layer 2 underneath. To get AI to actually work for your business — consistently, reliably, at scale — you need to engineer your prompts, manage context windows, chain agents together, pick the right LLM for the right task. That is specialist knowledge. Most businesses don't have it."
- "So there's a wall. A UX wall and an integration wall, stacked on top of each other. And most businesses bounce off the first layer and never get near the second."
- "So what do you do? You can try to figure it out yourself — learn prompt engineering, experiment with different models, build your own system from scratch. Some businesses do. It takes months and a lot of trial and error."
- "Or — you work with someone who's already solved both layers."
- **Transition:** "That's what we built."

**Timing:** ~2:00

---

## Slide 9 — Need: Pragmatic Labs AI — The Translation Layer

**Visual:** Full-size image only (no title, no extra overlay text), using `slides/images/pragmatic_labs_bridge.png`. The image should clearly show the translation layer concept with filled-in human-side input and filled-in structured output.

**On-screen text:**
> _(None — image only)_

**Speaker notes (~3:00):**
- **Intro:** "This is Pragmatic Labs AI. Four things make it work."
- **Pillar 1 — Platform:** "The platform already exists. AI routing, knowledge base integration, form engine, agent orchestration — all of it. We don't start from zero for each client. What changes is the configuration: your tools, your knowledge, your workflows. That's what keeps it fast and affordable."
- **Pillar 2 — Human first:** "We start with a conversation — human to human. Your business, your workflows, your pain points. Where does AI actually help *you*? That happens before a single thing gets configured."
- **Pillar 3 — Specialized tools:** "Then we configure specialized tools — one per use case. Customer support gets its own. Proposals get another. Each uses the model that's best for that task — Claude for writing, GPT-5 for analysis, whatever produces the best results. Your team doesn't need to know which model is running. They don't need to know if it's Claude, GPT-5, or a very fast intern." [beat] "Unlike the intern, it doesn't call in sick."
- **Pillar 4 — Beyond chat:** "And your team never sees a blank text box. They get a form — structured fields: client name, product type, budget, tone. Clean input in, consistent output out. Every time. I configure it once, the whole team uses it forever. I can go on holiday. It keeps working."
- **Transition:** "We've done this across industries. Let me give you three real examples."

**Timing:** ~3:00

---

## Slide 10 — Need: Three Organizations. Real Problems. Real Tools.

**Visual:** Three large tiles in a row (same pattern as the workflows slide). Icon + org type + one-line result per tile. Billboard-simple. Font large enough to read from back of room.

**On-screen text:**
> **Three Organizations. Real Problems. Real Tools.**
>
> 🎓 **Coaching org** → Students get answers at 9PM. Coaches focus on what matters.
> ⚖️ **Law firm** → Client intake → research memo. Hours → minutes.
> 🏥 **Care org** → Group travel for special needs. Weeks → minutes.
>
> _Same platform. Different tools. Real results._

**Speaker notes (~2:30):**
- "A coaching organization came to us with a scaling problem. They didn't have enough coaches. Students had questions at 9 in the evening and nobody to ask. So we built a library of tools on the platform — assessment explainers, goal planners, even a conversation practice tool with roleplay. Now a student at 9PM can clarify their Grit Scale results, practice a difficult conversation, or build a growth plan — without waiting for a coach. The coach is freed up for the work that actually needs a human."
- "A family law firm. Their bottleneck was research memos — take client facts, apply jurisdiction-specific law, produce a structured memorandum with next steps. Hours of work per case. We built one tool: structured intake form in, legal research memo out. Same quality, every time."
- "A care organization for people with special needs. Group travel planning — accessibility requirements, medical needs, dietary needs, transport logistics. This used to take *weeks* to draft. Now it takes minutes. And the form makes sure nothing gets missed — because when you're planning travel for people with special needs, nothing *can* be missed."
- "Three different industries. Three completely different problems. Same platform, same approach."
- **Transition:** "Let me show you two of these live."

**Timing:** ~2:30

---

## Slide 11 — Need: Live Demo

**Visual:** Single slide, minimal text — this is a live demo frame. Dark background. Tool names on screen. Have static screenshots as backup layers (hidden, reveal if tech fails).

**On-screen text:**
> **LIVE DEMO**
>
> 🏥 Group Travel Planner &nbsp;&nbsp;&nbsp; ⚖️ Case Researcher

**Speaker notes (~2:00 — live demo):**
- "I tested these before the talk. They worked." [beat] "Let's find out if they still do." [open browser]
- [Open the Travel Planner tool]
- "This is the group travel planner from the care organization. The form captures everything — number of travelers, special needs, accessibility requirements, dietary restrictions, dates, budget. I fill in what's specific to *this* trip."
- [Fill in form, submit — show structured output: itinerary with accessibility notes, transport options, accommodation with requirements, cost breakdown]
- "There it is. Complete travel plan with every special requirement addressed. Try doing that with ChatGPT and see how many things get missed."
- [Switch to Case Researcher tool]
- "And this is the family law case researcher. Client facts in — jurisdiction, issues, parties involved — research memorandum out. With applicable law, analysis, and practical next steps for the attorney."
- [Fill in form, submit — show structured memo output]
- "Same platform. Different tool. Different model behind it. Same pattern: structured input, high-quality output."

> _**Tech fallback:** If demo fails — don't apologise, just pivot: "The wifi has opinions about AI apparently." [switch to screenshots] "Let me show you what the output looks like." Walk the screenshots. Keep energy up._

**Timing:** ~2:00

---

## Slide 12 — Close + Q&A / Contact

**Visual:** Dark background, minimal text, centered. Three-line close message in large type. Below: Antonio's name with Pragmatic Labs AI logo + wordmark (if available), then contact block with real QR code. **⚠️ Action required before Friday: replace the QR code placeholder with a real QR code** pointing to Antonio's booking link or the Pragmatic Labs AI website — a placeholder icon will look unfinished on the projector screen.

**Branding block (bottom of slide):**
- Pragmatic Labs AI logo / wordmark — use the actual brand asset if available; if not, styled text: **PRAGMATIC LABS AI** in a clean sans-serif, slightly smaller than the close text
- Antonio's contact or booking link below the logo
- QR code: encodes `mailto:tony@pragmaticlabs.ai` — generated via qrserver.com, displayed at ~4×4 cm

**On-screen text:**
> **Europe has the talent.**
> **Your business has the knowledge.**
> **AI is the bridge.**
>
> _Stop guessing. Start integrating._
>
> **Antonio Alejo Combarro** — Cofounder, Pragmatic Labs AI
> pragmaticlabs.ai · tony@pragmaticlabs.ai · [QR → tony@pragmaticlabs.ai]

**Speaker notes (~1:00 + Q&A):**
- Slow down. Let it land.
- "Europe has more AI professionals per capita than anywhere else. Your business has knowledge that no generic AI tool can replicate — your clients, your products, your way of doing things."
- "The bridge is not complicated. It's not expensive. And it's not just for big companies. It's AI that knows your business, delivered through tools your team can actually use."
- "And if you only remember one thing from today: stop asking ChatGPT to 'write me a professional email.' It doesn't know what professional means in your business. You do. Give it the right tool, and it will." [smile]
- Q&A opener if silence: "Let me ask you — what's the most repetitive task in your business that you'd love to never do manually again?"
- Fallback prompts:
  - "Who here has tried ChatGPT? What actually happened?"
  - "What would you do with an extra 26 minutes every day?"
  - "Does anyone feel like AI isn't relevant to your type of business? — that's actually the most interesting answer."
- Also offer: "I have a case researcher and a few other tools on the platform — happy to show you after if you want to see a different use case."

**Timing:** ~1:00 + Q&A

---

## Visual QA Notes

Issues to check when reviewing the generated deck:

| Slide | Issue | Fix |
|-------|-------|-----|
| **1** | Horizontal divider rule between subtitle and bio block | Remove rule; use vertical spacing only |
| **3** | EU column: all values tinted same warning color | Use red/orange only for negative figures ($8B, 3 models, compute lag); keep talent row (+30%) in neutral or positive accent |
| **4** | EU bar chart uses grey bars on dark blue background | May wash out on projector. Test on venue screen. Consider lighter grey or white bars |
| **6** | "HAVING A SYSTEM" column header wraps to 2 lines; "TOUCHING AI" sits on 1 line | Reduce right header font by 1–2pt so both headers are single-line and visually symmetrical |
| **8** | Wall visual — two barrier labels must be legible | Layer 1 (amber) and Layer 2 (red) must read clearly; tagline anchors bottom — no dead space below it |
| **9** | Human-side form and output panel must be filled-in | Do NOT leave either side blank; form shows labelled fields, output shows document with section headers + Export PDF button |
| **10** | Demo slide — have static screenshot as backup layer | Screenshot: travel planner form (left) + output (right). Reveal if wifi/projector fails |
| **12** | QR code is a placeholder icon | ✅ Real QR generated — encodes tony@pragmaticlabs.ai |

---

## Total Estimated Timing

| Section | Slides | Time |
|---------|--------|------|
| Title + Hook | 1–2 | ~1:30 |
| Situation _(Slide 3 optional)_ | 3–5 | ~4:00 (–2:00 if Slide 3 cut) |
| Problem + Implication | 6–7 | ~4:00 |
| Need (Post-chat + Product + Demo + Workflows) | 8–11 | ~8:30 |
| Close + Q&A | 12 | ~1:00 + Q&A |
| **Total (with Slide 3)** | **12** | **~19:00–21:00** |
| **Total (without Slide 3)** | **11** | **~17:00–19:00** |

**Pacing notes:**
- With demo (Slide 10) and Slide 3 both included: ~19–21 min — slightly over budget. Drop Slide 3.
- **Recommended default:** skip Slide 3, run demo. 17–19 min with healthy Q&A buffer.
- If demo runs long or has tech issues: cap it at 90 seconds, skip "under the hood" explanation.
- Case researcher and travel planner can both be teased at Q&A: *"I also have a case research tool and a few others — happy to show you after."*

---

## Narrative Arc

1. **Hook:** France is moving on AI — 26% of TPE/PME now use it, doubled in a year. Momentum is real. But there's a catch. (The catch is withheld here — revealed in Slide 6 for maximum impact.)
2. **Situation:** Europe lags the US and China on AI investment and infrastructure, but holds a talent advantage. French and EU small businesses lag large enterprises by 3–6× on formal adoption. The opportunity is real and uncrowded — 9% in France means early movers have the field to themselves.
3. **Problem:** Here's the catch. INSEE says only 10% of French businesses have formally integrated AI — below the EU average. That 16-point gap is the "guessing" problem: ChatGPT on a personal account, different prompts every time, no business context, knowledge that lives in one person's head. Objection handled here: EU AI Act is not a blocker for everyday SMB use cases.
4. **Implication:** The gap compounds. Businesses that build systems now get further ahead every quarter. 26 min/person/day reclaimed. Proposals in 20 min instead of 4 hours. The gap isn't staying the same size — it grows.
5. **Need:** Post-chat AI is the answer — not a chatbot, but purpose-built tools connected to business knowledge. Pragmatic Labs AI: admins configure once, team fills forms, AI generates structured output. Live demo — travel planner — proves the differentiator: "ChatGPT can write. This *knows your business.*" Three workflows that pay back fast: support, proposals, operations.
6. **Close:** Europe has the talent. Your business has the knowledge. AI is the bridge. Stop guessing. Start integrating.

---

## Verified Sources

| ID | Source | Organization | Methodology | Sample | Date | Strength |
|----|--------|-------------|-------------|--------|------|----------|
| **[1]** | [Salesforce SMB AI Trends](https://www.salesforce.com/news/stories/smbs-ai-trends-2025/) | Salesforce | Survey of SMB leaders (≤200 employees), NA/LATAM/APAC/Europe | 3,350 SMB leaders | Aug–Sep 2024 (pub. 2025) | **A** |
| **[2]** | [UK Gov Copilot Trial](https://www.gov.uk/government/news/landmark-government-trial-shows-ai-could-save-civil-servants-nearly-2-weeks-a-year) | UK DSIT | Workplace trial with Microsoft 365 Copilot; self-reported daily savings | 20,000 civil servants | Sep–Dec 2024 (pub. Jun 2, 2025) | **B** (self-reported) |
| **[3]** | [OECD "Generative AI and the SME Workforce"](https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/11/generative-ai-and-the-sme-workforce_83bafdfb/2d08b99d-en.pdf) | OECD | Representative survey of SMEs in 7 countries; **46% of SMEs using genAI report improved employee performance**; 31% of SMEs use genAI | 5,000+ SMEs (Austria, Canada, Germany, Ireland, Japan, Korea, UK) | Nov 2025 | **A** |
| **[4]** | [Euronews: "The AI Race — Can Europe Catch Up?"](https://www.euronews.com/my-europe/2026/01/27/the-ai-race-can-europe-catch-up-to-the-us-and-china) | Euronews | Secondary aggregation of Stanford AI Index + State of AI Report | Various | Jan 27, 2026 | **B** (secondary) |
| **[5]** | [Eurostat: "20% of EU enterprises use AI"](https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20251211-2) | Eurostat | Annual EU enterprise survey; **10+ employees only** | EU-wide | 2025 data, pub. Dec 11, 2025 | **A** |
| **[6]** | [Stanford AI Index Report 2025](https://hai.stanford.edu/ai-index/2025-ai-index-report) | Stanford HAI | Comprehensive annual global AI report, multi-source | Multi-source | 2025 | **A** |
| **[7]** | [EU Digital SME Alliance (via HBR)](https://hbr.org/2025/09/how-smes-can-prepare-for-the-eus-ai-regulations) | European Digital SME Alliance | Survey of EU small/medium tech companies on AI Act readiness | Not disclosed | Sep 2025 | **A** |
| **[8]** | [Baromètre France Num 2025](https://www.francenum.gouv.fr/guides-et-conseils/strategie-numerique/comprendre-le-numerique/barometre-france-num-2025-le) | France Num / Direction générale des Entreprises | Online + phone survey of **all TPE/PME** (including <10 employees); broad AI definition | 11,021 companies (7,978 TPE + 3,043 PME) | Mar 26–Apr 18, 2025 (pub. Sep 2025) | **A** |
| **[9]** | [INSEE Enquête TIC Entreprises 2024](https://www.insee.fr/fr/statistiques/8616837?sommaire=8616883) | INSEE | Annual TIC survey; **10+ employee firms** only; stricter "formally integrated AI" definition | French enterprises 10+ employees | 2024 data | **A** |
| **[10]** | [EU AI Act — European Parliament](https://www.europarl.europa.eu/topics/en/article/20230601STO93804/eu-ai-act-first-regulation-on-artificial-intelligence) | European Parliament (EPRS) | Official legislative timeline | — | 2025 | **A** |
| **[11]** | [BCC/Intuit "Turning Point for SMEs"](https://www.britishchambers.org.uk/wp-content/uploads/2025/09/The-Turning-Point-for-SMEs-Unlocking-the-next-level-of-AI.pdf) | British Chambers of Commerce + Intuit | Survey of UK SME leaders; 35% actively using AI, only 10% customised to internal operations | 1,500 UK SME leaders | Sep 2025 | **A** |

### Stats Used Per Slide

| Slide | Stats / Claims | Source IDs |
|-------|---------------|------------|
| 2 (Hook) | 26% TPE/PME use AI, up from 13% in 2024 | [8] |
| 3 (Global Race) | $109B vs $8B vs $9.3B; 40 vs 3 foundation models; 17× compute; +30% talent | [4], [6] |
| 4 (FR/UK/EU gap) | FR 9% integrated; UK 10% customised; EU small 17% active | [5], [9], [11] |
| 5 (Proof) | 26 min/day × 20,000 = 8,600 hrs/day; 46% of SMEs using AI report better employee performance | [2], [3] |
| 6 (Problem) | 26% use vs 10% integrate (France); EU AI Act framing (low-risk for SMB use cases) | [8], [9], [10] |
| 7 (Implication) | Knowledge lock-in vs any team member delivers; 91% of AI-integrated SMBs report revenue boost | [1] |
