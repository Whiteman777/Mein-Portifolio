# Portfolio

Personal portfolio site for **Youssef Waleed Mohamed**  App & Backend Developer from Cairo, Egypt.

A single-page, dependency-free static site. No build step, no framework, no bundler.

## Structure

```
.
├── index.html      # the entire site (markup, styles, script)
├── assets/
│   └── profile.jpg # profile photo shown in the hero
└── README.md
```

All CSS lives in a `<style>` block in `index.html` and all JS in a small `<script>` at the bottom of the same file. The only external resource is Google Fonts (Space Grotesk + Inter).

## Viewing locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

A local server is preferable, since the photo is loaded from a relative path and some browsers restrict `file://` requests.

## Sections

| Anchor      | Contents                                                        |
| ----------- | --------------------------------------------------------------- |
| `#hero`     | Name, role, photo, and the fake `status.sh` terminal panel        |
| `#about`    | Short bio and a fact list (location, GPA, languages)              |
| `#skills`   | Skill groups: Flutter, Backend, Database, Data Science, and more  |
| `#projects` | Six selected projects with tech stacks                            |
| `#experience` | Professional work history                                       |
| `#education`  | Degree and GPA                                                  |
| `#certs`    | Certifications and spoken languages                               |
| `#contact`  | Email, phone, and location                                       |

## Editing content

All copy lives as plain text inside `index.html`:

- **Bio, projects, experience** — search the text in each section and edit directly.
- **Add a project** — copy an existing `<div class="project">` block and update the index, name, description, and `.stack` tags.
- **Add a skill** — insert another `<span class="pill">` into the relevant `.pills` group.
- **Change colors** — edit the CSS custom properties at the top of the `<style>` block (`--ink`, `--signal`, `--paper`, and friends).
- **Swap the photo** — replace `assets/profile.jpg`, keeping the same filename. If the image is missing or fails to load, the site falls back to a "YW" monogram automatically.

## Deployment

The site is fully static, so any static host works  GitHub Pages, Netlify, Vercel, or Cloudflare Pages. Upload the folder as-is; there is nothing to compile.

To publish on GitHub Pages, push the folder to a repository and enable Pages on the branch root.
# Mein-Portifolio
# Mein-Portifolio
