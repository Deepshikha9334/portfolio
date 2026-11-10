---
name: karpathy-guidelines
description: Coding discipline inspired by Andrej Karpathy's observations on common LLM coding mistakes. Use whenever writing, editing, refactoring or reviewing code in this repository.
---

# Karpathy coding guidelines

Four habits that avoid the most common mistakes AI coding assistants make.

## 1. Think before coding
- State your assumptions out loud. If something is unclear, ask instead of guessing.
- If there are several reasonable ways to read the request, name them and pick one, or ask.
- Push back when a simpler approach exists or the request seems to be heading the wrong way.

## 2. Keep it simple
- Write the least code that solves the problem as asked.
- No features, options, abstractions or "future-proofing" nobody asked for.
- If 200 lines could be 50, rewrite it.

## 3. Make surgical changes
- Touch only what the task needs. Don't reformat, rename or "improve" neighbouring code.
- Match the existing style, even if you would write it differently.
- Clean up only the mess your own change created (unused imports, dead variables).
- Mention unrelated problems you notice; don't fix them unasked.

## 4. Work toward a checkable goal
- Turn the task into a success criterion you can verify (a test, a page that renders, a command that passes).
- For multi-step work, write a short plan with a check after each step.
- Don't call it done until the check passes, and report honestly if it doesn't.
