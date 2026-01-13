# Hanzla Baig — Creative & Classical Portfolio ✨

[![GitHub stars](https://img.shields.io/github/stars/wecoded-dev/hanzlabaig?style=flat-square)](https://github.com/wecoded-dev/hanzlabaig/stargazers) [![GitHub forks](https://img.shields.io/github/forks/wecoded-dev/hanzlabaig?style=flat-square)](https://github.com/wecoded-dev/hanzlabaig/network/members) [![Top Language](https://img.shields.io/github/languages/top/wecoded-dev/hanzlabaig?style=flat-square)](https://github.com/wecoded-dev/hanzlabaig) [![Repo Size](https://img.shields.io/github/repo-size/wecoded-dev/hanzlabaig?style=flat-square)](https://github.com/wecoded-dev/hanzlabaig) [![License](https://img.shields.io/github/license/wecoded-dev/hanzlabaig?style=flat-square)](https://github.com/wecoded-dev/hanzlabaig)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-ready-blue?style=flat-square)](https://wecoded-dev.github.io/hanzlabaig/) [![Last Commit](https://img.shields.io/github/last-commit/wecoded-dev/hanzlabaig?style=flat-square)](https://github.com/wecoded-dev/hanzlabaig/commits/main)

Live demo: https://wecoded-dev.github.io/hanzlabaig/ (GitHub Pages)

---

Table of Contents
- About
- Live Preview
- Badges & GitHub Components
- Features
- Repository structure
- Files of note
- How to preview / run locally
- Deployment (GitHub Pages)
- Contributing
- Accessibility & Performance
- SEO & Best Practices
- License
- Contact
- Acknowledgements
- Roadmap

---

About

Hanzla Baig — Creative & Classical Portfolio is a hand-crafted, static portfolio site built with plain HTML. The repository is 100% HTML and contains a landing page, several article pages, images, and a downloadable PDF guide. The project emphasizes simple, semantic markup and static deployment with GitHub Pages.

Use-cases:
- Personal creative / developer portfolio.
- Learning example for organizing a small static web project.
- Starter template to fork for a simple static site.

Why this repo?
- Minimal dependencies (pure HTML).
- Easy to fork and customize.
- Good starting point for learning static site deployment (GitHub Pages).

Badges & GitHub components

This README includes live badges for: stars, forks, top language, repo size, license, last commit, and GitHub Pages status. Consider adding:
- GitHub Actions status badge (after adding workflows)
- Deployment badges (Netlify, Vercel) if you deploy there
- Release badge (if you add releases)
- Contributors or Sponsor badges if applicable

Example GitHub Actions badge (add after you create a workflow):
[![CI](https://github.com/wecoded-dev/hanzlabaig/actions/workflows/ci.yml/badge.svg)](https://github.com/wecoded-dev/hanzlabaig/actions)

Features

- Pure, static HTML pages — no build step required.
- Several article-style pages and a downloadable PDF guide.
- Static images and a banner for portfolio presentation.
- Clean, semantic markup suitable for accessibility and SEO.
- Ready for GitHub Pages deployment.

Repository structure

Root files (high level):
- index.html — main portfolio landing page
- github.html — GitHub profile / integration demo page
- collaborators.html — collaborators or team showcase page
- newsletter.html — newsletter / signup demo
- Emerging-AI-APIs-Every-Developer-Should-Explore-in-2026.html — article
- 10-Proven-SEO-Hacks to-Skyrocket-Your-Website-Traffic-in-2026.html — article
- from-idea-to-launch-startup-guide-for-developers.html — article
- from-idea-to-launch.pdf — downloadable guide (PDF)
- hanzla-banner.png — banner graphic
- cover.JPG — cover photo
- Purple Modern Meet Our Team Instagram Story_20251211_195042_0000.png — social image

Files of note (quick links)
- [index.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/index.html)
- [github.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/github.html)
- [collaborators.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/collaborators.html)
- [newsletter.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/newsletter.html)
- [Emerging-AI-APIs-Every-Developer-Should-Explore-in-2026.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/Emerging-AI-APIs-Every-Developer-Should-Explore-in-2026.html)
- [10-Proven-SEO-Hacks to-Skyrocket-Your-Website-Traffic-in-2026.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/10-Proven-SEO-Hacks%20to-Skyrocket-Your-Website-Traffic-in-2026.html)
- [from-idea-to-launch-startup-guide-for-developers.html](https://github.com/wecoded-dev/hanzlabaig/blob/main/from-idea-to-launch-startup-guide-for-developers.html)
- [from-idea-to-launch.pdf](https://github.com/wecoded-dev/hanzlabaig/blob/main/from-idea-to-launch.pdf)
- [hanzla-banner.png](https://github.com/wecoded-dev/hanzlabaig/blob/main/hanzla-banner.png)
- [cover.JPG](https://github.com/wecoded-dev/hanzlabaig/blob/main/cover.JPG)
- [Purple Modern Meet Our Team Instagram Story_20251211_195042_0000.png](https://github.com/wecoded-dev/hanzlabaig/blob/main/Purple%20Modern%20Meet%20Our%20Team%20Instagram%20Story_20251211_195042_0000.png)

How to preview / run locally

Because this project is static HTML, previewing locally is straightforward:

1. Clone the repository:
   git clone https://github.com/wecoded-dev/hanzlabaig.git

2. Open index.html in your browser:
   cd hanzlabaig
   open index.html   # macOS (or double-click index.html in your file manager)

Recommended: run a local static server for consistent relative path behaviour.

- Python 3:
  python3 -m http.server 8000
  Open http://localhost:8000

- Node (http-server):
  npx http-server -p 8000
  Open http://localhost:8000

Deployment (GitHub Pages)

This repo is ready for GitHub Pages. To publish:
1. Navigate to repository Settings → Pages.
2. Set Source to branch `main` and folder `/ (root)`.
3. Save. Site should be available at:
   https://wecoded-dev.github.io/hanzlabaig/

If you add a build step or move files to a docs/ folder, change the Pages source accordingly.

Contributing

Contributions are welcome. Follow the typical fork → branch → PR workflow:

- Fork the repo.
- Create a branch: git checkout -b feature/my-change
- Commit and push: git push origin feature/my-change
- Open a Pull Request describing your changes.

Guidelines:
- Keep PRs focused and small.
- Use semantic HTML.
- Optimize images before adding (compress JPEG/PNG or use WebP).
- If you add CSS/JS, keep them minimal and well-documented.

Accessibility & Performance

- Use semantic elements and descriptive alt attributes for images.
- Reduce image file sizes and serve appropriately-sized assets.
- Avoid relying on JS for core content (progressive enhancement).
- Add meta viewport and language attributes in HTML for better UX and SEO.

SEO & Best Practices

- Add meaningful titles, meta descriptions, and Open Graph (OG) tags for better sharing.
- Use structured headings (H1 → H2 → H3) and semantic HTML.
- Use canonical URLs if you serve the same content at multiple URLs.
- Consider adding sitemap.xml and robots.txt for search engines.

License

No LICENSE file is included by default. If you want to license this repo, add a LICENSE file. Common choices:
- MIT — permissive and common for code
- CC BY-SA — for content/design share-alike
Add your chosen license file at the repo root.

Contact

- GitHub: [@wecoded-dev](https://github.com/wecoded-dev) (repo owner)
- Email: add-your-email@example.com (replace with your contact if you wish)

Acknowledgements

Thanks to the open-source community and tooling that make static site creation and deployment straightforward.

Roadmap & Next steps (suggested)

- Add small CSS stylesheet or theme toggle (light/dark).
- Add GitHub Actions to run linters or preview deploys (Netlify/Pages previews).
- Add a LICENSE and CONTRIBUTING.md + CODE_OF_CONDUCT.md.
- Consider a small JS enhancement for dynamic features while maintaining progressive enhancement.

Issue reporting & support

- Open issues for suggestions, bugs, or feature requests on the repository Issues page.
- For urgent changes, open a PR with a short description of the fix.

---

If you'd like, I can commit this README.md to your repository. Reply with:
- "Yes, commit" — to commit to `main` with message: "Update README.md — project overview and instructions"
- "Yes, commit to BRANCH_NAME" — to commit to a branch of your choosing

If you want edits to the README before committing, tell me what to change and I'll update it.
