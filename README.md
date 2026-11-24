# Evelina | Digital Marketing Portfolio

A personal portfolio website: homepage, About, Skills, three projects with case-study pages, Marketing Approach and Contact.
It is a plain website made of one page (`index.html`). There is nothing to install and no build step.

## What is in this folder

| File | What it does |
|---|---|
| `index.html` | The whole website: content, design and interactivity |
| `404.html` | Friendly page shown if someone opens a link that doesn't exist |
| `robots.txt` | Lets search engines read the site |
| `.nojekyll` | Tells GitHub Pages to serve the files exactly as they are |
| `.gitignore` | Stops junk files (like `.DS_Store`) being uploaded |
| `README.md` | These instructions |

## 1. Preview it on your computer

Double-click `index.html`. It opens in your browser.
(The fonts load from Google Fonts, so you need an internet connection to see them as designed.)

## 2. Edit your content

1. Open `index.html` in a text editor (Notepad, TextEdit in plain-text mode, or VS Code, which is free).
2. Find the block near the top of the script that starts with `EDIT YOUR CONTENT HERE`.
3. Change the words between the quote marks. Keep the quote marks and commas.
4. Save and refresh the browser.

**Replace these two placeholders first:**
- `email: "your.email@example.com"`
- `linkedin: "https://www.linkedin.com/in/your-profile"`

Other things you can edit in the same block:
- `SITE`: your headline, introduction, About text, skills, approach steps and contact message.
- `PROJECTS`: the three case studies. To add a project, copy one whole `{ ... }` item, paste it after the last one (with a comma between), and change the text and the `id`.
  If you add a project, also add its short label in the `label` line further down.
- The "Where it stands" list in the Golden Mess case study is a draft. Update it to match reality.

**Keep it honest.** The concept projects are labelled as fictional and claim no results. If you later do real work, add it as a new project and only include figures you can prove.

## 3. Publish on GitHub (free, with GitHub Pages)

### First time

1. Create a free account at https://github.com if you don't have one.
2. Click the **+** at the top right, then **New repository**.
3. Repository name: `evelina-portfolio` (or any name). Choose **Public**. Click **Create repository**.
4. On the new repository page, click **uploading an existing file**.
5. Unzip this folder on your computer. Open it, select **all the files inside it** (including `.nojekyll` and `.gitignore`; they may be hidden, see the tip below) and drag them into the GitHub page.
6. Scroll down and click **Commit changes**.
7. Go to **Settings**, then **Pages** (left menu).
8. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Choose branch **main** and folder **/ (root)**. Click **Save**.
9. Wait one or two minutes and refresh the Pages screen. It will show your live address:
   `https://YOUR-USERNAME.github.io/evelina-portfolio/`

**Tip for hidden files:** on Mac press Cmd+Shift+. in Finder, on Windows turn on View, Show, Hidden items. If you can't upload `.nojekyll`, the site still works, because it contains no Jekyll files.

**Optional:** name the repository `YOUR-USERNAME.github.io` and your address becomes simply `https://YOUR-USERNAME.github.io/`.

### Updating later

1. Open your repository on GitHub and click `index.html`.
2. Click the pencil icon (Edit), make your changes, and click **Commit changes**.
3. The live site updates within a minute or two.

### Use your own domain (optional)

Buy a domain from any registrar, then in **Settings, Pages, Custom domain** enter it and follow GitHub's DNS instructions
(https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site). Tick **Enforce HTTPS** once it's available.

## Before you share the link: checklist

- [ ] Real email address added
- [ ] Real LinkedIn link added
- [ ] Course name, location and About text are accurate
- [ ] Golden Mess "Where it stands" list is up to date
- [ ] Opened the live site on your phone and clicked every link
- [ ] Concept projects still clearly labelled as concept

## Notes

- Case-study pages use `#` links (for example `.../#golden-mess`), so they work on GitHub Pages without extra settings.
- Fonts (Bricolage Grotesque and Figtree) come from Google Fonts. If they can't load, the site falls back to your device's default fonts.
- The site respects dark mode and reduced-motion settings.
- No licence is included, so by default all rights remain with you. Add one if you want others to reuse the code.
