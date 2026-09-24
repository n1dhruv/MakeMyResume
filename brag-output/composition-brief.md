# Hyperframes Composition Brief: MakeMyResume

## Objective
Create a confident, high-energy SaaS launch video for MakeMyResume, showcasing how it turns a user's verified Skill Bank into tailored, ATS-optimized, single-page LaTeX resumes without hallucinations.

## Output
- Composition directory: `brag-output/composition/`
- Rendered video: `brag-output/brag.mp4`
- Poster image: `brag-output/brag.jpg`
- Format: landscape — 1920x1080
- Duration: 20.0 seconds

## Source Material
- Project root: `/home/dhruv/Project/MakeMyResume`
- Primary files read: `README.md`, `PRODUCT.md`, `client/src/app/page.tsx`, `client/src/app/globals.css`, `client/src/components/rewrite/RewriteBulletCard.tsx`, `client/src/components/ModelProviderPicker.tsx`, `client/src/app/(app)/editor/page.tsx`, `client/src/lib/demo.ts`.
- Product name: MakeMyResume
- Tagline: "Your evidence. Your approval. Your resume."
- Hero claim: "Build from what you've done. Tailor for where you're going."
- Key UI moments to recreate:
  1. Skill Bank cards with verified tags and metrics (`18 → 6 min`, `2.4M events/mo`).
  2. Hybrid vector search & reranking pipeline (Pinecone 2048-d dense + sparse BM25 + FlashRank reranker).
  3. Side-by-side Rewrite Bullet Card with fabrication guardrails and user approval.
  4. In-browser LaTeX editor + live compiled PDF preview with dark/light mode toggle and BYOK badge.
  5. The official logo emblem `[ R ]`, brand name, tagline, and `makemyresume.tech` URL.

## Creative Direction
- Tone preset: `polished` (enhanced with fast-paced, modern SaaS launch reel energy)
- Creative direction: Confident SaaS launch reel with product-demo authenticity and elegant editorial typography.
- Angle: Anti-hallucination resume tailoring. Real career evidence stored in a structured Skill Bank, hybrid search and reranking to match job descriptions, auditable fabrication guardrails, and instant in-browser LaTeX PDF compilation with full BYOK privacy.
- Avoid:
  - Generic SaaS buzzwords
  - Abstract spinning 3D shapes or filler geometric art
  - Inventing random UI styling that ignores the site's actual design tokens

## Visual Identity
- Dark Canvas background: `#0d0c0b` / `oklch(14% .01 55)`
- Dark Surface card: `#181715` / `oklch(17.5% .012 55)`
- Light Mode accent surface: `#f8f7f4` / `oklch(96% .015 78)`
- Primary text (Ink): `#f4f2ee`
- Muted text: `#9b9890`
- Brand Accent: `#c84b31` (Terracotta rust / warm coral)
- Accent soft: `rgba(200, 75, 49, 0.15)`
- Success green: `#22c55e`
- Warning gold: `#eab308`
- Border lines: `#2d2b27`
- Display font: `Newsreader`, `Georgia`, serif
- Body font: `Instrument Sans`, `Avenir Next`, system-ui, sans-serif
- Mono font: `IBM Plex Mono`, monospace

## Storyboard Summary
1. **Scene 1 (0.0s – 3.2s) — Skill Bank Foundation**: Emblem `[ R ]` intro + "Build from what you've done." + 2 structured Skill Bank evidence cards with verified metrics.
2. **Scene 2 (3.2s – 7.2s) — Hybrid Retrieval**: Job Description entered ("Fathom · Senior Product Engineer") + Pinecone dense (2048-d) + sparse BM25 search + reranking → top candidates matched at 94% confidence.
3. **Scene 3 (7.2s – 11.8s) — Fabrication Guardrails**: Side-by-side comparison ("Original — source truth" vs "Proposed rewrite") + guardrail checks (`No invented metrics`, `Verified tech`) + cursor hits "Approve" with instant green badge change.
4. **Scene 4 (11.8s – 16.5s) — In-Browser LaTeX + PDF**: Dual split editor (TeX code on left, compiled PDF on right) + "Compiled" badge + dark/light mode toggle + "BYOK: OpenAI · Claude · Gemini" privacy badge.
5. **Scene 5 (16.5s – 20.0s) — Outro & Brand**: Logo emblem `[ R ]` + MakeMyResume + "Your evidence. Your approval. Your resume." + **makemyresume.tech**.

## Audio
- Audio role: Confident, modern SaaS launch bed with crisp UI precision and motion-matched interaction.
- Music: `happy-beats-business-moves-vol-12-by-ende-dot-app.mp3`
- Music treatment: Bed on track 10, volume 0.32, fade-out 1.5s ending at 20.0s.
- Music cue guidance: Preset cues at 8.74s, 10.93s, 13.11s, 17.47s.
- Audio-coupled moments:
  - Skill Bank cards: card slide/place SFX (`assets/sfx/casino/card-slide-2.ogg`, `card-place-1.ogg`)
  - Search trigger: interface click (`assets/sfx/interface/click_002.ogg`)
  - Guardrail pills & results: interface drop (`assets/sfx/interface/drop_001.ogg`, `drop_002.ogg`)
  - Approval checkmark: clean button click (`assets/sfx/ui/click1.ogg`)
  - PDF compile & mode switch: toggle switch (`assets/sfx/interface/switch_001.ogg`)
  - Outro logo reveal: soft impact bell (`assets/sfx/impact/impactBell_heavy_000.ogg`)
- SFX tracks: Track indices 11 through 20.

## Hyperframes Instructions
- Implement in `brag-output/composition/` using standard Hyperframes markup (`index.html`, `hyperframes.json`, `package.json`).
- Ensure all text elements are readable with settled hold periods.
- Keep total duration at exactly 20.0 seconds.
- Run `npx hyperframes check` and resolve all audit checks prior to render.
- Render final video to `../brag.mp4`.
