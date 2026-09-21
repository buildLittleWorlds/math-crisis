# AI, over coffee

A friendly, illustrated publication about AI for curious friends and family. The first story explores the September 2026 mathematics controversy.

## Website

The website is plain HTML and CSS in `docs/`, published with GitHub Pages from `main` → `/docs`. No package installation, build system, account, or JavaScript is needed to read it.

- Homepage: `docs/index.html`
- First article: `docs/stories/when-ai-solves-math/index.html`
- Shared design: `docs/assets/styles.css`

To preview locally from the repository root:

```sh
python3 -m http.server 8765 --directory docs
```

Open `http://localhost:8765/`. To publish another story, add a new folder under `docs/stories/` with an `index.html`, use the existing article as the structure, and add its link on the homepage. Update the title, description, canonical URL, dates, illustration, and source links. Push to `main` to publish through the configured Pages source.

## Research dossier

Research on the September 2026 debate about AI, mathematical discovery, human understanding, and the future of mathematical communities.

**Research cutoff: September 21, 2026.** This is an initial research dossier, not an endorsement of a declaration or a mathematical verification of announced proofs.

- [Read the research brief](research/2026-09-21-math-and-ai-debate.md).
- [Check the viral quotation and its context](research/quote-check.md).
- [Browse the source register](research/sources.md).

The guiding question: **When does faster mathematical discovery serve the public, and when does it undermine the human capacities that make discoveries useful?**

The brief distinguishes slowing AI development, moderating automated problem-solving campaigns, improving publication standards, and protecting space for learning. These are different proposals with different costs.

Research and synthesis prepared with Codex. Statements by participants are attributed; the assessment is an editorial synthesis. The repository contains original summaries and links. A working auto-caption transcript is retained locally and excluded from Git.
