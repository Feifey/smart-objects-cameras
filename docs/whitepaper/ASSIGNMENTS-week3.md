# Week 3 Homework — "Explain it to someone else"

**Week 3:** week of Mon Apr 27, 2026
**Due:** Sun May 3, 2026 (end of Week 3)
**Theme:** explain it to someone else

This is the third of four white-paper bundles. Three small pieces this week — a vignette, an interview with someone outside the class, and a hand-drawn system diagram. Plan for **1.5–4.5 hours** total. Due **Sun May 3**.

> **About the time range:** the low end (~1.5 hr) is "you know what you want to say and knock it out." The high end (~4.5 hrs) is "you iterate, you redraw the diagram twice, and you hand in something you're proud of." Both are valid — pick your pace.

All three submissions go in the repo under `docs/whitepaper/`. Open one PR for the bundle (or three if you prefer) — don't push to `main`.

---

## Part 1 — "A moment in the room" vignette (30 min – 1.5 hrs)

Pick **one specific moment** when your project actually played out in the classroom — when someone reacted to it, missed it, was confused by it, was delighted by it, was creeped out by it. Then write the scene.

**Steps:**
1. Copy `docs/whitepaper/vignettes/TEMPLATE.md` to a new file named `<yourfirstname>-<project>-vignette.md` in the same folder.
   - Example: `phil-timer-vignette.md`
2. Pick a real moment with at least one other person present. Not a hypothetical, not a composite of several moments — one specific time you can name (date and roughly when of day).
3. Fill in every section. Write the moment in **present tense** if you can — it makes the scene come alive.
4. (Optional) Drop a supporting artifact in `docs/whitepaper/artifacts/` using the convention `<firstname>-<project>-vignette.<ext>` and link it from your vignette.
5. Open a PR titled `vignette: <yourfirstname> <project>`.

**The section that matters most is "Why this moment mattered."** A scene without a finding is just a story. What did this moment reveal about how the room and the software relate that you couldn't see from a screenshot or a status file?

**Do NOT use AI to write your vignette.** The whole point is to capture *your* voice describing something you actually saw.

---

## Part 2 — Outsider interview (45 min – 2 hrs)

Find someone who **doesn't know much about this class** — a roommate, a sibling, a friend in another program, a parent on FaceTime, a classmate from an unrelated course. Show them your project with minimal setup. Capture what they say.

**Steps:**
1. Copy `docs/whitepaper/interviews/TEMPLATE.md` to a new file named `<yourfirstname>-<project>-interview.md` in the same folder.
   - Example: `phil-timer-interview.md`
2. Pick a genuine outsider — **not another student in this class.** The whole assignment hinges on this. People inside the class can't see your blind spots because they're inside it too.
3. Show, don't explain. Hit play on a clip or demo with as little front-loading as possible. The less context you give, the more honest their reaction.
4. Capture answers in their **actual voice**. Quote them verbatim — don't translate into engineering-speak. *"Wait, the camera's the brain?"* is more useful than *"the interviewee inquired about the role of the camera in the system architecture."*
5. Add at least one question that's specific to your project — something you genuinely want an outsider's read on.
6. Open a PR titled `interview: <yourfirstname> <project>`.

**The section that matters most is "What I learned that I couldn't have learned from a classmate."** Be honest, especially if the feedback stung — that's usually the most useful kind. Have your interviewee read the writeup before you submit so they're okay with how they're quoted.

**Do NOT use AI to write your interview writeup.** Same reason as above.

---

## Part 3 — Hand-drawn system diagram (15 min – 1 hr)

Draw your project's data flow on paper. Boxes for components, arrows for data, plain English labels.

**Steps:**
1. Get a piece of paper and a pen or sharpie. (Whiteboard works too — just photograph it cleanly.)
2. Draw a box for each component in your project: camera, detector script, status file, bot, Discord, viewer, anything else that holds state or moves data.
3. Draw arrows showing what flows between them, and **label every arrow** — "person count," "screenshot," "Discord message," "config change."
4. Add a one-line caption at the bottom of the page in your own handwriting.
5. Photograph it in good light, straight on. Crop the photo so the page fills the frame.
6. Save it to `docs/whitepaper/diagrams/` as `<yourfirstname>-<project>-diagram.<ext>` (jpg or png).
7. Open a PR titled `diagram: <yourfirstname> <project>`.

**Why hand-drawn?** It forces you to commit to a few key abstractions instead of fiddling with formatting. The point is to show the *shape* of the system, not to make it pretty. Crooked lines and crossed-out boxes are fine — encouraged, even. We want to see how you actually think about your project, not what a diagramming tool wants you to draw.

If your project is mostly a single script, the diagram should still have at least 4–5 boxes (camera, model, script logic, output file, viewer). If it has many components, prioritize clarity over completeness — you can always note "details omitted" on the page.

---

## Why we're doing this

- **Vignettes** give the white paper its scenes — the moments that show how this stuff actually lands in a room with real people. Screenshots are evidence; vignettes are story.
- **Outsider interviews** surface the assumptions you can't see from inside the class. Every project has tone problems, weird metaphors, and missing affordances that are invisible to people who've been living with the code for weeks. An outsider sees them in thirty seconds.
- **Hand-drawn diagrams** give us a visual index of every project, side by side, in a uniform style. When the white paper is assembled, this section should look like a sketchbook — twelve different brains explaining their systems in twelve different handwritings.

Your name will be on each piece. This is a portfolio.

---

## Questions

Post in the class Discord. Don't let tooling block your submission — if a git or photo-upload issue is in your way, say so early.

**Due:** Sun May 3, 2026 (end of Week 3).

---

## What's coming next (so you can plan ahead)

- **Week 4 (starting May 4) — "Synthesis & showcase":** The white paper is assembled, everyone reviews their own sections, we prep the live showcase. No new templates — just review and polish the pieces you've already submitted across Weeks 1–3.
