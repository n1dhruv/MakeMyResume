# Brag Plan: MakeMyResume

## What is this app?
MakeMyResume is an evidence-backed AI resume-tailoring platform that matches a user's verified Skill Bank against job descriptions using hybrid vector search and reranking, rewrites bullets with strict fabrication guardrails, and compiles single-page LaTeX PDFs editable in-browser.

## The angle
Most AI resume tools hallucinate fake metrics, invent technologies, and dump unformatted Markdown. MakeMyResume enforces strict truth: source evidence is immutable, hybrid vector search + reranking extracts the highest-relevance proof points, AI rewrites are audited against fabrication guardrails, and users control their own LLM with BYOK—compiling to professional, ATS-ready LaTeX PDFs.

## Hook (first 2-3 seconds)
The video opens on the iconic framed `[ R ]` emblem and editorial serif headline: *"Build from what you've done. Tailor for where you're going."* Real Skill Bank cards slide in with verified tags and metrics (`18 → 6 min`, `2.4M events/mo`).

## Key moments (the middle)
1. **Hybrid Vector Search & Reranking (Scene 2):** Job description pasted ("Fathom · Senior Product Engineer") → dual Pinecone dense (2048-d) + sparse indexes run in parallel → reranker filters candidates to 94% match confidence.
2. **AI Rewrite with Fabrication Guardrails (Scene 3):** Side-by-side comparison: *"Original — source truth"* vs *"Proposed rewrite"*. Visual guardrail badges check numbers & tech; user hits "Approve" with a crisp checkmark.
3. **In-Browser LaTeX & PDF with Dark/Light + BYOK (Scene 4):** Live split-screen with Monaco-style LaTeX code editor on the left and rendered PDF resume on the right; seamless dark/light toggle and BYOK pill badge showing user LLM control.

## Outro / punchline
The MakeMyResume boxed `[ R ]` emblem scales into center focus alongside the official tagline: *"Your evidence. Your approval. Your resume."* ending on the clear launch domain: **makemyresume.tech**.

## User flow worth showing
1. **Entry:** Skill Bank with structured, tagged experience bullets and measurable metrics.
2. **Action 1:** Pasting JD → Hybrid Pinecone dense/sparse search + reranker selects exact evidence.
3. **Action 2:** AI rewrites bullets with strict anti-fabrication guardrail checks and explicit user approval.
4. **Result:** In-browser LaTeX compilation to instant single-page PDF with dark/light mode and BYOK.

## Tone
- **Preset:** `polished`
- **Creative direction:** Confident SaaS launch reel with product-demo authenticity and elegant editorial typography.
- **Interpretation:** Snappy pacing with generous settled holds for reading; high-contrast typography pairing editorial serif (Newsreader) with clean sans (Instrument Sans) and terminal mono (IBM Plex Mono); terracotta accent pop against crisp deep surfaces.

## Format: landscape — 1920x1080
## Duration: 20.0 seconds

## Visual identity (from the project)
- **Background (Dark):** `#0e0d0c` / `oklch(14% .01 55)` (Canvas), `#171614` (Surface)
- **Background (Light mode flash):** `#f7f6f3` / `oklch(96% .015 78)`
- **Accent:** `#c84b31` / `oklch(55% .175 34)` (Terracotta coral brand color)
- **Accent soft:** `rgba(200, 75, 49, 0.15)`
- **Text:** `#f4f2ee` (Ink white), `#9b9890` (Muted), `#22c55e` (Success green), `#eab308` (Warning gold)
- **Display font:** Newsreader / Georgia / serif
- **Body font:** Instrument Sans / Avenir Next / sans-serif
- **Mono font:** IBM Plex Mono / monospace
- **Strongest visual element:** The boxed `[ R ]` logo, the split Source vs Rewrite card with guardrail pill badges, and the live LaTeX + PDF compiler view.

## Share copy (draft)
Stop letting AI hallucinate your resume. MakeMyResume matches your verified career evidence with hybrid search, rewrites with strict fabrication guardrails, and compiles beautiful LaTeX PDFs: makemyresume.tech

## Audio direction
- **Role:** Modern, energetic, confident SaaS launch bed with crisp UI percussion and motion-matched interface feedback.
- **Music:** `happy-beats-business-moves-vol-12-by-ende-dot-app.mp3`
- **Music treatment:** Upbeat bed starting at 0.0s, steady 110 BPM groove at volume 0.32, smooth 1.5s fade-out under the final tagline.
- **Music cue guidance:** Using precomputed preset cues from `happy-beats-business-moves-vol-12-by-ende-dot-app.music-cues.json`:
  - Strong cues: 8.74s, 10.93s, 13.11s, 17.47s, 22.93s.
  - Beat-grid windows: Scene 2 search results (5.34s, 6.00s, 6.56s), Scene 3 guardrail tags (8.74s, 9.29s, 9.83s), Scene 4 compile & render (12.55s, 13.11s).
- **Audio-reactive treatment:** Subtle RMS warmth and terracotta glow breathing behind the brand emblem and active cards.
- **SFX posture:** Moderate, motion-matched precision: UI clicks on user actions, card drops on evidence matching, keypress ticks on JD input, crisp check ding on approval, resonant bell on final logo.
- **Audio-coupled moments:**
  - Skill Bank cards landing: `casino/card-slide-1.ogg`, `card-place-1.ogg`
  - JD paste & search trigger: `interface/click_002.ogg`
  - Hybrid vector match pill reveal: `interface/drop_001.ogg`, `drop_002.ogg`
  - Approval checkmark toggle: `ui/click1.ogg`
  - LaTeX compile trigger & PDF ready: `interface/switch_001.ogg` & `impact/impactBell_heavy_000.ogg`
- **Restraint rule:** Never obscure text readability; no loud explosion noises; all sounds stay grounded in premium productivity tool aesthetics.

## Storyboard

### Scene 1 — The Foundation: Skill Bank (0.0s – 3.2s)
The video opens with the MakeMyResume `[ R ]` brand mark and editorial serif statement: *"Build from what you've done."* Two structured Skill Bank cards slide in showing verified evidence with tags (`React`, `TypeScript`, `PostgreSQL`) and quantifiable metrics (`18 → 6 min`, `2.4M events/mo`).
- Sequential/interaction: Logo reveals at 0.2s, headline at 0.6s, two evidence cards cascade in at 1.4s and 2.0s.
- Audio intent: Crisp, confident launch opener.
- Audio-coupled idea: Subdued impact on logo reveal (`impactSoft_medium_001`), card slides on evidence arrival (`casino/card-slide-2`).
- Music: Upbeat start.
- Transition mood: Clean slide transition → Scene 2.

### Scene 2 — The Input: JD & Hybrid Search (3.2s – 7.2s)
A Job Description card appears: *"Fathom · Senior Product Engineer"*. A search radar pulses showing: *"Hybrid Retrieval: Dense (2048-d Nemotron) + Sparse BM25 + FlashRank Reranker"*. Matched candidate cards populate with confidence indicators (`94% relevance`).
- Sequential/interaction: JD input types/appears at 3.4s, Pinecone vector search pulse at 4.2s, 3 matched proof pills pop sequentially at 5.2s, 5.8s, 6.4s.
- Audio intent: Precision tech capability, high computational confidence.
- Audio-coupled idea: Input click at 3.5s, sequential drop accents on match pills (`interface/drop_001`, `drop_002`).
- Transition mood: Fast wipe → Scene 3.

### Scene 3 — The Guardrails: Tailored Rewrite & User Approval (7.2s – 11.8s)
Direct recreation of the `RewriteBulletCard` UI. On the left: *"Original — source truth"*; on the right: *"Proposed rewrite"*. The system audits the draft with anti-fabrication guardrail pills: `✓ No invented metrics`, `✓ Verified tech stack`, `✓ ATS keywords matched`. A simulated cursor clicks "Approve", turning the status pill bright green: *"Approved"*.
- Sequential/interaction: Comparison card enters at 7.4s; guardrail badges highlight sequentially at 8.6s, 9.2s; cursor clicks "Approve" button at 10.2s with instant badge state change.
- Audio intent: Trustworthy, human-in-the-loop control.
- Audio-coupled idea: Toggle click on approval button (`ui/click1.ogg`), subtle confirmation chime.
- Transition mood: Smooth scale & crossfade → Scene 4.

### Scene 4 — The Output: Instant In-Browser LaTeX + PDF & BYOK (11.8s – 16.5s)
A split workspace reveals: on the left, an in-browser Monaco LaTeX editor highlighting clean TeX code; on the right, the compiled single-page PDF with crisp typography. A "Compiled" green badge glides in. A quick theme flick demonstrates seamless Dark & Light mode rendering, while a floating badge highlights *"BYOK — Your OpenAI, Claude, or Gemini Key"*.
- Sequential/interaction: Dual pane editor slides in at 12.0s, "Compiled" badge hits at 13.0s, light-mode preview flash at 14.2s transitioning back to sleek dark mode at 15.2s.
- Audio intent: Complete, polished craftsmanship and instant gratification.
- Audio-coupled idea: Subtle compile sound (`interface/switch_001.ogg`), chime on PDF preview.
- Transition mood: Dramatic zoom-fade → Scene 5.

### Scene 5 — Outro & Punchline: The Launch (16.5s – 20.0s)
The background clears into deep obsidian canvas with a warm terracotta radial glow. The MakeMyResume emblem slams in at scale:
**MakeMyResume**
*"Your evidence. Your approval. Your resume."*
Followed by the clean URL:
**makemyresume.tech**
- Sequential/interaction: Logo and title slam in at 16.6s, tagline fades in at 17.2s, website URL lands at 18.0s and holds till 20.0s.
- Audio intent: Unmistakable launch finale, lingering resonance.
- Audio-coupled idea: Logo hit (`impactBell_heavy_000.ogg`), music fade out.

**Music mood for this video:** Upbeat, modern, confident SaaS launch groove.
**Audio summary:** Propulsive corporate-tech beat driving from verified evidence through hybrid matching, human-in-the-loop review, and instant LaTeX compilation to an authoritative brand finish.
