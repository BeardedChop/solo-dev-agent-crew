![Solo Dev Agent Crew](cover.jpg)

# Solo Dev Agent Crew

**Write one sentence before bed. Wake up to reviewed code.**

A 3-agent workflow that turns Claude Code (or any AI coding tool) into an overnight development team.

No infrastructure. No subscriptions. No code to write. Just prompts.

---

## What This Is

3 copy-paste prompts that run in sequence:

1. **Planner** → Analyzes your task and writes a detailed spec
2. **Builder** → Writes working code from the spec
3. **Reviewer** → Checks code against spec and flags issues

You write one sentence. They do the rest.

---

## Quick Start

```bash
mkdir crew
```

Copy the [all-in-one prompt](prompts/all-in-one.md) into Claude Code, Cursor, or Codex. Replace `[YOUR TASK HERE]` with something specific.

Hit enter. Go to sleep. Check `crew/review.md` in the morning.

---

## What's Included

| File | What |
|------|------|
| `prompts/planner.md` | Planner agent prompt |
| `prompts/builder.md` | Builder agent prompt |
| `prompts/reviewer.md` | Reviewer agent prompt |
| `prompts/all-in-one.md` | Single prompt for all 3 agents |
| `examples/todo-list/` | Real example outputs from a working run |

---

## Example

**Task:** "Add a todo list with add, complete, delete. Use React hooks."

**Result:** [See full example](examples/todo-list/)

- `plan.md` — detailed spec with tasks and acceptance criteria
- `build-log.md` — what got built and why
- `review.md` — **PASS** with optional nitpicks

---

## Who This Is For

- Solo devs who want to ship faster
- Vibe coders tired of context-switching
- Anyone who wants an "overnight crew" without building one

---

## Requirements

- Claude Code, Cursor, Codex, or any AI coding tool
- A project folder
- 5 minutes per night

---

## Want the Full Guide?

This repo has the prompts and examples. For the complete 8,000+ word guide with troubleshooting, advanced workflows, and more examples:

👉 [Get it on Gumroad](https://bchoplxxxii.gumroad.com/l/ibtmjx) (free — enter $0 at checkout)

---

MIT.

do whatever you want with this.

Built by [@BChopLXXXII](https://x.com/BChopLXXXII)

built for vibe coders who just want their AI to feel less... corporate.

**Ship while you sleep.** 🚀

if this helped, ⭐ the repo — it helps others find it.
