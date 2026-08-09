# Getting your portfolio live on GitHub Pages

You already have a GitHub account, so this takes about 10 minutes. No git commands needed — everything below is done in the browser.

## 1. Create the repository

1. Go to github.com and click the **+** in the top right → **New repository**.
2. Name it `portfolio` (or anything you like).
3. Set it to **Public** (private repos can't use free GitHub Pages).
4. Leave everything else default, click **Create repository**.

## 2. Upload the file

1. On the new repo's page, click **Add file → Upload files**.
2. Drag in `index.html` from this folder.
3. Scroll down, click **Commit changes**.

## 3. Turn on GitHub Pages

1. In the repo, go to **Settings → Pages** (left sidebar).
2. Under "Build and deployment," set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
4. Wait 1–2 minutes, refresh the page — GitHub will show you the live URL
   (something like `https://YOUR-USERNAME.github.io/portfolio/`).

That URL is what goes on your resume and LinkedIn.

## 4. Before you consider it "done" — edit these placeholders in index.html

Open `index.html` on GitHub (click the file → pencil icon to edit in-browser, no software needed) and replace:

- Your real name in the `<h1>` tag
- Your GitHub username in the GitHub link
- Your LinkedIn URL
- The "About" paragraph — make it sound like you, not me
- The four project cards — write 1 real writeup per project and link it (even a simple `writeup.md` file in the same repo works as a link target)
- The "Lab & Investigation Writeups" placeholder rows — replace with your first Let's Defend / TryHackMe entries as you complete them

## 5. Ongoing habit

Every time you finish a lab, CTF room, or project: add one line to the writeups section and commit. That's the whole maintenance loop — a few minutes, not a redesign.
