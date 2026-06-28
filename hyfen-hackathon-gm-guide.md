# Hyfen Mini Sprint — Game Master Guide

> Your reference for running the day. Each stage has **what to say**, **what to do**, and **what to hand out**. Read the SAY blocks more or less verbatim if you want, or riff off them.

**Two teams, two projects:**

- **Team A — Vuln fix automations**
- **Team B — Refinement & Review agents**

**Your role:** Game Master + wildcard freelancer. You float between teams. Each team must allocate you **2 hours on Day 1** and **45 minutes on Day 2** worth of tickets — you're a shared resource they have to scope work for, not an organiser hovering on the sidelines.

**What we measure:** every piece of work gets judged on two things — **token efficiency** (did we get the result without burning a fortune in tokens?) and **usefulness** (would we actually use this?). Flag this early and often so teams build with it in mind.

**Ticket management:** sticky notes are the source of truth on the wall. Mirror anything that produces a PR into Jira so we keep traceability — but the wall is where the day lives.

---

## Stage 0 — Kickoff
**Tuesday · 10:00–10:30 · Full team**

### SAY
> "Today and tomorrow we're not doing an experiment. We're building two things that are genuinely usable and not half-baked by the time we leave. Two teams, two projects.
>
> Team A is **vuln fix automations**. Team B is **refinement and review agents**.
>
> Here are the teams: *(read out the splits)*.
>
> Two ground rules. One — I'm a freelancer you can hire. Each team has to carve out **2 hours of my time on Day 1** and **45 minutes on Day 2**, as actual tickets. Scope me like you'd scope any contractor. If you don't give me work, that's on you.
>
> Two — everything we build gets judged on two axes: **is it token-efficient**, and **is it actually useful**. Keep both in your head the whole time. Clever but wasteful loses to simple and cheap."

### DO
- [ ] Read out the team splits clearly. Confirm everyone knows which team they're on.
- [ ] Point at the sticky-note wall. Explain: stickies = truth, Jira = anything that becomes a PR.
- [ ] Remind them of the hard timings: build stops at **17:00 today**, demos are **Wednesday 13:15**.
- [ ] Keep this under 30 minutes. Nobody wants a long kickoff.

### HAND OUT
- Sticky notes + markers per team
- A wall / board section per team

---

## Stage 1 — Refine & Plan
**Tuesday · 10:30–12:30 · Split teams**

### SAY
> "Next two hours is planning, not building. By the end of this I want to see on your wall: the scope, broken into shippable sticky-note tickets, and a clear definition of done.
>
> Two of those tickets are mine — 2 hours of work, scoped tight enough that I can pick them up and run. Same for Day 2: 45 minutes.
>
> Don't start coding yet. Two hours is plenty to plan a day's worth of work, and a good plan now saves you the afternoon."

### DO
- [ ] Get each team to write a one-line **definition of done** and stick it at the top of their wall.
- [ ] Check both teams have scoped your tickets (2h Day 1, 45m Day 2). Push back if they're vague.
- [ ] Sanity-check scope against the clock — ~6 hours of build Day 1, ~2 hours Day 2. Cut anything that won't land.
- [ ] Make sure PR-producing tickets have a matching Jira ticket.

### HAND OUT
- The **GM ticket cards** (below) for each team to fill in for your time.

---

## Stage 2 — Pre-build briefing
**Tuesday · ~13:10 · Quick all-hands before heads-down**

### SAY
> "Before you dive in — two reminders that decide how we score this.
>
> **Token efficiency.** Keep a rough eye on what you're spending. The goal isn't to use the fanciest model for everything — it's to get a useful result without setting money on fire. We'll ask about this at the end.
>
> **Usefulness.** If it works but nobody would ever turn it on, it failed. Build the thing you'd actually keep.
>
> Optional team check-in around 15:30 — 15 minutes max, just to surface blockers. Find me when you've got tickets for me."

### DO
- [ ] State the two measures one more time. This is the moment it sticks.
- [ ] Agree a loose check-in time (~15:30) with each team.
- [ ] Start working your Day 1 tickets.

---

## Stage 3 — Build Sprint 1
**Tuesday · 13:15–17:00 · Parallel execution**

### DO
- [ ] Float between teams. Unblock, don't hover.
- [ ] Deliver your 2 hours of scoped tickets.
- [ ] Around 15:30, run the optional 15-min check-in per team: *What's done? What's blocked? Will we hit 80% by 17:00?*
- [ ] **Hard stop at 17:00.** No commits after this — the BBQ is on.

### SAY (at 17:00)
> "Laptops down. We want to be roughly 80% there — tomorrow morning is short and you do not want to start fresh with a hangover. Great work. BBQ time."

---

## Stage 4 — BBQ & party
**Tuesday evening · at the venue**

No agenda. No PRs. Eat, drink, switch off. (You're staying at the venue, so this is the night for it.)

---

## Stage 5 — Slow start
**Wednesday · 10:00–10:30 · Full team**

### SAY
> "No standup, no agenda. Get coffee, remember what you were building, ease back in. We've got two hours of build then we wrap."

### DO
- [ ] Keep it genuinely light. People may be fragile.
- [ ] Don't force structure — just let people re-find their thread.

---

## Stage 6 — Build Sprint 2 — finish & polish
**Wednesday · 10:30–12:30 · Split teams**

### SAY
> "This is finish-and-polish, not new features. Make the happy path work, wrap loose ends, and write one sentence of docs so this doesn't die after today. Hard stop at 12:30 to prep demos.
>
> Anyone got the last 45 minutes of my time scoped? Now's the moment."

### DO
- [ ] Deliver your 45 minutes of Day 2 tickets.
- [ ] Discourage new features. Ruthlessly. The day is about a working thing, not a bigger thing.
- [ ] Nudge each team toward a demoable state.
- [ ] **Hard stop at 12:30.**

---

## Stage 7 — Lunch & demo prep
**Wednesday · 12:30–13:15 · Full team**

### SAY
> "Eat, then each team takes 15 minutes to agree who's presenting and what. Live walkthrough only — no slides. Show the thing working."

### DO
- [ ] Each team picks presenter(s) and a demo path.
- [ ] Remind them: present however you like, but it has to be a live demo of the real thing.

---

## Stage 8 — Show & Tell + the vote
**Wednesday · 13:15–14:15 · Both teams present**

### SAY
> "Each team gets the floor — present however you want. When you're done, the **whole team votes**: would we actually use this? Majority passes or fails. No hard feelings — a 'no' just means it needs more before it's real.
>
> While you watch, the evaluators are scoring the *other* team on the card."

### DO
- [ ] ~20 min demo + ~10 min Q&A per team.
- [ ] After each demo, run the **use-it vote**: everyone votes yes/no. **Majority decides.** Record the result.
- [ ] Make sure the three evaluators (you + one from each team) are filling the **cross-team scorecard** (below) during the *other* team's demo.

### THE USE-IT VOTE

| | Team A — Vuln automations | Team B — Refinement & review |
|---|---|---|
| Votes **for** use | | |
| Votes **against** | | |
| **Verdict** (majority) | ☐ Use it ☐ Not yet | ☐ Use it ☐ Not yet |

---

## Stage 9 — Retrospective
**Wednesday · 14:15–15:00 · Full team**

Run it in two halves. First the work, then the people.

### Part A — The work (standard retro)

Four columns on the wall, sticky notes, everyone contributes:

| What went well | What went badly | What could be improved | What we'll action |
|---|---|---|---|
| | | | |

> Push for the **action** column to be concrete — owner + a real Jira ticket, not "we should think about X."

### Part B — The people (the interesting half)

This is the part that makes a small team stronger. Go round the room.

**About yourself / your team:**
- What did you discover you're good at this sprint?
- What did you struggle with?

**About your colleagues:**
- What did a teammate do really well that you noticed?
- What did you learn about how a colleague's *work* actually happens — something you didn't appreciate before?

> Keep this generous and specific. The goal is "I didn't realise how much goes into Dante's legal flow" or "Rick's eye for acceptance criteria saved us," not vague praise.

### DO
- [ ] Timebox Part A to ~20 min, Part B to ~20 min.
- [ ] Capture the action items as real tickets before anyone leaves.
- [ ] Close out. Done at 15:00. Go home — or finish the leftovers.

---

# Appendix A — GM ticket cards

Hand one set to each team. They scope your time as if hiring a contractor.

### Team A — your tickets for the GM

| | Day 1 (2 hrs total) | Day 2 (45 min total) |
|---|---|---|
| **Ticket title** | | |
| **What "done" looks like** | | |
| **Jira ref (if PR)** | | |

### Team B — your tickets for the GM

| | Day 1 (2 hrs total) | Day 2 (45 min total) |
|---|---|---|
| **Ticket title** | | |
| **What "done" looks like** | | |
| **Jira ref (if PR)** | | |

---

# Appendix B — Cross-team scorecard

**Three evaluators:** you (GM) + one member from each team. Each evaluator scores the **other** team (you score both). Rate 1–5, then total.

### Scoring Team A — Vuln fix automations

| Criterion | What you're judging | Score (1–5) |
|---|---|---|
| **Usefulness** | Would we actually turn this on and use it? | |
| **Token efficiency** | Result vs. tokens burned — lean or wasteful? | |
| **Does it work** | Is there a real, working happy path? | |
| **Completeness** | How close to genuinely shippable? | |
| **Presentation** | Did the demo show the thing clearly? | |
| **Wildcard** | Anything that impressed you — ambition, polish, cleverness | |
| | **TOTAL (out of 30)** | |

### Scoring Team B — Refinement & review agents

| Criterion | What you're judging | Score (1–5) |
|---|---|---|
| **Usefulness** | Would we actually turn this on and use it? | |
| **Token efficiency** | Result vs. tokens burned — lean or wasteful? | |
| **Does it work** | Is there a real, working happy path? | |
| **Completeness** | How close to genuinely shippable? | |
| **Presentation** | Did the demo show the thing clearly? | |
| **Wildcard** | Anything that impressed you — ambition, polish, cleverness | |
| | **TOTAL (out of 30)** | |

### Final tally

| | Team A | Team B |
|---|---|---|
| Evaluator 1 (GM) | | |
| Evaluator 2 | | |
| Evaluator 3 | | |
| **Combined total** | | |
| **Use-it vote verdict** | | |

> The scorecard and the use-it vote are two different signals. A team can score high and still get a "not yet" on the vote, or vice versa. Read them together when you decide what actually carries forward into a real ticket.

---

# Quick timing cheat sheet

| Time | Stage |
|---|---|
| **Tue 10:00** | Kickoff |
| **Tue 10:30** | Refine & plan |
| **Tue 13:10** | Pre-build briefing (token + useful) |
| **Tue 13:15** | Build sprint 1 → deliver your 2 hrs |
| **Tue 15:30** | Optional check-ins |
| **Tue 17:00** | Hard stop → BBQ |
| **Wed 10:00** | Slow start |
| **Wed 10:30** | Build sprint 2 → deliver your 45 min |
| **Wed 12:30** | Hard stop → lunch + demo prep |
| **Wed 13:15** | Show & tell + use-it vote + scoring |
| **Wed 14:15** | Retrospective (work, then people) |
| **Wed 15:00** | Done |
