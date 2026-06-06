# Your al-folio site — status & next steps

Live at https://BarryTang22.github.io (GitHub Actions builds and deploys to the `gh-pages` branch).

## Done
- Recruiting-focused homepage (`_pages/about.md`): research in multimodal reasoning, representation
  learning, agentic AI, efficient AI; 700+ citations; explicit PhD-student call.
- Contact: chong.tang@bristol.ac.uk; socials: Google Scholar, LinkedIn, GitHub (`_data/socials.yml`).
- Publications page from `_bibliography/papers.bib`.
- Projects tab (`_pages/projects.md`, `_projects/`): ongoing and previous research projects.
- News feed (`_news/`): AIRR funding, Bristol appointment, ICLR 2026, NeurIPS 2025, NVIDIA grant.
- CV removed from the website (page, nav tab, download button, and PDF all deleted).

## Left for you
1. **Photo** — pasted images don't reach me as files. In File Explorer, copy your photo into
   this folder as `assets/img/prof_pic.jpg` (overwrite the placeholder), then re-push.
2. **Project images (optional)** — project cards use placeholder images; replace the `img:` field
   in each `_projects/*.md` with your own figures when ready.

## Re-publish after any change
```
git add .
git commit -m "Update site"
git push
```
GitHub Actions rebuilds and redeploys automatically (~2 min).
Keep Pages on: Settings -> Pages -> Source = Deploy from a branch -> gh-pages -> /(root).
