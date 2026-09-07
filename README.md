# PLM Bootcamp — Fundamentals

[![Version](https://img.shields.io/github/v/release/yjyoo122/plm-bootcamp-fundamentals?label=version&labelColor=1a1a1a&color=0696D7)](https://github.com/yjyoo122/plm-bootcamp-fundamentals/releases/latest)
[![Last updated](https://img.shields.io/github/release-date/yjyoo122/plm-bootcamp-fundamentals?label=last%20updated&labelColor=1a1a1a&color=0696D7)](https://github.com/yjyoo122/plm-bootcamp-fundamentals/releases)
[![Changelog](https://img.shields.io/badge/changelog-all%20versions-0696D7?labelColor=1a1a1a)](CHANGELOG.md)

An interactive training deck for Autodesk **Fusion Manage** (PLM), built to be run live in front of a room or read on your own.

## ▶ Open the training

### **https://yjyoo122.github.io/plm-bootcamp-fundamentals/**

That's it. No install, no login, no download. Click the link and it runs in your browser.

---

## Version

**This is Version 3.** The badge above always shows what is live right now — it reads straight from the latest release, so it can't go stale.

- **What changed, version by version** → **[CHANGELOG.md](CHANGELOG.md)**
- **Every release, with dates** → **[Releases](https://github.com/yjyoo122/plm-bootcamp-fundamentals/releases)**

Already opened this before? Check the badge against the version you last ran. If it's higher, the deck has been updated — hard-reload with <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd> to get the new one.

The version goes up whenever the deck itself is republished. README or facilitator-guide edits don't bump it.

---

## Quick start

1. Open the link above.
2. Press <kbd>F</kbd> for fullscreen.
3. Press <kbd>→</kbd> or <kbd>space</kbd> to advance.
4. Stuck? Press <kbd>?</kbd> for the shortcut list at any time.

If you'd rather read at your own pace than be presented to, press <kbd>P</kbd> to switch from **Present** to **Explore** mode — the whole deck becomes one scrollable page with a table of contents.

## Requirements

| | |
|---|---|
| **Browser** | Any current Chrome, Edge, Firefox, or Safari |
| **Install** | None |
| **Account / login** | None |
| **Internet** | Only to load the page the first time |
| **Screen** | Designed for 16:9 projector or laptop; works on tablet |

The deck is a **single self-contained HTML file**. Every image, font fallback, and style is embedded — nothing is fetched from a CDN. Once the page has loaded, it keeps working with the network off.

Two links *inside* the content do need internet when clicked: the Autodesk Help pages (`help.autodesk.com`) and the feedback form at the end.

## Running it offline (no internet at the venue)

Recommended if you're presenting somewhere with unreliable wifi.

1. Download the file: **[index.html](https://raw.githubusercontent.com/yjyoo122/plm-bootcamp-fundamentals/main/index.html)** (right-click → Save link as…, ~18 MB)
2. Double-click the saved file. It opens in your default browser and runs identically.

No web server needed — `file://` works fine.

---

## Navigating

### Toolbar

The bar across the top, left to right:

| Control | What it does |
|---|---|
| ☰ | Chapter menu — jump to any section |
| ⌂ | Back to the cover |
| ← → | Back / forward |
| **Notes** | Show presenter notes for the current screen |
| **Basic / Advanced** | Toggle the depth of the content (see below) |
| **Present / Explore** | Toggle slide mode vs. scrollable-page mode |
| ? | Shortcut list |
| ⛶ | Fullscreen |

### Keyboard shortcuts

| Key | Action |
|---|---|
| <kbd>→</kbd> / <kbd>space</kbd> / <kbd>PageDown</kbd> | Next — also reveals callouts one at a time |
| <kbd>←</kbd> / <kbd>PageUp</kbd> | Back |
| <kbd>S</kbd> | Presenter notes |
| <kbd>P</kbd> | Present / Explore mode |
| <kbd>A</kbd> | Basic / Advanced mode |
| <kbd>F</kbd> | Fullscreen |
| <kbd>H</kbd> | Jump to cover |
| <kbd>M</kbd> | Chapter menu |
| <kbd>Esc</kbd> | Close menu, notes, or an enlarged image |

Click any screenshot to enlarge it. <kbd>Esc</kbd> closes it.

> **Note on <kbd>→</kbd>:** screens reveal their callouts progressively. If a slide looks like it isn't advancing, it is — you're stepping through the annotations on that screen before moving to the next one.

### The two modes

**Present vs. Explore**

- **Present** — one screen at a time, fills the display, arrow-key driven. Use this when you're the one talking.
- **Explore** — the deck becomes a single scrollable document with a table of contents down the side. Use this for self-study, for skimming back to something, or for sending to someone who wasn't in the room.

**Basic vs. Advanced**

- **Basic** — the standard session. This is what you want for end users and for a first pass.
- **Advanced** — appends an admin/configuration section at the end covering **workspace anatomy, relationships, the workflow editor, and scripting**. Turn this on for administrators and technical implementers.

---

## What's in it

Twelve chapters, in order:

| # | Chapter | Covers |
|---|---|---|
| 1 | **Cover** | Title and host |
| 2 | **Why PLM** | The problem, proved with a laptops-closed group exercise before any product is shown |
| 3 | **Two editions** | How the Fusion Manage editions differ and which one applies to you |
| 4 | **Workspaces** | The core building block of Fusion Manage |
| 5 | **Access** | Getting in — roles and permissions |
| 6 | **Fusion ↔ Manage** | How Fusion design data connects to Manage |
| 7 | **Change management** | Change requests and orders end to end |
| 8 | **Quality** | Quality workspace and non-conformance handling |
| 9 | **Ideas** | A full guided walkthrough: list → create → the record → workflow → blocked → read the docs → the fix → voting → implemented |
| 10 | **Documents** | Document handling and control |
| 11 | **Your move** | Where to go next, plus the feedback form |
| 12 | **Advanced** | *(Advanced mode only)* Workspace anatomy, relationships, workflow editor, scripting |

Chapter 2 includes a physical icebreaker ("Pass the Part") that needs a little prep — see **[PRESENTING.md](PRESENTING.md)** before you run the session live.

---

## Who this is for

- **Attendees** — open the link, follow along, revisit later in Explore mode.
- **Facilitators / presenters** — read **[PRESENTING.md](PRESENTING.md)** first.
- **Administrators** — run it in Advanced mode (<kbd>A</kbd>) for the configuration chapter, then move on to the Advanced module below.

## The bootcamp series

| Module | Audience | Link |
|---|---|---|
| **Fundamentals** *(this one)* | Everyone. Start here | [Open](https://yjyoo122.github.io/plm-bootcamp-fundamentals/) |
| **Advanced** | Administrators, implementers. Hands-on build session — needs your own tenant | [Open](https://yjyoo122.github.io/plm-bootcamp-advanced/) · [Repo](https://github.com/yjyoo122/plm-bootcamp-advanced) |

## Sharing it

The link is public — anyone with it can open the training, no account needed. Send the URL directly, or link to this repository.

Because the browser has to receive the whole file to display it, anyone viewing can also save a copy. Treat the content as shareable.

## Feedback

The final chapter has a feedback form built in. Use it — it's the fastest route to changing the material.

## Maintaining this deck

<details>
<summary>For whoever owns the content</summary>

All content lives in a single `DECK` array inside `index.html`. Structure, styling, and behaviour are separate from it, so:

- **To edit content** — change `DECK` only.
- **To translate** — translate `DECK` only. Every user-facing string lives there. Japanese and Korean font fallbacks (`Noto Sans JP` / `Noto Sans KR`) are already in the font stacks.
- **Presenter notes** are the `note` field on each screen; the spoken script is `say`.
- **Images** are base64 data URIs in the image registry, keyed by short name (e.g. `logo`, `yj`).
- Styling follows the Autodesk Brand Hub palette — see the comment at the top of the `<style>` block.

### Publishing a new version

This deck is a live document — update it as often as you like.

**Easiest way.** In the repo folder, either:

- **Double-click `Publish deck.bat`** — publishes the newest `.html` from the OneDrive bootcamp folder, or
- **Drag any `.html` file onto `Publish deck.bat`** — publishes that specific file

The script copies the file over `index.html`, re-applies the "PLM Bootcamp - Fundamentals" title, commits, and pushes. It reports what it did and stops with an explanation if anything looks wrong.

**Why not just copy the file yourself:** a fresh export from source carries the original `PLM Technical Bootcamp` title. The script re-applies the current title on every publish so it can't silently revert. To change the title permanently, edit the two lines near the top of `publish.ps1`.

The script also handles the **version**, so you never have to think about it:

1. reads `VERSION` (currently `3`) and bumps it to `4`
2. adds a `## Version 4` entry to `CHANGELOG.md`
3. tags the commit `v4` and publishes a **GitHub release** titled *Version 4*

The README badge picks the new number up automatically — nothing else to edit.

Give the release a real description instead of a timestamp:

```powershell
.\publish.ps1 -Notes "Rewrote the Quality chapter; new screenshots throughout"
```

That one line becomes the commit subject, the changelog entry, and the release notes.

| Switch | Effect |
|---|---|
| `-Notes "..."` | Text for the changelog entry and release notes. Use it. |
| `-NoBump` | Publish without raising the version (typo fix in an already-released deck) |
| `-NoRelease` | Bump and tag, but skip creating the GitHub release page |

Releases need the [GitHub CLI](https://cli.github.com/) (`gh`) signed in. Without it the script still bumps, tags and pushes — it just prints a link for creating the release by hand.

**Manually, if you prefer git:**

```bash
cd plm-bootcamp-fundamentals
# replace index.html with the new build
echo 4 > VERSION            # bump it
# add a "## Version 4" entry to CHANGELOG.md
git commit -am "Version 4 - what changed"
git tag -a v4 -m "Version 4"
git push && git push origin v4
gh release create v4 --title "Version 4" --notes "what changed"
```

**Or with no tools at all:** on the repo page, open `index.html` → pencil icon → delete-and-upload, or drag the new file into the repo. Works only while the deck stays **under 25 MiB** — that's GitHub's browser upload limit, and the deck is currently 17.5 MiB.

### Things to know about updating

- **Pages rebuilds in about a minute** after a push.
- **Browsers cache the page for 10 minutes** (`Cache-Control: max-age=600`). If you still see the old version, hard-reload with <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd>. Attendees mid-session are unaffected — they already have the file loaded.
- **Every revision stores a full ~18 MB copy.** GitHub recommends repositories stay under 1 GB, so budget roughly **55 updates** before the history needs squashing. The publish script warns you as you approach it.
- **Don't rename the repository.** It changes the Pages URL and breaks every link you've shared — `github.io` paths do not redirect. The deck title is independent of the repo name.

</details>

---

*Hosted by Yeon Jong (YJ) Yoo · Autodesk Fusion Manage*
