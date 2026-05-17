# HANDOFF — Read me first 👋

This is your academic website, built from the
[academicpages](https://github.com/academicpages/academicpages.github.io)
template and tuned to a **modern / classic / minimalist** style.

Everything is filled with clearly-marked **`TODO`** placeholders. You only edit
plain text files — no coding required.

---

## 1. The two things you must know

> **A. Free hosting needs a PUBLIC repo.**
> GitHub Pages is free only for *public* repositories. This repo is currently
> **private** for setup. To put the site online for free it must be made
> **public** (Step 4 below).

> **B. The clean address `https://liuyanruc416.github.io` needs the repo to be
> owned by *your* account (`liuyanruc416`) and named exactly
> `liuyanruc416.github.io`.**
> It was created under a helper account. Transferring it to you (Step 3) is a
> few clicks and is the only step that produces the nice URL.

---

## 2. What is where

| You want to edit… | Open this file/folder |
|---|---|
| Homepage bio & research interests | `_pages/about.md` |
| Your name, email, photo, profile links | `_config.yml` (top section + `author:` block) |
| Top menu links | `_data/navigation.yml` |
| Publications | one file per paper in `_publications/` (copy the sample) |
| Talks | one file per talk in `_talks/` (copy the sample) |
| Teaching | one file per course in `_teaching/` (copy the sample) |
| CV | replace `files/cv.pdf` with your real PDF; edit `_pages/cv.md` |
| Headshot | replace `images/profile.png` with your photo (square is best) |

Search the project for `TODO` — every spot that needs your input is marked.

**To add a new publication (same idea for talks/teaching):**
1. In `_publications/`, copy `2025-01-01-sample-publication.md`.
2. Rename it `YYYY-MM-DD-short-title.md` (the date sets the order — newest first).
3. Edit the fields between the `---` lines and save. Done.

You can edit everything **directly on github.com** (click a file → pencil
icon → commit), or locally (Section 5).

---

## 3. Transfer the repo to your account (gives you the nice URL)

1. Accept the email/GitHub invitation to this repository (you were added as
   **admin**).
2. Ask the helper account owner to go to **Settings → General → Danger Zone →
   Transfer ownership** and transfer to **`liuyanruc416`**, OR (since you are
   admin) coordinate the transfer. The repo name `liuyanruc416.github.io` is
   already correct, so no rename is needed.

## 4. Put the site online (free)

After the repo is under your account:
1. Repo **Settings → General → Danger Zone → Change visibility → Public**.
2. Repo **Settings → Pages**:
   - **Source:** *Deploy from a branch*
   - **Branch:** `main` (or `master`) / `/ (root)` → **Save**.
3. Wait ~1–2 minutes. Your site is live at **https://liuyanruc416.github.io**.
4. Every time you commit a change, the site rebuilds automatically.

## 5. (Optional) Preview locally before publishing

**You do not need this** — GitHub builds and shows the site for you after every
commit (Step 4). Local preview is only for impatient editing.

⚠️ **Important:** this template uses the GitHub Pages "classic" gem stack,
which only runs on **older Ruby (3.1 or earlier)**. It will *not* run on a
modern system Ruby (3.2+). Pick one of these:

**Option A — Docker (recommended, no Ruby version juggling):**
Install Docker Desktop, then:
```bash
cd liuyanruc416.github.io
docker compose up
```
Open <http://localhost:4000>. `Ctrl+C` to stop.

**Option B — a pinned Ruby via a version manager:**
```bash
cd liuyanruc416.github.io
rbenv install 3.1.6 && rbenv local 3.1.6   # or use rvm/asdf
bundle install
bundle exec jekyll serve --livereload
```
Open <http://localhost:4000>. `Ctrl+C` to stop.
(`_config.yml` changes need a server restart in either option.)

> Note: the maintainer verified the **content and configuration parse
> correctly**; the only local hiccup is this Ruby-version constraint, which
> does not affect the live GitHub Pages build.

---

## 6. Style

The minimalist look (serif headings, sans-serif body, deep-red accent) is set
with two small, reversible changes:
- `_sass/_themes.scss` → `$header-font-family`
- `_sass/theme/_default_light.scss` → `$primary-color` and link colors

To try a built-in palette instead, change `site_theme` in `_config.yml`
(options: `default`, `air`, `sunrise`, `mint`, `dirt`, `contrast`).

Questions about the template: <https://academicpages.github.io/markdown/>.
