# Muhammad Latif — Lead 2D Artist Portfolio

A dependency-free static portfolio for Muhammad Latif, featuring selected game work, professional experience, a downloadable CV, App Store and Google Play profiles, and a contact form.

## Repository contents

This repository intentionally contains only seven files:

```text
.
├── .gitignore
├── .nojekyll
├── README.md
├── index.html
├── assets
│   ├── Muhammad-Latif-CV.docx
│   └── muhammad-latif-portrait.webp
└── data
    └── projects.json
```

No package installation or build step is required.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository's `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/(root)` folder, then save.

GitHub will provide the public Pages URL after deployment finishes.

## Update the portfolio

- Edit page content, layout, styles, and interactions in `index.html`.
- Edit featured games in `data/projects.json`.
- Replace `assets/Muhammad-Latif-CV.docx` to update the downloadable résumé while keeping the same filename.
- Replace `assets/muhammad-latif-portrait.webp` to update the portrait while keeping the same filename and portrait orientation.

## Contact form activation

The contact form sends submissions to `latif.2dartist@gmail.com` through FormSubmit. The first submission triggers a one-time confirmation email. Confirm that email to activate delivery for future messages.

## Technical notes

- Static HTML, CSS, and JavaScript only
- Responsive desktop, tablet, and mobile layout
- No committed dependencies or build output
- Relative local paths compatible with GitHub Pages project sites
- External store artwork loads from the public app-store image URLs listed in `data/projects.json`
