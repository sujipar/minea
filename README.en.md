# MINEA

[한국어](README.md) · [English](README.en.md)

**An assistant that does things before you ask.**

It watches your screen, mail and messages, and when something is worth doing, it does
it. And when you wonder about something, **it builds a curriculum and teaches you.**

> **The app's interface is in Korean and English.** Switch at the top of Settings —
> no restart needed.

<p align="center">
  <img src="https://minea.minea.workers.dev/preview.gif" width="700" alt="MINEA spots a date in an email and offers to add it to the calendar">
</p>

<p align="center">
  <a href="https://minea.minea.workers.dev/intro.mp4">Watch the intro (29s, Korean)</a>
</p>

## Get it

**[Download MINEA →](https://minea.minea.workers.dev)**

macOS 11 (Big Sur) or later · Intel and Apple Silicon · 357MB

**One more download, once.** You can start giving it tasks right away by typing
`@미네아 …` in any text field. But to let it **watch on its own**, it needs a local
model (about 5.4GB) that decides — on your machine — whether to speak up. One button
in the app. No Homebrew, no password.

## It doesn't only help while you're at the screen

> **These four need the iPhone app.** Before it goes to the App Store proper, it's opening
> on **TestFlight** first — currently awaiting Apple's review. The link will be posted here
> once it's open. Everything on the Mac side works today.

An assistant that lives inside a window stops existing the moment you walk away.

- **It calls you.** Before an appointment. If you went to bed late, the wake-up call
  is pushed 30 minutes (unless something is scheduled right after). Pick up and it's a
  conversation — ask "what time was that meeting again?" and it answers; it hangs up
  when you say you're done
- **Hand off work from the iPhone lock screen.** Call it through Siri and your Mac
  does the work. The screen goes dark while it runs, and a notification wakes you when
  it's finished
- **It reads your Apple Watch as a multi-week trend**, not as single days. When health
  declines it usually *slides* — no single day crosses a threshold, so day-by-day checks
  never fire. **It does not diagnose.** It says "this differs from your usual" and stops
  there, and it writes things down so you have an answer when a doctor asks "since when?"
- **It puts text on Meta Ray-Ban Display lenses** — silent, so it works around other people

## It teaches what you were curious about

An answer helps once. So instead of just answering, it **builds a curriculum.**

The number of sessions and their length come from the subject — one English phrase is
15 minutes, data modeling gets 50-minute sessions. It finds the free slots, puts them on
your calendar, and **the window opens on the hour.**

- **A 20-minute assessment first.** Not just what you know — how you spot the crux, how
  you transfer an idea, your instinct for it. You get a report with evidence behind every
  score, and blanks where there isn't any.
  Reasoning questions are written so that **you can answer them knowing nothing about the
  subject** — if a newcomer misses everything and gets "logic: 1", that's not an
  assessment, it's a label
- **A 7-minute debrief at the end.** An honest read on how it went. To keep it from
  inventing praise, it may only cite **things actually said that session** — "you asked
  twice whether the rest keeps running after a failure." If you barely spoke, it says so
- **An exam, and one retry if you miss.** Pass and your level in that field goes up a
  notch, so the next subject starts from there. There is no third attempt — past that,
  it isn't guidance anymore, it's debt collection

## It moves even when nothing comes in

Most assistants need an input to react to. So on a quiet day they do nothing at all.

- **It asks a separate question: what's missing today?** Two hours lying down, and it
  books 30 minutes of yoga into a free slot two hours out. **It doesn't say anything —
  it just leaves the slot.** Skip it, delete it, no harm done
- **It cleans up what it scheduled.** Seeing yesterday's skipped workout again tomorrow
  morning is a debt notice. Things you scheduled yourself are never touched
- **It keeps a one-page journal of each day.** Raw logs are too heavy to ever get read.
  Patterns get pulled from the journal and become the basis for what it does next
- **Observation beats what you wrote down.** If your Watch says "bedtime 10pm" but you
  actually sleep at 3am, it moves the baseline — one step a day, with a note on why,
  and it tells you once that it moved

## On the Mac

- Reads new mail and messages, pulls out appointments, deadlines, things to reply to
- Watches the screen and speaks up — only when there's actually something to do
- Adds, moves and deletes calendar events and reminders (Google Calendar too)
- Works while you're out — send it a task from your iPhone or Telegram
- Type `@미네아 draft a reply to this email` in any text field

## You decide how far it goes

| | |
|---|---|
| Calendar, notes, organizing | Done without asking. It's reversible. |
| Replies and outgoing mail | **Drafted only.** You press send. |
| Payments and bookings | **Stops right before.** A person always presses the last button. |

The biggest thing building this taught us: **if interrupting is the only channel you
have, you end up saying nothing.** When every nudge has to ring, you second-guess each
one — and eventually stay quiet. Only after adding a *silent* layer (quietly placing
things on the calendar) could it start looking after things often.

## Price

- **If you have a Claude account**, use it with no limits.
- If not, **30 runs** free. No card.
- Real pricing isn't set yet. We want to hear from people who've used it first.

## What it sees is filtered on your machine

Whether to speak up is decided **on your Mac**. The text of your messages and mail never
leaves the computer — only a few lines, already filtered down to "worth acting on", go out.
Messages from banks and brokerages aren't read at all; account, card and ID numbers are
masked before anything is passed along.

## For web tasks

Sign in to claude.ai in Chrome and install the [extension](https://claude.ai/chrome), and
MINEA can click through websites for you. The Claude desktop app takes over that
connection if it's running, so quit it when handing over web work.

## Still being built

If something feels off or doesn't work, that's exactly what we want to hear.
Open an [issue](../../issues) or write to suji63261@gmail.com.
