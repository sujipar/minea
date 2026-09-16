# MINEA

**A Mac assistant that does things before you ask.**

It watches your mail, messages, and screen. When it spots something worth doing, it does it — or offers, with one tap.

```
Your mail says "next Tuesday at 3"
   -> Tuesday 3pm meeting. Add it to your calendar?
```

Tap it and it's done. Ignore it and it disappears.

> **Note on language.** MINEA speaks Korean. The app interface, its replies, and the
> download page are all in Korean. This page is in English so you can tell whether it's
> for you — but the product itself is not localized yet.

## Download

**[Get MINEA](https://minea.minea.workers.dev)** (page in Korean)

macOS 11 (Big Sur) or later, Apple silicon only. 212 MB.
Signed and notarized by Apple, so it opens without warnings.

**One more download, once.** You can type `@미네아 …` (the trigger is Korean) in any text
field right away.
But to let it **watch** your mail and screen, it needs a model (about 5.4 GB) that decides
locally whether something is worth raising — one button inside the app, no Homebrew,
no password. That download is why your messages never leave the machine.

## What it does

- **Reads mail and messages as they arrive** — pulls out appointments, deadlines, and replies you owe
- **Watches the screen** — when there's something to do on it, a small bubble offers to do it
- **Writes to Calendar and Reminders** for you, with time and place filled in
- **Takes direct orders** — type `@미네아 <task>` in any text field, anywhere

## Where it stops

| | |
|---|---|
| Calendar, notes, tidying up | Does it without asking. Reversible. |
| Replies and emails | **Drafts only.** You press send. |
| Payments and bookings | **Stops right before.** You press the last button. |

## Price

- **If you have a Claude account**, it uses yours — no limits, nothing to pay us.
- If you don't, **10 runs free**. No card.
- Pricing after that isn't decided. We want to hear from the first users first.

## Your screen stays on your Mac

The decision of whether to speak up is made **locally**, on your machine. The full text of
your mail and messages never leaves it. Only a few lines — the part that looks like a task —
are sent out when MINEA actually does the work.

## Source

This repository is the download page and the issue tracker. **The app is not open source.**
If something is broken or awkward, that's exactly what we want to hear — open an issue,
or write to suji63261@gmail.com.
