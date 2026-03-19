# insanridho.github.io

Personal portfolio and CV site for Insan Ridho Chairuasni.

Built with [Jekyll](https://jekyllrb.com/) and the [AcademicPages](https://github.com/academicpages/academicpages.github.io) theme (a fork of Minimal Mistakes).

---

## Deployment Instructions

### First-time setup (theme switch from Minima → AcademicPages)

1. Replace all files in this repo with the new versions
2. In GitHub repo settings → Pages → confirm source is `main` branch
3. Push changes — GitHub Actions will rebuild automatically (takes ~2 minutes)

### Before pushing, fill in these placeholders:

- `_config.yml` line `email`: replace `your@email.com` with your actual email
- `_config.yml` line `linkedin`: confirm handle is correct (`insanridho`)
- `contact.md`: replace `your@email.com` with actual email
- `cv.md`: once you have a PDF CV, place it at `assets/files/InsanRidho_CV.pdf`
  If no PDF yet, remove the download line from `cv.md`

### File structure

```
insanridho.github.io/
├── _config.yml          # Site settings, author sidebar, navigation
├── _posts/              # Blog posts (YYYY-MM-DD-title.md format)
├── assets/
│   ├── images/
│   │   └── profile.jpg  # Your profile photo (keep existing)
│   └── files/
│       └── InsanRidho_CV.pdf  # Add your PDF CV here when ready
├── index.md             # Homepage (About me + News)
├── cv.md                # CV page
├── talks.md             # Talks & speaking engagements
├── publications.md      # Publications & op-eds
├── blog.md              # Blog index
├── contact.md           # Contact page
└── CNAME                # Custom domain (insanridho.com)
```

### Adding a new blog post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`:

```markdown
---
title: "Your Post Title"
date: 2026-03-19
---

Your content here.
```

### Adding a new talk or publication

Simply edit `talks.md` or `publications.md` and add a new bullet point at the top of the relevant section.
