# 88 Tabs Deep — Visual Reports

Companion site for the 88 Tabs Deep newsletter. Hosted free on GitHub Pages.

## What's in here

```
index.html                    Home page: list of all reports
assets/style.css              Brand colors and fonts for the whole site
reports/
  _template/index.html        Blank report: copy this for each new one
  law-school-programs/        Example report (sortable table)
README.md                     This file
```

## First-time setup

1. Create a **public** repository on GitHub (for example `88tabsdeep-visuals`).
2. Click **Add file → Upload files**.
3. Open this folder on your computer, select **everything inside it**
   (index.html, assets, reports, README.md), and drag it all onto the page.
   Don't drag the outer folder itself, or index.html ends up one level too deep.
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under "Build and deployment," choose
   **Deploy from a branch**, pick **main** and **/ (root)**, and click **Save**.
6. Wait a minute or two, then refresh. Your link appears at the top:
   `https://YOUR-USERNAME.github.io/88tabsdeep-visuals/`

## Personalize once

- `assets/style.css`: change the colors at the top to your brand colors.
- `index.html` and `reports/_template/index.html`: replace `YOURNAME` with your
  Substack address and update the tagline.

## Adding a new report

1. On GitHub, open `reports/_template/index.html` and copy all of its text.
2. Click **Add file → Create new file**.
3. In the filename box, type `reports/your-topic-name/index.html`.
   Typing the slashes creates the folders for you. Use lowercase and hyphens.
4. Paste the template, then fill in every spot marked `EDIT`.
5. Commit. The page will be live at `.../reports/your-topic-name/`.
6. Open `index.html`, click the pencil icon, copy one `<li class="report-card">`
   block, paste it at the top of the list, and update it to point to the new report.

If Claude gives you a finished report file, skip steps 1 and 4: create the file
at the new path and paste Claude's code in.

## Rules of thumb

- Folder names become your links, so keep them short and readable.
- Everything in this repo is public. Only publish data you're allowed to share.
- Check each new page on your phone before linking it from Substack.
