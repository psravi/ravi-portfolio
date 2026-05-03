# Ravi Mukkapati Portfolio Website

A static personal portfolio site for Ravi Mukkapati, built with plain HTML, CSS, and JavaScript. It is ready to push to GitHub and deploy on Vercel.

## Files

```text
.
├── index.html
├── styles.css
├── script.js
├── vercel.json
├── assets/
│   ├── ravi-mukkapati-profile.jpg
│   ├── favicon-profile.png
│   ├── Ravi_Mukkapati_Resume.pdf
│   └── Ravi_Mukkapati_Resume.docx
└── README.md
```

## Local preview

From the project folder, run:

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Deploy with GitHub and Vercel

1. Create a new GitHub repository, for example `ravi-portfolio`.
2. Copy these files into the repository root.
3. Commit and push:

```bash
git init
git add .
git commit -m "Create personal portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ravi-portfolio.git
git push -u origin main
```

4. In Vercel, import the GitHub repository.
5. Use the default static site settings:
   - Framework preset: Other
   - Build command: leave empty
   - Output directory: `.`
6. Deploy.

## Customization checklist

- Replace `YOUR_USERNAME` in the Git command above.
- Update any project wording in `index.html` if you want more detail or fewer client names.
- Replace the resume files in `assets/` whenever you update your resume.
- Update the email or LinkedIn links in `index.html` if they change.

## Privacy note

The public website uses the email and LinkedIn URL provided for the portfolio. The phone number from the source resume is intentionally not published in the site content.
