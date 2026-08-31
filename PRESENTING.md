# Facilitator guide

For whoever is running the session. If you're an attendee, you want the [README](README.md) instead.

## The deck has a facilitator track built in

Every screen carries two things you can't see in Present mode:

- **`say`** — the spoken script for that screen. Not a suggestion; it's written to be said.
- **`note`** — why the screen exists and what to watch for in the room.

Press <kbd>S</kbd> (or click **Notes**) to bring them up. Read the notes for a chapter before you teach it — several of them are the difference between the exercise working and the exercise dying.

## Before the session

**Test the display.** Open the link, press <kbd>F</kbd> for fullscreen, confirm it fills the projector at 16:9.

**Take an offline copy as insurance.** Download [index.html](https://raw.githubusercontent.com/yjyoo122/plm-bootcamp/main/index.html) to your laptop and confirm it opens by double-clicking. If the venue wifi fails, you present from the local file and lose nothing.

**Decide Basic or Advanced.** Press <kbd>A</kbd> to toggle. Advanced appends the admin chapter (workspace anatomy, relationships, workflow editor, scripting). Use it for administrators and implementers; leave it off for end users.

**Bring supplies for the icebreaker** (see below):

- Pen and paper for the person at the front of each line — 2 sets
- A stack of loose sheets, several per participant
- Tape, for putting the sheets on a wall

**Check the head count.** You need **two lines with an odd number of people each**. If a line comes out even, a facilitator joins the end of it. This matters — an even line ends on an actor, so there's nothing written down to compare against the original.

## Chapter 2 — "Pass the Part" icebreaker

Roughly ten minutes, laptops closed, before a single product screen. Don't skip it and don't shorten it — the rest of the deck argues against a problem this exercise makes the room feel.

**Setup.** Two lines. Everyone faces forward. Pen and paper to the person at the front of each line; nobody else needs anything.

**Rules.** Person one thinks of a **physical part** — a wiper blade, a battery cover, a torque wrench — writes it down, and shows it only to the person behind them. That person may not speak and may not write: they tap the next shoulder and act it out. The next person writes down what they think it was. Write, act, write, act, to the end of the line.

**Three things to enforce:**

1. **Constrain it to a part.** If someone picks an animal, the lesson becomes about charades.
2. **Acting is one-to-one, on a shoulder tap — never to the room.** This is what makes a quiet room take part.
3. **One referee per line.** They watch for peeking and they keep every sheet of paper.

**Running it.** The "Go." screen has a **7-minute timer built in** — set it before you start. Float, but do not help and do not rescue anyone. *The failure is the content.*

**The result.** When the last person has an answer, they walk to the front. Person one reads out the original; the last person reads out theirs. Then **tape every sheet on the wall, left to right, in order.**

That wall is a revision history, and every sheet on it was somebody doing their job correctly. **Leave it up.** Point at it later when you show change history in the Change management chapter — that callback is the strongest moment in the session.

**The close.** Nothing about the people changed. Nothing about the task changed. The only thing that changed is that information stopped being handed over and started being shared. That's the whole argument for PLM, and the room just watched it fail without it. Laptops open.

## Chapter 3 — Two editions

The one chapter you cannot afford to be vague on. Standalone and Fusion connected are **not two price points of one product** — they sit on different data foundations.

Say the Catia/NX limitation out loud: check-in and version control work through the Vault add-ins, but BOM and item metadata do not synchronise. It's the first thing a serious customer will test, and volunteering it is what gets you trusted with the next question.

The deck's note on this is blunt and worth repeating: learn this in the room and it costs nothing; learn it in front of a customer and it costs the deal.

## While presenting

- <kbd>→</kbd> reveals callouts **one at a time** before moving on. If a screen seems stuck, you're still stepping through its annotations — that pacing is deliberate, use it.
- **Click any screenshot to enlarge it** when someone at the back can't see. <kbd>Esc</kbd> closes.
- <kbd>M</kbd> jumps to the chapter menu if a question pulls you somewhere else; <kbd>H</kbd> returns to the cover.
- Diagram callouts have numbered pins matching the annotation list. Point at the picture, not the text.

## After the session

Send attendees the link: **https://yjyoo122.github.io/plm-bootcamp/** — tell them to press <kbd>P</kbd> for Explore mode so they get a scrollable document rather than a slideshow.

The final chapter has a feedback form. Ask for it in the room while people are still sitting down; response rates collapse once they leave.

---

## Session shapes

| Audience | Mode | Skip? |
|---|---|---|
| End users, first exposure | Basic | Nothing. Run the icebreaker. |
| Administrators / implementers | Advanced (<kbd>A</kbd>) | Nothing — the admin chapter is at the end |
| Partner / pre-sales enablement | Advanced | Give chapter 3 (Two editions) extra time |
| Self-study, sent by link | Explore (<kbd>P</kbd>) | — |
