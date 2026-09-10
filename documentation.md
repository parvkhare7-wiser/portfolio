# Portfolio Website — Documentation

## 1. Student Details
- **Name:** Parv Khare
- **Roll No.:** 590027984
- **Program:** B.Tech, Computer Science, UPES
- **Date:** 10 September 2026

## 2. Template / Starting Point
Built from scratch — no third-party template or theme was used. The layout, color system, and copy were designed specifically for this brief with AI assistance (see below), then hand-adjusted.

## 3. AI Tools Used
| Tool | What it was used for |
|---|---|
| Claude (Anthropic, claude.ai) | Generating the initial HTML structure, CSS design system (colors, type, layout), and JavaScript for the mobile nav and contact form; drafting section copy; writing this documentation file |

No other AI tools were used for this build.

## 4. Prompts Used
The assignment brief was pasted directly into Claude, in full, exactly as issued by the instructor (objective, section requirements, download-button spec, hosting steps, and rubric), followed by:

> "This is the project given by my teacher help me and give me a generated website"

Claude then produced the full site (`index.html`, `style.css`, `script.js`) and this documentation file in one pass, using the student's own background (B.Tech CSE at UPES, coursework in networking/AI-ML/digital electronics, an NGO internship, and design work for a family bookshop) as the real content for the About and Projects sections, rather than placeholder text.

## 5. Method / Approach
1. **Planned the content** — identified real, existing work to use as the three project entries instead of generic placeholders (a networking lab report, a business identity project, an NGO internship report).
2. **Designed a visual system** before writing code: a warm paper background, deep green + gold accent (drawn from the student's own bookshop branding), a serif display face (Fraunces) paired with a monospace face for technical labels, and a mono/sans body face — deliberately avoiding generic "AI-template" defaults (no stock gradient hero, no identical rounded SaaS cards).
3. **Built semantic HTML** for header/nav, hero, about, projects, contact, and footer sections as required by the brief.
4. **Wrote CSS** with variables for the color/type system, a responsive grid that collapses from a 3-column project layout and 2-column about/contact layout on desktop to a single column on mobile, and a hamburger menu below 680px.
5. **Added JavaScript** for the mobile navigation toggle and a client-side contact form handler (the form is not yet wired to a backend — see note in the code).
6. **Wrote this documentation file** and wired the footer "Download Documentation" button to it via a simple `<a href="documentation.md" download>` link.
7. **Tested responsiveness** by resizing the viewport from mobile to desktop widths.
8. **Prepared for hosting** on GitHub Pages: `index.html` at the repo root, public repository, Pages source set to the main branch.

## 6. Live Link & Repository
- **Live site:** _[ADD YOUR GITHUB PAGES URL HERE — e.g. https://your-username.github.io/your-repo/]_
- **GitHub repo:** _[ADD YOUR REPO URL HERE — e.g. https://github.com/your-username/your-repo]_

---

### Before you submit — checklist
- [ ] Replace the placeholder email and GitHub/LinkedIn links in the Contact section of `index.html`
- [ ] Replace the SVG avatar in the About section with a real photo (swap the `<svg class="avatar">` block for an `<img src="your-photo.jpg" class="avatar">`)
- [ ] Point each project's "View project →" link at something real (a repo, a PDF, or a Google Drive link)
- [ ] Push all files (`index.html`, `style.css`, `script.js`, `documentation.md`) to a **public** GitHub repo
- [ ] Enable GitHub Pages: Settings → Pages → Source: `main` branch → Save
- [ ] Fill in the live link and repo link at the top of this section, and re-download/re-commit this file
- [ ] Test the live link and the Download Documentation button before submitting to the form
