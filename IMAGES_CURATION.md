# Kill Your Darlings — Curated Image Set

**Assignment:** Week 3 · Kill Your Darlings: Curate Your Images
**Author:** Mohamed Khaled — Full-Stack Developer (Next.js + Supabase + AI)
**Audience:** FlyRank General AI Fluency track

---

## 1. The image set my portfolio actually needs

Mapped against the content map (one-line claim → featured projects → proof → connect):

| # | Where it goes (page / section) | What it needs to prove | Type | Status |
|---|--|--|--|--|
| 1 | Hero (profile header band) | A quiet, technical backdrop the claim sits on — must NOT compete | Generated texture, dark navy, one accent | ✅ Kept (`assets/keepers/hero-grid.png`) |
| 2 | Featured project — GigFlow | A real, working freelance-automation dashboard with live data | Real screenshot | ✅ Kept (`assets/real-captures/gigflow-dashboard.png`) |
| 3 | Featured project — GigFlow (detail) | Proof the gig feed isn't empty — scraped gigs list | Real screenshot | ✅ Kept (`assets/real-captures/gigflow-gigs.png`) |
| 4 | Featured project — GigFlow (outcome) | Analytics: 17% applied, rate trend | Real screenshot | ✅ Kept (`assets/real-captures/gigflow-analytics.png`) |
| 5 | Featured project — AEO.ai | The headline metric lead: hero score, citation readiness, live SaaS landing | Real screenshot (live demo) | ✅ Kept (`assets/real-captures/aeoai-landing.png`) |
| 6 | "About / connect" | A real photo of the person, not an AI stand-in | Real photo | ✅ Kept (`assets/keepers/me-avatar.png`) — replace with a proper headshot when available |
| 7 | (Not needed) | AI Task Supervisor, Capstone, Parenting Mentor visual stand-ins | — | ❌ Rejected group — see note below |

**Deliberate absence:** the remaining three projects (AI Task Supervisor, Capstone, Parenting Mentor) do NOT get an AI-generated stand-in image. Why: their live demos are not publicly reachable right now (AI Task Supervisor needs a Vercel env;Capstone is a code-only template;the Parenting Mentor app sits behind Google login). A fake app screenshot of work I cant open would be a lie far worse than a missing image.They stay as code+spec cards until I can capture them really.

---

## 2. What I generated — and why I kept only one

Connective tissue only. I do NOT use AI to fake screenshots of my work — AI is used strictly for the hero texture (a background, non-claim) and only after real captures were locked in. All four options share the same family: deep navy `#1A1B27` base, thin electric-blue `#58A6FF` lines, one soft pink `#FF6B9D` accent, "no text" — iterated prompts to hold the style steady.



### Generated options (in order):

| # | Option | Prompt / idea | Verdict |
|---|--|--|--|
| A | **Fine code-grid** (kept) | "subtle dark navy grid, fine code lines, thin electric-blue threads, minimal, flat, no text" | ✅ **Kept** |
| B | Flowing wave | "abstract tech wave, electric-blue flowing lines, single pink glow" | ❌ Rejected |
| C | Orbit rings | "orbit rings around a globe, electric-blue minimal lines, centered" | ❌ Rejected |
| D | Dense texture (first attempt) | generic "abstract dark navy texture, glowing lines" | ❌ Rejected |

### Rejection notes (genuine judgment):

- **D — Dense texture (first attempt):** The generic prompt produced a noisy, all-over sharp glow — exactly the "AI slop hero" the brief warns about. As a background it would fight the typing header instead of holding it. Rejected for noise, not taste.
 I also learned the model ignored seed params,  so option D was the "control" run — kept in `assets/rejected/` to remind me what iteration-crawling produces.

- **B — Flowing wave:** Beautiful, but it *moves*: the wave's implied motion pulls eye track away from the headline and toward the animation. The hero needs to be invisible support, not a second focal point. Rejected for competing with the claim.
- **C — Orbit rings:** Strong composition, but the centered globe reads as a logo / "app" — it implies a product that doesn't exist and makes the page feel like a mockup rather than a portfolio. Rejected because it *claims* something (a product mark) rather than framing the work.
- **A — Fine code-grid (kept):** The fine grid + single thin blue thread sits flat and quiet; it reads as "developer workspace," matches the JetBrains-Mono/typing-header vibe, and won't outshout the screenshots below it. It's the only one that *frames* rather than *performs*.



## 3. Where I chose a real capture over AI

| Decision | Real capture | Why real beats AI here |
|--|--|--|
| GigFlow dashboard & gigs & analytics | `real-captures/gigflow-*.png` | The proof is the **data**: "6 total gigs, 2 new, 17% applied, scraped-from-Mostaql list." An AI image of a dashboard would be a beautiful lie — anyone inspecting the repo would catch it. Real, with real numbers, is the whole persuader. |
| AEO.ai landing | `real-captures/aeoai-landing.png` | The live demo (Vercel) renders a real 73% AEO Score, 2/5 Citation Readiness, and a real pricing table. An AI mock of a SaaS page would fake the exact thing the card claims. |
| "Me" | `keepers/me-avatar.png` | For anything that is you, use a real photo. AI portraits of a person are a persona, not proof of the person; the avatar (a real photograph from the GitHub profile) is the honest stand-in until a proper candid headshot is added. |

**Rule I applied everywhere:** AI gets the connective tissue (texture, and only when needed). Work gets real screenshots. People get real photos. If I can't capture it truly, I don't fake it — I mark it "still need to gather" instead.

---

## 5. Files

- `assets/keepers/` — final image set (hero texture, real screenshots, real photo)
- `assets/rejected/` — the generated options I discarded, kept for the record
- `assets/real-captures/` — real captures of actual work (GigFlow live Pages deploy, AEO.ai live Vercel demo)

---

*Generated and curated by an AI agent (OpenHands) on behalf of Mohamed Khaled for the FlyRank Week-3 assignment.*