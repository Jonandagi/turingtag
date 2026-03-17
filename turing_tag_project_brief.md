# The Turing Tag — Project Brief
*For use in Claude Cowork. Drop this file in your project folder to provide full context.*

---

## What This Is

The Turing Tag is a voluntary content authorship badge system for LinkedIn and other social platforms. Writers self-declare how their content was created by attaching a badge to their posts. No enforcement, no verification — the system runs entirely on voluntary disclosure and personal integrity.

The name references Alan Turing and *The Imitation Game*. The tagline is:

**"Voluntary Content Authorship Standard"**

---

## The Three Tiers

| Badge | Letter | Label | Meaning |
|-------|--------|-------|---------|
| A | A | AI | 100% AI generated. No human authorship. |
| B | B | Blended | Human written. AI consulted. |
| C | C | Crafted | 100% human written. No AI. |

The letter system runs A/B/C deliberately — A = AI, B = Blended, C = Crafted. The letters map directly to the words.

---

## Design Specifications

**Typography**
- Letter blocks: SF Mono / Menlo (monospace)
- Label text: Helvetica Neue (sans-serif)
- All text bold on top tagline and bottom footer

**Color System**
- Background: #F2F2F2 (light gray)
- A badge block (AI): #4A6580 (slate blue)
- B badge block (Blended): #4D1717 (deep burgundy)
- C badge block (Crafted): #174D38 (forest green)
- Label panels: #FFFFFF (white) with #111111 primary text, #444444 secondary text
- Border: #CBCBCB
- Top tagline color: #0A1F14 (near black)
- Footer color: #444444 (dark gray)

**Badge Structure**
Each badge is a horizontal two-block layout:
- Left block: colored, contains the letter (large, monospace)
- Right block: white, contains the label word and short descriptor
- Border radius: 12px (full badge), 6px (post-size version)
- Border: 3px solid #CBCBCB

**Two sizes:**
1. Full size — for concept graphics and explainer posts
2. Post-size — compact version for attaching to individual posts

**Footer text:** "Voluntary · Self-declared · No enforcement"

---

## Files Already Produced

- `turing_tag_clean.png` — high-res PNG (3600px wide) of the full badge system, no post-size section. Ready for Adobe Express.
- `turing_tag_hires.png` — version with post-size badges included.
- `turing_tag.html` — standalone HTML file, the source for all renders.
- `turing_tag_clean.html` — the current working HTML source file.

---

## Where We Left Off

The next phase is building a **Turing Tag Analyzer App** — a simple tool that helps writers self-declare their badge honestly.

### Concept
The app is a **declaration tool, not a detector.** The philosophy: help writers choose and apply their own badge accurately, rather than catching liars. This keeps it aligned with the voluntary spirit of the system.

### Planned functionality
1. User pastes their post text into the app
2. Claude analyzes the writing and asks a few clarifying questions about the creation process
3. App recommends a badge (A, B, or C) with a brief rationale
4. User can accept or override the recommendation
5. App displays the appropriate Turing Tag badge, ready to use

### Version 1 scope
- Text analysis only (image analysis is harder and less reliable — save for v2)
- Recommendation with rationale, not a hard verdict
- Manual override always available
- Display the badge visually on acceptance

### Design direction
- Match the Turing Tag visual system (same colors, same fonts, same badge design)
- Clean, minimal UI — this is a utility, not a product launch
- Should feel like something that already exists, not a prototype

---

## John's Voice and Context

John Grimshaw is a senior ecommerce professional (20+ years, Amazon/AI/marketing) currently based in Portland and in a job search. He publishes on LinkedIn three times a week under the Grimshaw Report byline. The Turing Tag is a concept he originated and will be proposing publicly on LinkedIn.

Writing voice: confident, wry, direct, contrarian when warranted. No em dashes. No bullet points in prose. No corporate LinkedIn language.

---

## LinkedIn Post (To Be Written)

A Tuesday "Take" post proposing the Turing Tag concept to LinkedIn has not yet been drafted. It should:
- Introduce the concept without over-explaining it
- Take a position (voluntary disclosure is more interesting than enforcement)
- Reference Turing without being precious about it
- Land in 220-250 words
- End with honest tension, not a neat conclusion
- Be drafted in John Hunter voice (Thompson urgency, Twain deadpan, Mencken precision)
