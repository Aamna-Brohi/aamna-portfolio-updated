# Aamna Brohi — Portfolio

High-craft, mobile-first personal portfolio website of **Aamna Brohi**, AI Developer and Computer Science (AI) student at Sukkur IBA University.

> **"Where there's a gap, I build."**

---

## 🌟 Overview & Architecture

- **`index.html`** — Single-file responsive architecture with clean modular CSS and vanilla JS modules.
- **`assets/images/`** — High-fidelity WebP and JPEG photography and project previews.
- **`Aamna_Brohi_CV.pdf`** — ATS-friendly CV linked across navigation, hero, and dedicated download cards.

### Key Architectural Highlights
- **Mobile-First Layout (375px baseline)**: Fully optimized for 375px–430px viewports (iPhone SE through Pro Max) and seamlessly scales to 4K displays.
- **Zero Horizontal Overflow**: Robust container sizing preventing layout shifts and horizontal scroll jitter.
- **Fluid Typography**: Calculated `clamp()` scalers for headings and body copy using **Fraunces** (editorial serif) and **DM Sans** (clean geometric sans).
- **Accessibility & Touch Standards**: Every interactive element satisfies the WCAG `>=44x44px` tap target guideline.
- **Dark/Light Theme Switcher**: Instant theme toggle with `localStorage` persistence and automatic `prefers-color-scheme` support.
- **Interactive Workbench**: Master-detail project showcase on desktop transitioning to touch-optimized tabbed panels on mobile.
- **Direct Action Paths**: One-click email copy with animated toast feedback, direct CV downloads, and verified credential links.

---

## 📂 Sections

1. **Hero**: Value proposition, availability badge, motto, action CTAs, and continuous capabilities marquee.
2. **About ("The Story")**: Narrative from Jacobabad to Sukkur IBA, plus profile factsheet card.
3. **Projects ("The Work")**:
   - **UniPath AI**: RAG-based university guidance system for Pakistani Intermediate students.
   - **Ilmora Labs**: B2B SaaS for MDCAT preparation academies with live dashboard preview and team gallery.
   - **GenAI in Higher Education**: Proposed 10-country cross-national research study.
   - **Dukhtar Studio**: Tech-enabled women empowerment ecosystem across Sindh.
4. **Experience ("The Journey")**: Interactive milestone cards covering Ilmora Labs, FlyRank AI, Strategic Media Journey, DataCrumbs, and RA MAOYI LLC.
5. **Certifications ("The Credentials")**: Verified Coursera & Google credentials (IT Automation, BI, AI Essentials, Prompting) with direct verification links.
6. **Leadership & Community ("Beyond Code")**: Fellowship and mentorship showcases (Qimam Fellowship, TCF Alumni Ambassador, NGLI 2026, NYPF, ICBEM, Skills4U, STHP Award, Smile of Tomorrow, Tech Club).
7. **Contact & CV Hub**: Direct mail, clipboard copy toast, LinkedIn, GitHub, and ATS-friendly CV download / browser view.

---

## 🚀 Deployment

Static site hosted on GitHub Pages:
- Repository: Settings → Pages → Build and deployment → Branch: `main` / `/ (root)`.
- Updates publish automatically upon push.
