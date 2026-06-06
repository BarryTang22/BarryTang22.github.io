# Your al-folio site — status & next steps

Built from your CV (Dr. Chong Tang) on the al-folio theme. Most content is done.

## Done
- Homepage bio, title, and contact — `_pages/about.md`, `_config.yml`
- Social links: email, Google Scholar, LinkedIn, CV download — `_data/socials.yml`
- Publications page from your 5 selected papers — `_bibliography/papers.bib`
- Full CV page: education, experience, grants, publications, teaching, service, awards — `_data/cv.yml`
- CV PDF compiled from your LaTeX and wired to the download button — `assets/pdf/cv.pdf`
- News feed: Bristol appointment, ICLR 2026, NeurIPS 2025, NVIDIA grant — `_news/`
- Navbar trimmed to About / Publications / CV (demo pages hidden)

## Left for you
1. **Photo** — your pasted image didn't arrive as a file. Save it as `assets/img/prof_pic.jpg`
   (overwrite the placeholder), or send it to me as a file attachment and I'll drop it in.
2. **GitHub username** — done: set to `BarryTang22`; site URL is `https://BarryTang22.github.io`.
3. Optional: add ORCID to `_data/socials.yml` (line is ready to uncomment).

## Deploy to GitHub Pages
1. On github.com, create a public repo named exactly `BarryTang22.github.io`.
2. In this folder, run:
   `git init -b main`
   `git add .`
   `git commit -m "Initial al-folio site"`
   `git remote add origin https://github.com/BarryTang22/BarryTang22.github.io.git`
   `git push -u origin main`
3. Repo Settings -> Pages -> Source = **GitHub Actions** (al-folio's workflow builds it automatically).
4. Live at `https://BarryTang22.github.io` about a minute later.

## Preview locally (optional)
- Docker: `docker compose up` -> http://localhost:8080
- Ruby: `bundle install` && `bundle exec jekyll serve` -> http://localhost:4000
