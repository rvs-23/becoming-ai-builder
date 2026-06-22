# How This Works

Read this once before we start. It's short.

## Why we're changing things

For three years we learned coding the classic way. The world moved. AI can write code now, so the goal is no longer "type code fast." The goal is to **build real things with AI and still understand, fix, and judge them without it.** That skill is rare and valuable, and it's what we're building toward.

The shift in one line:

- Old signal of skill: write code unaided.
- New signal: build with AI and prove we understand it. Read it, test it, find its bugs, and know when it's wrong.

The old skill still matters. It's just not the whole game anymore.

## We're not making this up

Some strong programs are moving this way:

- **Harvard's CS50** gives students a custom AI tutor that guides instead of handing over answers, and blocks the auto-answer tools.
- **AP Computer Science** lets students use AI to build, but they have to explain their own code on a closed exam.

The shared idea: use AI to build, prove we understand it without AI. That's our rule too.

## How we'll work

We work in **arcs**. An arc is a few weeks on one mission that ends in something we built and can show off. We pick a theme we care about: games, basketball, finance, whatever's fun. Every Sunday should feel like a mission, not a lecture.

Here's roughly the next year or two. We go for real understanding, not speed, so the pace can stretch when a topic deserves it.

1. **Code sense:** build a small tool of our own, the right way (tests, clean code, our AI rules).
2. **Data claims:** take real data and prove one true thing with a chart we can defend.
3. **Databases:** give an app a real memory that remembers and links our data (SQLite).
4. **Simulation:** run something thousands of times to answer "what are the odds?" (a streak, a game, a market).
5. **Game studio:** build a real browser game people can actually play, in a second language (TypeScript).
6. **Machine learning:** train our first model to predict something, and learn when not to trust it.
7. **Tiny LM lab:** build a tiny text-predictor from scratch. Small, but it's one of the core ideas behind ChatGPT.
8. **AI app capstone:** ship a real AI app that answers from our own sources, shows its evidence, and says "I don't know" when it should.

By the end we can take an idea, build it with AI, explain and fix it ourselves, tell whether AI's output is actually right, and ship projects worth being proud of.

## How the repo is organized

Everything lives in this one GitHub repo, organized by arc. One simple rule: **one folder per arc.** Each arc folder opens with a short README (the mission, what we built, what we learned), then the code.

```
becoming-ai-builder/
├── README.md              this file
├── brainstorm.md          ideas, themes, and things we want to build next
├── arc-1-code-sense/      we start here
│   ├── README.md          mission, what we built, notes
│   └── ...                project files
├── sandbox/               quick experiments and AI-off challenges
└── ...                    arc-2, arc-3, and so on, added as we go
```

We only create an arc's folder when we start it, so the repo never looks scary up front. When we finish an arc, its folder is something to show people. By the end there will be eight of them.

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

Let's build.
