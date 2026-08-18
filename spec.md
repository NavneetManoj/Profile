# Portfolio Website — Spec

## Goal
Build a personal portfolio website generated from my resume content, with a
distinctive visual style and typography (see "Style & Font" below).

## Constraints
- Plain HTML/CSS/JS only — no framework, no build step, no bundler.
- Must run by opening index.html directly or via any static file server —
  no backend/server-side logic.
- Fully responsive: mobile, tablet, desktop.
- Semantic, accessible HTML (proper landmarks, alt text, sufficient color
  contrast, keyboard-navigable).
- No fabricated content — every fact on the page must trace back to the
  resume.
- Style & Font: 
  Professional, Light contrast, Minimalistic

## Input
- **Resume:** `./resume.<ext>` — TODO: drop resume file into this folder
  (pdf/docx/md/txt). Source of truth for all content: name, contact info,
  summary, work experience, education, skills, projects.
- **Style/font prescription:** TODO — user to add specifics under
  "Style & Font" above (or as a separate `style-guide.md`).
- **Assets (optional):** headshot/profile photo, project screenshots,
  resume PDF for download link — TODO if desired.

## Output
Static site in this folder:
- `index.html` — page structure/content
- `styles.css` — visual styling implementing the prescribed style/font
- `script.js` — any interactivity (nav toggle, smooth scroll, etc.), only
  if needed
- Sections: Hero/Intro, About/Summary, Experience, Education, Skills,
  Projects (if applicable), Contact
- Deployable as-is to any static host (GitHub Pages, Netlify, Vercel
  static, etc.) with no build step

## Acceptance Criteria
- [ ] All content on the page is traceable to the resume — nothing invented
- [ ] Style & Font section (once filled in) is faithfully implemented
- [ ] Layout is responsive with no horizontal scroll/overflow at common
      breakpoints (mobile ~375px, tablet ~768px, desktop ~1440px)
- [ ] Page loads with zero console errors/warnings
- [ ] Semantic HTML + accessibility basics pass (landmarks, alt text,
      contrast, focus states)
- [ ] Opens correctly via `file://` and via a plain static server, no
      build step required
- [ ] Contact info / links (email, LinkedIn, GitHub, etc.) are present and
      correct per resume
 Optimised for phone and laptop

    my github credentials and iisc thesis on heat exchangers and ai to be added

Transcript of this session is also to be made


   