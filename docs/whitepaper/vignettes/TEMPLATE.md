# Vignette: <a short title that captures the moment>

**Student:** <your name>
**Project:** <your project name>
**Camera used:** orbit / gravity / horizon (delete the ones you didn't use)
**When it happened:** <date + rough time, e.g. "Thu Apr 23, ~4:15pm">
**Who was in the room:** <first names are fine>

---

## The moment

One paragraph — roughly 5–10 sentences. Tell it like you're telling a friend the story over dinner.

Set the scene first: who was where, what they were doing, what the room felt like. Then the moment itself — what did the camera or your project do, and how did people actually react? Did anyone laugh, ignore it, get confused, get it instantly? Did the timing land or feel off?

Try to stay in **present tense**. *"Phil flips the arUco tag and the timer starts"* feels alive in a way *"Phil flipped the tag and the timer started"* doesn't. No code, no implementation details — this is a scene, not a bug report.

> Example A — *a mode misfire:* It's Monday evening, the room is in focused-work mode — eight of us heads-down at our monitors, nobody talking. JuJu gets up to grab her laptop charger from the wall near the podium. She stops there for a few seconds to plug it in, and the bot pings: the room just flipped to "lecture." Ramon notices before she does and points at the Discord channel. Carrie has to step in and manually override it back. JuJu laughs: "I didn't even mean to do that."
>
> Example B — *a small social effect:* It's Monday evening, the room is in group-work mode, and three of us are working through a problem at the small table near horizon. Phil walks over to the timer board, picks up the "focus time" arUco tag, and flips it onto the magnetic strip. The Discord channel pings. Ramon, mid-sentence, glances at his laptop, sees the message, and just stops talking — without a word, the table goes quiet for almost ten seconds. Nobody decided that. The room decided it.

## Why this moment mattered

Two or three sentences. What did this moment reveal that a screenshot can't? Was it about timing, body language, surprise, an edge case, a misunderstanding? **"The system worked" is not enough** — what specifically did this expose about how the room and the software relate to each other?

This is the section that turns a story into a finding. Don't skip it.

> Example A — *paired with the mode misfire above:* The system saw a body at the podium and inferred lecture, but everyone else's heads were down — the actual mode was focused work. The same misfire happens during tech demos: someone leading a demo *from the podium* looks identical to a lecture from the camera's angle. Lecture, tech demo, and "I'm just plugging in my laptop" all share one visual cue (a body at the podium with the rest of the room seated), and the camera can't tell them apart. For now, the instructor still has to confirm mode changes — the room can suggest, but a human has to verify.
>
> Example B — *paired with the timer scene above:* We'd been treating the timer as a personal tool — one student sets it for themselves. But the Discord ping turned a private gesture into a room-wide signal, and the table self-corrected before anyone said anything. The interesting thing isn't that the timer worked; it's that a tag flip became social pressure.

## One supporting artifact (optional)

If you have a screenshot, photo, short clip, or Discord log excerpt that captures part of the moment, drop it in `docs/whitepaper/artifacts/` using the convention `<firstname>-<project>-vignette.<ext>` and link it here:

![](../artifacts/<firstname>-<project>-vignette.png)

Caption: one sentence describing what we're looking at.

If the moment was too quick or too subtle to capture cleanly, say so — *"no artifact, this happened in 4 seconds and I didn't have a camera up"* is a fine answer.

---

*Submission checklist:*
- [ ] File named `<firstname>-<project>-vignette.md` and placed in `docs/whitepaper/vignettes/`
- [ ] Names a real moment, not a hypothetical or composite of several moments
- [ ] Sets the scene (time, place, who was there) before the moment itself
- [ ] "Why this mattered" goes beyond "it worked"
- [ ] No code snippets — this is a story, not a tutorial
- [ ] Your words, not AI-generated
- [ ] Opened as a pull request, not pushed to `main`
