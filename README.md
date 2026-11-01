# AAIA Tech Panel — Proposal (Draft for Comment)

:::info
**Status:** Draft — open for comments
**Core group:** 5 members 
**How to give feedback:** Select any text and add a comment, or add to the *Open Questions* section at the bottom.
:::

[TOC]

---

## 1. Purpose

A recurring, hands-on technical discussion panel for AAIA members. The focus is **deep dives with real, practical experience**, not slide-only talks. Each session should leave attendees with something they can try themselves.

## 2. Format

| Item | Proposal |
|---|---|
| Frequency | Twice a month |
| Duration | 1 hour |
| Mode | Virtual (link shared via Luma) |
| Recording | TBD — see Open Questions |

### Session agenda (60 min)

| Time | Segment | Notes |
|---|---|---|
| 0:00–0:05 | **What's New** | Open floor: anything anyone heard, read, or tried that's new. Each item gets logged in the GitHub "What's New" log so it's not lost in chat. |
| 0:05–0:45 | **Deep Dive** | Presenter-led, hands-on: live demo, code walkthrough, or guided exercise. |
| 0:45–0:55 | **Q&A / Discussion** | Open questions, lessons learned, "how would you do this at your org?" |
| 0:55–1:00 | **Wrap-up** | Confirm next session's topic and presenter; note follow-ups. |

> *All timings are suggestions — please comment if you'd split it differently.*

## 3. Where things live

| What | Where | Why |
|---|---|---|
| Session schedule, RSVPs, reminders | **Luma** calendar | People subscribe once and get every session automatically — no forwarding in WhatsApp/email. |
| Session materials, code, setup steps | **GitHub** (one folder per session) | Hands-on content stays versioned and reusable. |
| "What's New" log | **GitHub** (single running file or Discussions thread) | Everything mentioned in the first 5 minutes is captured with links. |
| Topic suggestions & voting | **GitHub** Discussions | Anyone can propose; upvotes help prioritize. |
| WhatsApp / email | **One pinned link** only | Points to Luma. No session details posted there. |

> *GitHub location is TBD — if AAIA has an official org, we'll use it; otherwise we'll start a temporary org and transfer it later.*

### Proposed repo structure

```
aaia-tech-panel/
├── README.md              ← overview, how to join, links to Luma
├── whats-new.md           ← running log from the first 5 min of each session
├── sessions/
│   ├── 2026-11-session-01-<topic>/
│   │   ├── README.md      ← summary, prerequisites, setup steps
│   │   ├── slides/
│   │   └── code/
│   └── ...
└── templates/
    └── session-template.md
```

## 4. How topics get chosen

1. Anyone posts a topic idea in GitHub Discussions using the template below.
2. Members upvote ideas they want.
3. The core group picks the next 2–4 topics each month, balancing votes and presenter availability.
4. The chosen topic gets a Luma event and a GitHub session folder.

### Topic suggestion template

```markdown
**Topic:**
**Why it matters / what attendees will learn:**
**Hands-on component (demo, code, exercise):**
**Level:** Beginner / Intermediate / Advanced
**Prerequisites for attendees:**
**Who could present:** (yourself, someone you'd recommend, or "need a presenter")
```

## 5. Roles (per session)

| Role | Responsibility |
|---|---|
| **Presenter** | Prepares and runs the deep dive; uploads materials to the session folder. |
| **Host / Moderator** | Runs the clock, facilitates What's New and Q&A. |
| **Scribe** | Logs What's New items and key takeaways into GitHub. |
| **Organizer** | Creates the Luma event, confirms presenter, sends any reminders. |

> *Roles can rotate among the core group and volunteers.*

## 6. Session page template (for each GitHub session folder)

```markdown
# Session <#>: <Topic>
**Date:** | **Presenter:** | **Level:**
**Luma link:** | **Recording:** (if any)

## What you'll learn
## Prerequisites / setup (do before the session)
## Walkthrough
## Key takeaways
## Resources & links
## Follow-up questions
```

## 7. Open Questions — please weigh in

- [ ] **Who organizes?** One rotating organizer per month, or a fixed owner?
- [ ] **GitHub home:** Does AAIA have an official GitHub org we should use?
- [ ] **Day and time:** What works across time zones (if chapters in multiple regions attend)?
- [ ] **Recording:** Record sessions? If yes, where are recordings hosted, and do presenters opt in?
- [ ] **Audience:** Open to all AAIA members, specific chapters, or invite-only to start?
- [ ] **Presenter pipeline:** How far ahead should topics be locked in?
- [ ] **Session length:** Is 1 hour enough for hands-on content, or should some sessions run 90 min?
- [ ] **Anything missing?**

---
*Last updated: Oct 18, 2026*
