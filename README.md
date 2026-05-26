# Roland Treiber Portfolio and Resume

This repository contains the source for my personal portfolio and resume website:

https://rolandtreiber.github.io/resume/

The site is a static Hugo Blox portfolio built from Markdown and YAML content. It presents my senior software engineering profile, selected projects, certifications, experience, publications and a downloadable PDF resume.

## What Is Included

- Resume-aligned homepage content for Roland Treiber
- Selected projects including Shoptopus, SyncBin, K40 SVG Optimiser and Laser Cut Render Blender Add-on
- Certification and experience sections
- Technical writing and tutorial links
- Static resume download at `static/uploads/resume.pdf`
- GitHub Pages-compatible Hugo configuration

## Project Structure

```text
content/_index.md              Homepage sections and landing page layout
content/projects/              Portfolio project pages and featured images
content/blog/                  Publication and article entries
data/authors/me.yaml           Profile, links, skills, education and awards
assets/media/authors/me.png    Profile image
static/uploads/resume.pdf      Downloadable resume
config/_default/               Hugo and Hugo Blox configuration
.github/workflows/             GitHub Actions build/deploy workflows
```

## Local Development

Install dependencies:

```bash
pnpm install
```

Run the local development server:

```bash
pnpm run dev
```

Hugo will print the local URL in the terminal. With the current GitHub Pages base URL, it is usually served under `/resume/`.

Build the static site:

```bash
pnpm run build
```

The generated site is written to `public/`.

## Tooling

This project expects:

- Hugo Extended
- Node.js
- pnpm
- Go, for Hugo module resolution

The package scripts are defined in `package.json`:

- `pnpm run dev` starts `hugo server --disableFastRender`
- `pnpm run build` runs `hugo --minify` and builds the Pagefind search index
- `pnpm run pagefind` rebuilds only the search index from `public/`

## GitHub Pages

The Hugo config sets:

```yaml
baseURL: 'https://rolandtreiber.github.io/resume/'
```

That means the built site is intended to be served from the `resume` repository path on GitHub Pages.

Before deploying, verify locally with:

```bash
pnpm run build
```

The GitHub Actions workflows in `.github/workflows/` contain the CI/deployment setup for building the static Hugo site.

## Content Updates

Most content changes should be made in Markdown or YAML:

- Edit homepage sections in `content/_index.md`
- Edit profile, links, skills, languages and certifications in `data/authors/me.yaml`
- Add or update project pages in `content/projects/`
- Add or update publication entries in `content/blog/`
- Replace the resume PDF at `static/uploads/resume.pdf`

Featured images should live beside their content page as `featured.png`, `featured.jpg` or another Hugo-supported image format.

## Credits

Built with [Hugo](https://gohugo.io/) and [Hugo Blox](https://hugoblox.com/).
