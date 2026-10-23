# Thin Muscle for Women (thin-muscle-women)

An AI strength coach skill for women. **It's not here to make you smaller. It's here so that at 40, and at 60, you can get up off the floor by yourself, carry your own groceries, and take a fall without breaking something.**

The lean-muscle protocols floating around the internet were written for men. This is that, rewritten for women — not relabeled, rebuilt:

| | Men's version | Women's version (this skill) |
|---|---|---|
| Priority order | shoulders > back > abs > chest > legs | **lower body > core > back > upper body** |
| Body fat | chase 10–13% | **hold 20–23%** (under 17% risks losing your cycle) |
| Supplements | generic advice | **muscle creatine stores run 70–80% lower than men's** — dosed separately |
| Physiology | not addressed | cycle, postpartum, pelvic floor, and bone density each have hard red lines |

---

## Install

It's **one file**. No dependencies, no API key.

```bash
# WorkBuddy / CodeBuddy
mkdir -p ~/.workbuddy/skills/thin-muscle-women
curl -L -o ~/.workbuddy/skills/thin-muscle-women/SKILL.md \
  https://raw.githubusercontent.com/LingganAI/thin-muscle-women/main/SKILL.en.md
```

Or clone the repo:

```bash
git clone https://github.com/LingganAI/thin-muscle-women.git
cp thin-muscle-women/SKILL.en.md ~/.workbuddy/skills/thin-muscle-women/SKILL.md
```

Note the rename: `SKILL.en.md` → `SKILL.md`. The skill folder always reads `SKILL.md`. Restart the conversation and it's live.

There is also an **`en/`** folder holding the same English build already named `SKILL.md`, for tools that only accept a directory:

```bash
cp -r en ~/.workbuddy/skills/thin-muscle-women-en
```

> Submitting to a skill marketplace? Point it at the `en/` folder, or upload `SKILL.en.md` as `SKILL.md`.

---

## How to use it

It is not a search box. You say one thing and it **takes over the conversation** — gathers your profile (age, height and weight, equipment, training history, cycle, goals), *then* writes a program. After that, one line per session and it handles the logging, the comparing, and the progression.

Open however you want:

> I want to look toned, but I'm scared of getting bulky.

> I only have a pair of 2 kg dumbbells. Can I still train?

> Here's what I ate today (photo) — did I hit my protein?

> Day two of my period. Should I train?

> I did 3×12 on squats last week. What should I do this week?

What it does:

- **Corrects the goal first** — lean and toned isn't thin. It's muscle plus low enough body fat to see it. The scale is the wrong instrument
- **Programs with what you actually own** — a pair of 2 kg dumbbells, a band, and bodyweight is enough. It runs progressive overload through six bodyweight dials (reps / tempo / leverage / range / pause / sets)
- **Guards progressive overload** — the single non-negotiable. Every session is a little heavier or one rep more
- **Keeps your numbers and settles up with you weekly** — girth and strength, never weight
- **Adjusts by cycle symptoms, not by calendar** (the evidence doesn't support universal cycle periodization)
- **Handles the eating too** — calories, protein, creatine, vitamin D, calcium, iron, in numbers
- **Carries the emotional load** — praise that lands on specifics, and no "girl," "queen," or "honey"

---

## Where this comes from

Not invented. It's written into Chapter 3 so it can be checked any time:

- **Delavier, *Guide des mouvements de musculation pour la femme*** — the strength author behind *Strength Training Anatomy* wrote an entire book for women, and it opens with the glutes
- **ROAR (Stacy Sims)** — female exercise physiology; the source of the 1.8–2.2 g/kg protein position and the opposition to fasted morning cardio
- **ISSN position stands** on protein and creatine — the checkable authority behind the numbers
- **ACSM 2026 position stand** on resistance training prescription — 1–2 sessions, 2–3 exercises, 1–3 sets each, and it works; plus the bone-density prescription
- **Li Ruotong** — a 26-year real-world case: started at 34, from a 20 kg deadlift, at the bottom of her life

On whether to periodize by menstrual cycle, two authorities disagree (ROAR says yes; RCT evidence says no). The skill shows the disagreement and takes the middle road: **adjust by symptoms, not by calendar.**

> The Chinese build of this skill cites 《运动营养学（第三版）》, a Chinese sports nutrition textbook. This English build substitutes the ISSN position stands — same job, but you can look them up in English.

---

## Printable cards

- `training-card.html` — A4, four pages: profile strip, the three-day split, progression ladders, girth tracker. Open in Chrome → Print → Save as PDF
- `wallpaper.html` — 1080×1920 phone wallpaper; screenshot it and set it as your lock screen

Both ship with blank underscores — print and write your own numbers in. Default rhythm is **three days a week (Mon / Wed / Fri), 30–40 minutes a session**.

---

## Disclaimer

General training and nutrition education, not medical advice. If you have cardiovascular disease, osteoporosis, pelvic floor dysfunction, are under 6 weeks postpartum, or are in treatment, talk to your doctor first. Learn the movement before loading it, and treat your own RPE as the final judge.

## License

MIT. Fork it, change it, use it — just credit the source.
