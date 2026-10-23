# First 5 minutes

Just what to try first, once it's installed.
Two minutes to read, three to do.

> **The app's screen is still in Korean.** Only the replies switch to English
> (Settings → the top row, `Language · 언어`). So this guide gives you the Korean
> labels **exactly as they appear**, with what they mean — you can match them by eye.
> A full English screen is being worked on.

---

## 1. Say something to it (30s)

Open the app and you get a chat box. Type anything:

```
What's on today?
```

It reads your calendar and tells you. **This works with no setup at all.**

Then try these:

```
Put dentist at 3pm tomorrow
Which days am I free this week?
Remind me to buy milk
```

> The first time it reads Calendar or Reminders, macOS will ask permission. Please hit **OK**.
> Without it, it can't read your schedule — and most of what follows is blocked.

---

## 2. Use it outside the window (30s)

In **any text field** — notes, mail, anywhere — type:

```
@minea what time is it?
```

Leave it a moment and MINEA replaces that line with the answer.
You don't have to open the app. Ask from wherever you already are.

---

## 3. Turn on "watching" (3 min + download)

This is the real thing. **Without it, it's just another chatbot.**

1. Open settings — the gear
2. Turn on **곁에서 지켜보기** ("watch alongside me")
3. Press the **준비** ("get ready") button once — it downloads the judgement model, **5.2GB**
   (A few minutes, depending on your connection. Steps 1 and 2 keep working while it downloads.)

Once it's down:

```
Your mail says "consultation, Tuesday next week, 3pm"
   → Tuesday 3pm — want me to put it in your calendar?   ← it speaks first
```

Click and it does it. Ignore it and it goes away. **It never adds anything without asking.**

> The judging happens **inside your Mac only**. What's on your screen never goes to the internet.
> That's what the 5.2GB is for.

---

## 4. The first few days are clumsy

It gets better as things accumulate — your schedule, your words, your rhythm.
**It really does improve with use.** The first few days are the worst it will ever be.

If it mishears a name, put it in settings → **잘못 들었을 때** ("when it misheard").
It will hear it right from then on.

---

## Common questions

**Does it work with other AI?**
The judging, calls, diary and tutoring that run inside your Mac already use **ollama**
(gemma, qwen). But the part that actually does things — edits your calendar, touches
files — is **Claude only**. ChatGPT isn't supported yet.

**Does it cost anything?**
You get **30 free runs** in the box. No card needed.
If you have a Claude account (Pro or Max), sign in once — from then on it runs
**on your subscription, with the stronger model**: the same setup the author uses.

**I don't want some of these features**
You can turn each one off in settings. Put anything annoying in **이건 알리지 마세요**
("don't tell me about this") and that category stops showing up. Things you'll never do go in
**안 하기로 하신 것** ("decided against") — those aren't even started.

**It talks to me too much**
Turn it off in settings, or put the noisy kind in **이건 알리지 마세요**.
It filters what you've listed from then on.

---

Stuck? Leave it in the **[issues](https://github.com/sujipar/minea/issues)** and it gets fixed.
