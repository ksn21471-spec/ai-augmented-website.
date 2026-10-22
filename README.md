# Abdul Ahad — Digital Portfolio

A responsive static portfolio website created for the **AI-Augmented Static Website Development with Git and GitHub** lab assignment.

## Project files

- `index.html` — website content and structure
- `style.css` — responsive layout, colors, typography, and visual styling
- `script.js` — mobile navigation and automatic footer year
- `README.md` — project notes and Git workflow

## Run locally

No build tools or package installation are required.

1. Extract the project folder.
2. Open `index.html` in a browser, or open the folder in VS Code and use a local preview extension.
3. Review the content and customize it before submission.

The Google Fonts import requires an internet connection; the page uses fallback fonts if unavailable.

## AI prompt used

> Create a complete, responsive, modern static portfolio website for Abdul Ahad, a computer science student at COMSATS University Islamabad, Abbottabad Campus. Use separate `index.html`, `style.css`, and `script.js` files. Give it a polished dark theme with violet and mint accents, accessible navigation, a hero section, student profile, technology interests, and a section explaining the AI-assisted Git/GitHub DevOps workflow. Make it mobile-friendly, readable, visually consistent, and easy for a beginner to understand. Do not use a framework or require a build step. Add small JavaScript behavior for the mobile menu and current footer year.

## Git and GitHub workflow

Run these commands in a terminal opened in this project folder:

```bash
git init
git status
git add .
git commit -m "Initial website commit"
git log --oneline
```

Create a **new empty public repository** on GitHub. Do not add a README, `.gitignore`, or license during repository creation.

Replace the URL below with your own repository URL:

```bash
git remote add origin https://github.com/YOUR-USERNAME/ai-augmented-website.git
git remote -v
git branch -M main
git push -u origin main
```

If Git asks you to configure your identity, use the name and email associated with your GitHub account:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Then retry the commit if needed. GitHub may prompt you to authenticate through a browser or credential manager.

## Screenshots for the assignment PDF

Capture your **actual local results**—do not fabricate terminal output or screenshots.

1. The AI prompt in the AI tool you used.
2. The website open in your browser.
3. Terminal showing `git init` and `git status`.
4. Terminal showing `git log --oneline`.
5. Terminal showing `git remote -v`.
6. Terminal showing the successful `git push -u origin main`.
7. GitHub repository page showing the uploaded files.
8. The public repository URL.

Put the screenshots in order in one document and export it as a single PDF. Keep the public repository available until grading is complete.
