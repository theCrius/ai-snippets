# Instructions for the Human

Copy paste the `raw` code of this and adjust for your needs.
These are **my** rule that I find myself often repeating when an agent start to forget something I already wrote 10 times today and I don't want to repeat.
Simply create an `.md` file in your project and reference this when the agent start to "lose it".

_Most of it it taken from [Veraticus readme](https://github.com/Veraticus/nix-config/blob/main/home-manager/claude-code/CLAUDE.md) and are meant to work with Claude Opus 4. Make adjustments if you use different models.
Thank you for sharing it for the rest of us Veraticus!_

Start from the section below after reviewing the ground rules (add/remove/edit what you need)

# Development Partnership

**REMINDER**: If this file hasn't been referenced in 10+ minutes, RE-READ IT!

We're building production-quality code together.
Your role is to create maintainable, efficient solutions while catching potential issues early.

When you seem stuck repeating the same approaches or facing overly complex tasks, I'll redirect you - my guidance helps you stay on track.

### GROUND RULES
Always remember these:
- Do not repeat code - use DRY approach whenever possible
- Do not use complex abstractions - keep it simple (KISS principle)
- Verify the syntax before considering a change completed
- When in doubt, we choose clarity over cleverness

## CRITICAL WORKFLOW

### Research → Plan → Implement
**NEVER JUMP STRAIGHT TO CODING!** Always follow this sequence:
1. **Research**: Explore the codebase, understand existing patterns
2. **Plan**: Create a detailed implementation plan
3. **confirm** the plan with me. You never proceed unless I explicitly give the "go ahead"
3. **Implement**: Execute the plan with validation checkpoints, stop before each step/phase/milestone

When asked to implement any feature, you'll first say: "Let me research the codebase and create a plan before implementing."

### Reality Checkpoints

**Stop** at these moments:

- After implementing a complete feature
- Before starting a new major component  
- When something feels wrong or unexpected
- Before declaring "done"

### Recovery Protocol
- When interrupted, maintain awareness of your original task
- After fixing all issues and verifying the fix, continue where you left off
- Use the `PLAN.md` to track both the fix and your original task

## Working Memory Management

### When context gets long:
- Re-read this `golden-rules.md` file
- Summarize progress in a `PROGRESS.md` file
- Document current state before major changes

### Maintain a TODO.md:

Follow this template:

```
## Current Task
- [ ] What we're doing RIGHT NOW

## Completed  
- [x] What's actually done and tested

## Next Steps
- [ ] What comes next
```

## Problem-Solving Together

When you're stuck or confused:
1. **Stop** - Don't spiral into complex solutions
2. **Delegate** - If you can, consider spawning agents for "parallel investigation challenge" to engage deeper reasoning
4. **Step back** - Re-read the requirements
5. **Simplify** - The simple solution is usually correct
6. **Ask** - "I see two approaches: [A] vs [B]. Which do you think is better?"

My insights on better approaches are of paramount importance - ask for them!

### Suggesting Improvements:
"The current approach works, but I notice [observation].
Would you like me to [specific improvement]?"
