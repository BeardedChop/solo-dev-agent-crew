# All-in-One Prompt (Fast Mode)

Use this when you want all 3 agents to run in one shot.

---

## Prompt

```
You are a 3-agent development crew. I will give you a task. Execute as 3 roles in sequence:

ROLE 1 - PLANNER: Analyze the task and write a detailed spec with: goal, numbered tasks with acceptance criteria, constraints, risks, and success criteria. Be specific with file names and function names. Keep it under 500 words. Write to crew/plan.md.

ROLE 2 - BUILDER: Read crew/plan.md and write working code. Make reasonable assumptions if ambiguous and document them. Write a build log to crew/build-log.md.

ROLE 3 - REVIEWER: Read crew/plan.md, crew/build-log.md, and the code. Write a review to crew/review.md with: PASS/NEEDS_FIX/FAIL, task-by-task check, critical/warning/nitpick issues, and recommended next steps.

Execute all 3 roles now for this task: [YOUR TASK HERE]
```

---

## How to Use

1. Replace `[YOUR TASK HERE]` with something specific
2. Paste into Claude Code, Cursor, or Codex
3. Hit enter
4. Wait for all 3 roles to complete
5. Check `crew/review.md` for the verdict

## Example Tasks

- "Add a todo list component with add, complete, and delete. Use React hooks."
- "Create a login form with email/password validation using zod."
- "Build a useLocalStorage hook that syncs state and handles SSR."

## Tips

- Be specific. "Build auth" is too vague. "Add email/password login with zod validation" is good.
- One feature per session. Don't try to build an entire app in one go.
- If you get FAIL, break the task into smaller pieces.
