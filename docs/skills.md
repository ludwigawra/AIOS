# Skills catalog

Every skill that ships in this repo, grouped by how it is installed. If a skill is not on this
page, it is not in the plugin. Anything you need that is missing is a job for `forge-skill`.

Core skills install for everyone. Optional skills install only when you connect the integration
they depend on. Meta skills manage AI-OS itself.

---

## Core

### `memory-search`
Search the brain before starting work. Finds people, companies, decisions, projects and prior
sessions relevant to what you are about to do, and loads them as context.

### `decision-check`
Surfaces prior decisions that touch what you are considering now, so you do not quietly
contradict yourself six weeks later.

### `project-status`
Status read on any project: cadence from git history, open commitments, blockers, next concrete
action, and an honest classification including stalled and abandoned quietly.

### `reflect`
Goal-by-goal progress with verdicts, patterns, contradictions and course corrections. Includes a
`What went unsaid` section. Tone is configurable, flattery is not.

### `foresight`
Ranked priorities for the period ahead, filtered through five lenses and forced to drop at least
one thing. Cross-checks against your learned patterns before it commits.

### `nightly-consolidation`
Processes short-term memory, routes content to the right region, extracts patterns from
corrections, and edits skills that received feedback. This is the loop that makes the system
improve while you sleep.

### `signal-calibration`
The brain tuning its own signal detector. Compares what was flagged against what actually
mattered in archived sessions, then proposes changes with citations. Applying them requires
explicit confirmation.

---

## Autonomy

Core skills, but they act rather than report. Read each one before enabling it.

### `nightly-goal-pursuit`
Moves stated goals forward overnight and records what it did in an autonomous-runs ledger.

### `behavioral-learning`
Learns how you actually work from your sessions, rather than from what you said you wanted.

### `auto-outreach-queue`
Drafts outreach and queues it for review. It never sends anything.

---

## Optional

Installed only if the matching integration is connected during setup.

### `meeting-prep` (calendar)
One-screen brief before a meeting: who is attending, what you have done with them, open threads
in both directions, and risk flags. A brief longer than one screen has failed.

### `relationship-check`
Last contact, cadence verdict, open commitments both ways, recent topics and a next action for
one person. Respects do-not-contact before anything else.

---

## Meta

### `aios-start`
Conversational setup. Scaffolds the brain folder, personalises `CLAUDE.md`, wires the session
hooks and writes a live setup checklist.

### `aios-help`
Tour the system, check what is set up, ask anything about how AI-OS works.

### `aios-explore`
Shows what the system can do from where you are today, based on what your brain already holds.

### `aios-update`
Updates skills and hooks without touching memory, learning, knowledge or projects. Detects your
own edits before overwriting, and rolls back on any failure.

### `forge-skill`
Builds a new skill for something you do repeatedly. This is how routines like a morning briefing,
inbox triage or content drafting get made, because those depend on your mail, your calendar and
your tooling rather than on anything this repo can ship blind.

---

## How skills improve

Skills are markdown, not code. When you give feedback on a skill's output, it is logged to
`learning/skill-feedback/`. Once enough feedback accumulates on one skill, the nightly
consolidation edits that skill file. Small adjustments happen automatically. Larger changes are
queued for you to approve. The skill you run next month is not the skill you installed.
