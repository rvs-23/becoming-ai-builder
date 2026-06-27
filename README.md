# Becoming an AI Builder

**TL;DR —** We use AI to build real things, then prove we can read, fix, and judge them *without* it. Eight arcs over the next year or two, each ending in a project worth showing off.

## Why we're changing things

For the past few years we learned coding the classic way. The world moved. AI can write code now, so the goal is no longer "type code fast." The goal is to **build real things with AI and still understand, fix, and judge them without it.** That skill is rare and valuable, and it's what we're building toward.

The shift in one line:

- Old signal of skill: write code unaided.
- New signal: build with AI and prove we understand it. Read it, test it, find its bugs, and know when it's wrong.

The old skill still matters. It's just not the whole game anymore.

## We're not making this up

Some strong programs are moving this way:

- **[Harvard's CS50](https://cs50.ai)** gives students a custom AI tutor (the CS50 Duck) that guides instead of handing over answers, and bars the outside auto-answer tools.
- **[AP Computer Science](https://apstudents.collegeboard.org/courses/ap-computer-science-a)** lets you learn with whatever tools you like, but the exam is closed — you read and write your own code, no AI.

The shared idea: use AI to build, prove we understand it without AI. That's our rule too.

## How we'll work

We work in **arcs**. An arc is a few weeks on one mission that ends in something we built and can show off. There are eight, and each one becomes a folder in the repo (`arc-1-builder-foundations`, `arc-2-data-claims`, and so on). We pick a theme we care about: games, basketball, finance, whatever's fun.

Here are the eight arcs, roughly the next year or two. We go for real understanding, not speed, so the pace can stretch when a topic deserves it.

| # | Arc | What we can do after |
|---|---|---|
| 1 | Builder Foundations | Own a real repo end-to-end: build a tested tool on real data, set up CI, handle git like a pro, and explain and fix it all without AI. |
| 2 | Data Claims | Make one honest claim from messy real data — with stats and a chart — and say what it doesn't prove. |
| 3 | SQLite App | Give an app a real memory; relational thinking. |
| 4 | Simulation & Probability | Model uncertainty with Monte Carlo; use probability as a tool. |
| 5 | Game Studio (second language) | Build a small browser game in TypeScript. |
| 6 | ML Without Magic | Train a simple model, beat a baseline, learn when to trust it. |
| 7 | Tiny LM Lab | Train a tiny model from scratch; the math comes with it. |
| 8 | AI Systems Capstone | A real AI app that answers from our own sources and shows its evidence. |

By the end we can take an idea, build it with AI, explain and fix it ourselves, tell whether AI's output is actually right, and ship projects worth being proud of.

## How the repo is organized

Everything lives in this one GitHub repo, organized by arc. One simple rule: **one folder per arc.** Each arc folder opens with a short README (the mission, what we built, what we learned), then the code.

```
becoming-ai-builder/
├── README.md              this file
├── brainstorm.md          ideas, themes, and things we want to build next
├── tracker.md             our class log and the tools/links we use
├── arc-1-builder-foundations/   we start here
│   ├── README.md          mission, what we built, notes
│   └── ...                project files
├── sandbox/               quick experiments and AI-off challenges
└── ...                    arc-2, arc-3, and so on, added as we go
```

We create an arc's folder only when we start it. When we finish an arc, its folder is something to show people.

## The AI rule

We can use AI. We're not going to pretend it doesn't exist. We use it in three modes, and I'll always say which one we're in:

- **AI off:** for basics, quick challenges, and showing what we know. This is how the skills actually stick.
- **AI hints:** when we're stuck, AI can nudge us, after we say what we think is wrong.
- **AI allowed:** for building real projects. We note what AI wrote, and we have to be able to explain it and change it on the spot.

One line to remember: **if we can't explain it, it isn't ours yet.**

## The deal, both ways

This only works if we're honest, with each other and with ourselves:

- No faking understanding. "I don't get this" is the most useful thing we can say.
- Do the small weekly task. It's short on purpose.
- When we use AI, we say so. No hiding it, and no shame in it.
- Flag anything boring or too hard. We fix it together.

My job: keep it interesting, tie it to things that matter to us, and never waste our time.

## Where we start

First up: we build a small tool, use AI on it once, then break it and fix it ourselves. Small, but that's the whole method in one go.

We keep a running log in [tracker.md](tracker.md) — what we did each class, and the tools and links we use. We add to it after every class.

Let's build.
