# Christian Al-Shatla — Modern Developer Portfolio

An editable, locally self-contained **HTML + CSS only** portfolio prototype inspired by the selected dark futuristic laptop dashboard reference. No frameworks, JavaScript, CDN, remote fonts or runtime dependencies.

## Open the prototype

1. Extract the entire ZIP, keeping the `assets` folder in place.
2. Open `index.html` in Chrome, Edge or Firefox; VS Code Live Server also works.
3. Navigate using the top navigation. Sections use standard semantic HTML anchors.
4. `style.css` contains ALL real, fully editable layout and animation rules. Nothing needs building, compiling, or a CSS framework.
5. For assignment requirements and outstanding submissions, see `ASSIGNMENT_COMPLIANCE.md`.

## What is included

- Home: name, professional headline, workstation hero artwork, introduction and links.
- Dashboard: three featured projects, technology logo tiles and experience summary.
- About: professional background, verifiable stats and included CV download.
- Projects: **nine user-selected projects** including AlphaGYM, VentaFit, PalDrive, K–12 School Management, Instruments Online Market, Abu 3meer Fan League, CR7 Mobile App, NOVA and Python AI Agent.
- Skills: languages, frameworks, databases and development tools, using local SVG logos.
- Experience: Bethlehem University, 204-hour FTS internship, Boot.dev and Eng4You training.
- Contact: working email and GitHub links; LinkedIn/Instagram identified for later URL completion.
- Footer and mobile responsive presentation.

## Important factual accuracy notes

- AlphaGYM: 300+ users and Hikvision access control; user-provided resume supports this.
- VentaFit is in development; do not present as released.
- PalDrive includes a planned, not guaranteed, FastAPI/PostGIS back end.
- Abu 3meer Fan League technology choices come from the proposal and should be described as **proposed**, not deployed.
- NOVA project specifications could not be confirmed; explicitly left pending.
- Individual project visuals are custom abstract **SVG illustrations** rather than fabricated product screenshots. Replace with actual screenshots when available.
- FTS internship **is not presented as Boot.dev work**.
- There are no invented LinkedIn/Instagram URLs, freelance employers, or project deployment links.

## Image quality notes

The main laptop artwork uses a **3840 × 2160 pixel WebP export** derived by upscaling and carefully cropping the previously approved AI concept. Its **original creative source was only 1672 × 941**, so it is NOT native optically detailed 4K. For honest presentation, this distinction is recorded here; 4K output dimensions do not recover lost native detail. The smaller original crop is also included so the browser can choose a lighter asset later if desired.

All icons and project graphics are local, infinitely scalable **SVG vectors**, so their edges remain sharp at any display resolution. Text, buttons and UI are rendered with real HTML/CSS and do not depend on embedded image text.

## Assignment checklist

✓ Semantic header/nav/main/section/footer
✓ Hero name/title; About; Skills; at least two Projects; Contact; Footer
✓ CSS styling, hover effects, Flexbox and Grid, mobile media queries
✓ Standalone site suitable for GitHub Pages (publish manually when approved)
✓ ZIP files can be prepared for eClass; GitHub and live links require deployment

## Before publishing

- Review/update all project descriptions to reflect latest verified project state.
- Add accurate LinkedIn and Instagram URLs if desired; their blocks currently say URL pending.
- Review your CV before publicly publishing: it contains real personal contact information.
- Publish to your own GitHub repository and enable GitHub Pages, then submit both URLs.

## File layout

- `index.html` — entire site content, editable HTML.
- `style.css` — theme, transitions, sections, responsive layout.
- `assets/hero/` — approved laptop concept art crop and enlarged export.
- `assets/projects/` — nine custom scalable SVG illustrations.
- `assets/logos/` — locally hosted technology logos (including some stylized representations).
- `assets/Christian_Al_Shatla_Updated_Resume.pdf` — the user's previously supplied CV.

All artistic illustrations and logos are independent decorative assets; brand names belong to their respective owners. Third-party assets were sourced from the earlier conversation's portfolio asset packs and the user's own reference image.

## Motion and transitions (CSS only)

- **Opening scene**: a branded ~2-second entrance with a lit logo, name, grid backdrop and a decorative progress line; it is NOT a network-loading progress indicator.
- **Hero entrance**: left-side text arrives in sequence, artwork unveils from the side, and the illustration has extremely slow motion.
- **Interactive navigation**: links animate on hover/focus; the selected anchor is highlighted with CSS `:has()`.
- **Buttons**: moving highlight, glow, lift on hover and soft press feedback.
- **Cards**: dashboard/project/experience cards have lift, border illumination and a restrained shine pass.
- **Skills**: each tile/technology icon lifts and glows on hover.
- **Scroll**: a slim reading-progress bar uses CSS scroll timelines; supported browsers also reveal content on entry.
- **Accessibility**: users who request reduced motion get a static version with the intro hidden and effects disabled.

To edit these, open the **bottom portion of `style.css`**, under
`INTERACTION & MOTION DESIGN — PURE CSS`. All CSS is readable and grouped by purpose.
Change the `opening-finish 1.95s` time to shorten/lengthen the introduction.
The decorative opening runs each time the page is freshly loaded, not each time a section link is clicked.

### Browser requirements
Recent Chrome/Edge/Firefox should render the core design and hover animations. CSS scroll timelines and `:has()` are progressive enhancements; the content and ordinary navigation work without them.

### Image integrity
The hero export is dimensionally 3840 × 2160, but is NOT native 4K-detail imagery; it is an upscale of the approved 1672 × 941 visual. Logos/project illustrations are scalable local SVGs. No real app screenshots have been fabricated.

## October 2026 customization update

- `style.css` is fully editable and contains the original CSS animations plus the new LinkedIn-inspired Experience feed, project marks, Skills grid/lobby switch, and a handwritten SVG signature.
- New `assets/signature-christian.svg` signs the footer, with the copyright line **© 2026 Christian Al-Shatla. All rights reserved.**
- The Skills section has a **Grid / Lobby view** switch implemented using native radio inputs and CSS selectors. No JavaScript is required.
- Real uploaded `assets/projects/alphagym-original.jpg` is used for AlphaGYM; other project identity marks are *original illustrations*, not independently confirmed official project logos.
- Bethlehem University and Foothill Technology Solutions use their confirmed public images when online and a local illustrated fallback when offline. Eng4You's local E4Y graphic is a *custom monogram*, not an official Eng4You asset. See `ASSET_SOURCES.md` for exact URLs and limitations.
- Four detailed Experience entries: Bethlehem University, 204-hour FTS internship, Eng4You backend training, Boot.dev coursework.
- All nine projects retain their names; descriptions were improved without making up launch dates or software features for projects lacking verified specifications.
- GitHub and email are usable; LinkedIn/Instagram still have visible placeholders because their personal URLs have not been provided.
- Browser preview caveat: an embedded-page Chromium test succeeded on 1512px desktop and 390px mobile widths, including both Skills modes and the signature. The browser blocked localhost/file navigation, so normal Live Server URL testing should still be done after extraction.
