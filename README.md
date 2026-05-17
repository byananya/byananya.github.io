# Ananya D — Academic Website

Personal academic website built with [HugoBlox](https://hugoblox.com/) (Academic CV template). Clean, minimal, single-column.

## Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) v0.121+
- [Go](https://go.dev/) 1.21+
- Git

## Run Locally

```bash
git clone https://github.com/byananya/ananyad.github.io.git
cd ananyad.github.io

# Download Hugo modules (also generates go.sum)
hugo mod tidy

# Start local dev server with live reload
hugo server

# Visit http://localhost:1313
```

## Build for Production

```bash
hugo --gc --minify
# Output in ./public/
```

## File Structure

```
content/
  _index.md                   # Homepage sections (bio, research, pubs, projects, teaching, contact)
  authors/admin/_index.md     # Your profile — name, role, bio, social links, interests, education
  publication/<slug>/         # One folder per publication
  project/<slug>/             # One folder per project
config/_default/
  params.yaml                 # Theme, colours, footer, features
  menus.yaml                  # Navbar links
  languages.yaml              # Language settings
assets/scss/custom.scss       # Minimal academic style overrides
static/uploads/               # Drop cv.pdf here
.github/workflows/deploy.yml  # Auto-deploy to GitHub Pages on push to main
```

## Customising

### Your profile
Edit `content/authors/admin/_index.md`:
- Name, pronouns, role, institution
- Bio (body text below the second `---`)
- Social links (Twitter/X, Google Scholar, GitHub, LinkedIn)
- Research interests
- Education history

### Add your photo
Add `content/authors/admin/avatar.jpg` (square crop, 400×400 px recommended).

### Add your CV
Drop `cv.pdf` into `static/uploads/`. The "Download CV" button links to it automatically.

### Add a publication
Copy `content/publication/llm-audit-framework-2024/` and edit `index.md`.

Key fields:
```yaml
title: 'Paper Title'
authors: [admin, 'Co-author Name']
date: '2024-01-01T00:00:00Z'
publication_types: ['paper-conference']  # or article-journal / preprint
publication: 'In *Venue Name*'
abstract: 'Your abstract.'
featured: true   # true = appears on homepage
```

### Add a project
Copy `content/project/trustai-audit/` and edit `index.md`.

### Change theme / colours
Edit `config/_default/params.yaml`:
```yaml
appearance:
  theme_day: minimal   # minimal | default | ocean | forest | dark | …
```

## GitHub Pages Deployment

### One-time setup
1. Merge the feature branch to `main`
2. Go to **Settings → Pages → Source** → select **GitHub Actions**
3. Every push to `main` triggers a build and deploy automatically

The live URL will be: `https://byananya.github.io/ananyad.github.io/`

### Custom domain (optional)
1. Create `static/CNAME` containing your domain (e.g. `ananyad.com`)
2. Configure DNS to point to GitHub Pages
3. Update `baseURL` in `hugo.yaml`

## Publication Types Reference

| Type | Use for |
|---|---|
| `paper-conference` | Conference papers |
| `article-journal` | Journal articles |
| `preprint` | arXiv / preprints |
| `chapter` | Book chapters |
| `thesis` | Theses / dissertations |

## Links

- [HugoBlox Docs](https://docs.hugoblox.com/)
- [Hugo Docs](https://gohugo.io/documentation/)
- [HugoBlox Academic CV Starter](https://github.com/HugoBlox/starter-hugo-academic-cv)