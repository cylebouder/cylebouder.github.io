# Portfolio Site — Progress Notes

## Done

### Design & Structure
- Applied full design system (Garden theme): DM Serif Display + DM Sans, warm cream background, leaf-green accent, OKLCH color tokens
- Floating pill nav with active section highlighting and scroll shadow
- Scroll reveal animations on sections
- Responsive layout down to 320px
- Split site into two pages:
  - **Homepage** (`index.html`) — minimal: hero, about, contact only
  - **Projects** (`projects.html`) — dedicated page with full timeline

### Content
- Hero tagline: "Rising senior at Blair's STEM magnet program. I build things with code."
- About section with skill tags: Python, JavaScript, HTML/CSS, Java
- Projects timeline restructured into two-column layout (year label left, cards right)
- Individual project cards with descriptions and tech tags:
  - **2020** — Blackjack, Hangman, Prime Factorization (separate cards)
  - **2025** — Multi-Model Image Classifier (ResNet), Poker Hand Probability Calculator
  - **2026** — Nash Equilibrium Simulator, VR Panorama Generator, Strategy Backtester, Pokémon Card Browser

### ResNet Classifier (fully deployed)
- Rewrote Flask app as a Streamlit app
- Deployed to Streamlit Community Cloud: https://resnet-classifier-demo.streamlit.app/
- Features: three models (ResNet-50 general, dog breeds, food), file upload + live webcam in each tab
- GitHub repo: https://github.com/cylebouder/resnet-classifier
- "Try it live →" link on the project card

## Deliberately left out for now
- Mr. Ross startup internship project — pending confirmation on what can be shared (possible NDA/employer restrictions)
- Uncle Nigel project — no description yet
- Morgan State ML models — not finished yet
- Capture-the-flag online game (repo exists: `capture-the-flag-online`) — not added yet

## To do next

### Projects to add
- [ ] **Poker calculator** — card in place, but no GitHub link yet (class org repo, not on personal GitHub)
- [ ] **Nash Equilibrium Simulator** — card in place, no GitHub link (private repo)
- [ ] **VR Panorama Generator** — in progress, repo exists (`vr-panorama`), add link when ready
- [ ] **Strategy Backtester** — no files reviewed yet, add description and tech tags
- [ ] **Pokémon Card Browser** — in progress, no files reviewed yet
- [ ] **Capture-the-flag online** — repo exists, not on portfolio at all yet
- [ ] **Mr. Ross / Uncle Nigel / Morgan State** — add when cleared up and finished

### Site improvements
- [ ] Add GitHub repo links to project cards where repos are public
- [ ] Decide whether to add more skills to the About section (SQL, Git, PyTorch, C/C++)
- [ ] Consider adding a profile photo to the homepage hero
- [ ] Consider a dark mode toggle
