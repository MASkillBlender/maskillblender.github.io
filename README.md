<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset=".github/assets/banner-light.svg">
  <img alt="MASkillBlender" src=".github/assets/banner-light.svg" width="530">
</picture>

<h1>🤖 MASkillBlender Project Page</h1>

<p><b>Project page for "MASkillBlender: Decentralized Whole-Body Coordination for Multi-Humanoid Loco-Manipulation via Skill Blending"</b></p>

<p>
  <a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/license-CC--BY--SA--4.0-blue"></a>
  <a href="https://github.com/MASkillBlender/maskillblender.github.io/commits/main"><img alt="Last commit" src="https://img.shields.io/github/last-commit/MASkillBlender/maskillblender.github.io"></a>
  <a href="https://github.com/MASkillBlender/maskillblender.github.io/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/MASkillBlender/maskillblender.github.io?style=flat"></a>
  <a href="https://agents.md"><img alt="AGENTS.md" src="https://img.shields.io/badge/AGENTS.md-ready-24292f"></a>
  <a href="https://agentskills.io"><img alt="Agent Skills" src="https://img.shields.io/badge/Agent%20Skills-open%20format-8250df"></a>
</p>

</div>

Static source of the MASkillBlender project page, served by GitHub Pages at
[maskillblender.github.io](https://maskillblender.github.io/). The page
presents the paper's abstract, the primitive skill library, and videos of
primitive skills, multi-humanoid coordination tasks, a TeamHOI baseline
comparison, box exchange, long-horizon coordination, and Sim2Sim transfer on
H1 and G1 humanoids. It is plain HTML, CSS, and JavaScript with vendored
libraries, so there is nothing to build.

## ✨ Highlights

- 🌐 **No build step**: GitHub Pages serves the tree as is (`.nojekyll`).
- 🎬 **Media first**: figures in `assets/pictures/`, skill and task videos in `assets/videos/`.
- 📦 **Self-contained**: Bulma, Font Awesome, and Academicons are vendored under `static/`, with no CDN calls.
- 🕶️ **Anonymous**: no author names, affiliations, or personal links anywhere in the repository.

## 🚀 Quick Start

> [!NOTE]
> Any static file server works; the command below needs only Python 3.

```bash
python3 -m http.server 8000
# then open http://127.0.0.1:8000/
```

<details>
<summary>Other preview options</summary>

Open the folder in VS Code and use the Live Server extension: right-click
`index.html`, then **Open with Live Server**.

</details>

## 📂 Project Structure

| Path | Purpose |
|---|---|
| `index.html` | The whole page |
| `static/css/index.css`, `static/js/index.js` | The page's own style and script |
| `static/css`, `static/js`, `static/webfonts`, `static/fonts` | Vendored Bulma, Font Awesome, Academicons |
| `static/third_party_licenses/` | Licenses of the vendored libraries |
| `assets/pictures/` | Teaser image and primitive skill library figure |
| `assets/videos/` | Videos, one folder per page section |
| `AGENTS.md`, `.agents/skills/` | Instructions and skills for AI coding agents |
| `.gitmessage`, `.gitattributes`, `.gitignore` | Commit format, line endings, ignore rules |

## 📚 Documentation

| Topic | Where |
|---|---|
| Agent instructions and repository conventions | [`AGENTS.md`](AGENTS.md) |
| Commit format, workflow, branch naming | [`.gitmessage`](.gitmessage) |
| Each skill's procedure | [`.agents/skills/<name>/SKILL.md`](.agents/skills) |

## 🤝 Contributing

Corrections are welcome. Read the [Contributing guide](CONTRIBUTING.md) first.

## 🔗 Resources

- [Bulma](https://bulma.io/): the CSS framework the page is built on.
- [Font Awesome](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/): the icon fonts.
- [GitHub Pages](https://docs.github.com/en/pages): the hosting service.

## ⚖️ Legal

- **License**: page content and source under [CC BY-SA 4.0](LICENSE); vendored files keep their own licenses: [Bulma](static/third_party_licenses/bulma-LICENSE.txt) (MIT), [Font Awesome 5 Free](static/third_party_licenses/fontawesome-LICENSE.txt) (icons CC BY 4.0, fonts SIL OFL 1.1, code MIT), [Academicons](static/third_party_licenses/academicons-LICENSE.txt) (font SIL OFL 1.1, CSS MIT)
- **Code of Conduct**: [Contributor Covenant 3.0](CODE_OF_CONDUCT.md)
- **Security**: report problems privately per [SECURITY.md](SECURITY.md)
<!-- - **Terms of Service**: [TERMS.md](TERMS.md) (add when the project runs a hosted service) -->

## ⭐ Star History

<a href="https://www.star-history.com/#MASkillBlender/maskillblender.github.io&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=MASkillBlender/maskillblender.github.io&type=Date&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=MASkillBlender/maskillblender.github.io&type=Date">
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=MASkillBlender/maskillblender.github.io&type=Date" width="600">
  </picture>
</a>
