# PLM Bootcamp — Fundamentals

An interactive training deck for Autodesk **Fusion Manage** (PLM), built to be run live in front of a room or read on your own.

## ▶ Open the training

### **https://yjyoo122.github.io/plm-bootcamp-fundamentals/**

That's it. No install, no login, no download. Click the link and it runs in your browser.

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
- **Administrators** — run it in Advanced mode (<kbd>A</kbd>) for the configuration chapter.

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

Publishing an update:

```bash
cd plm-bootcamp-fundamentals
# replace index.html with the new build
git commit -am "Update bootcamp deck"
git push
```

GitHub Pages rebuilds in about a minute. Note that each revision stores a full ~18 MB copy, so the repository grows with every update.

</details>

---

*Hosted by Yeon Jong (YJ) Yoo · Autodesk Fusion Manage*
