# Tomer Goldstein | Work in Motion (2026)

An original bilingual executive portfolio and ATS-friendly résumé microsite.

## What is included

- `index.html` — portfolio home, seven selectable case studies with original motion artwork.
- `resume.html` — complete, readable bilingual résumé page, with EN/LTR and עברית/RTL switching.
- `portfolio-data.js` — editable text and factual claims for portfolio cards in both languages.
- `cv-data.js` — approved detailed job descriptions, cases, skills and education from the previous site.
- `site.js`, `resume.js`, `styles.css`, `favicon.svg` — interface, navigation and motion.
- `media/digital_loop.mp4` and `media/ai_loop.mp4` — real silent 8-second H.264 MP4 loops (10 fps, with first-frame PNG posters).
- Five additional CSS motion compositions — campaigns, production, product marketing, eCommerce and analytics. These are live code animations, not MP4 files.
- `downloads/` — four actual ATS-style PDF and DOCX files, Hebrew and English.

## Open locally

Extract the ZIP and open `index.html`. No npm, build step, account or backend is required. Files must remain in the same relative folders.

## Publish on GitHub Pages

Upload the **contents** of this directory to the root of the GitHub Pages repository, maintaining `media/` and `downloads/`. Configure Settings → Pages → Deploy from a branch → main / (root). This ZIP is for testing and upload; no live deployment has been performed.

## Update content

- Change project cards, case studies, translations and source attribution in `portfolio-data.js`.
- Change detailed résumé text in `cv-data.js`.
- To update downloadable résumés, replace the corresponding PDF and DOCX files in `downloads/` with properly exported documents. The website never prints the browser page in place of the résumé files.
- Motion compositions are generated in `site.js` (sceneMarkup) and animated through `styles.css`. To replace a rendered video, update the MP4 and poster inside `media/`.

## Interaction & accessibility

- Desktop horizontal project rail; straightforward vertical project cards on mobile.
- Native dialog project detail views (Esc to close), click-outside close, arrow-key project navigation.
- Only the most visible scene runs. MP4 media is muted, loops and plays inline; off-screen media is paused. On mobile, responsive code-based visuals replace videos to avoid cropping important content.
- `prefers-reduced-motion` disables motion and video autoplay. Text remains visible.
- Keyboard focus states, semantic content, labels, native dialogs, EN/LTR and עברית/RTL.

## Provenance and careful claims

- Smith Tools Group internal 2024–2026 summary supports 14.8M TikTok views, 3.5M YouTube views, 2.5M Facebook views, 1,300% Instagram view growth, content operations, partnerships, product development responsibilities.
- Previous approved résumé supports employment history and eCommerce claims (including Meprolight Amazon 400-SKU setup).
- Confirmed conversation details support direct management of one creative production employee and two business-focused Custom GPT solutions.
- The motion scenes are **conceptual graphic illustrations**, not reproductions or documentary footage of actual campaigns, clients, products, events or dashboards. Where a claim is shown, its scope is explained in the relevant case study.
- External APIs, self-hosted AI agents and unverified financial results are **not** claimed.

## Files reviewed

Existing approved site ZIP and its four exported résumés; updated user-uploaded Hebrew PDF (`Tomer_Goldstein_ATS_HE(1).pdf`); Hebrew and English historical CVs; internal Smith Tools summary PDF; user-approved copy, dates and responsibilities from the chat.

## Browser QA

The implementation was tested locally by injecting production HTML/CSS/JS into a headless Chromium page, because direct browser navigation is restricted in this environment. This covered all seven project dialogs, close/next controls, RTL, both résumé languages, link/file existence, mobile layout and reduced-motion behavior. Videos were verified using ffprobe and frame comparison. Browser playback after upload to a public hosting origin should still be checked by the owner.
