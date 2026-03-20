# hello-world

> A friendly greeting skill — the starter example for the agent-skills repository.

---

## Overview

The **hello-world** skill triggers when a user sends the message `hello world` (case-insensitive). The agent responds with an ASCII art banner spelling "HELLO WORLD" followed by a short welcome message.

This skill is intentionally simple. Its purpose is to demonstrate the structure of a skill in this repository and serve as a copy-paste starting point for new skills.

---

## Files

| File | Description |
|------|-------------|
| `skill.md` | Skill definition: trigger, instructions, and expected I/O |
| `template.txt` | The ASCII art output the agent returns |
| `README.md` | This documentation file |

---

## How It Works

1. The user sends: `hello world`
2. The agent detects the trigger phrase (case-insensitive match)
3. The agent returns the contents of `template.txt`

---

## Example

**Input:**

```
hello world
```

**Output:**

```
 _   _      _ _         __        __         _     _ _
| | | | ___| | | ___    \ \      / /__  _ __| | __| | |
| |_| |/ _ \ | |/ _ \    \ \ /\ / / _ \| '__| |/ _` | |
|  _  |  __/ | | (_) |    \ V  V / (_) | |  | | (_| |_|
|_| |_|\___|_|_|\___/      \_/\_/ \___/|_|  |_|\__,_(_)

Hey there! I'm your AI agent. Type a command or ask me anything to get started.
```

---

## How to Use

Copy the contents of `skill.md` into your agent's system prompt or instruction set. The agent will use `template.txt` as the response format whenever the trigger phrase is detected.

---

## Notes

- The ASCII art is designed to render correctly in monospace fonts (terminals, code editors, chat interfaces with fixed-width rendering).
- This skill has no external dependencies.
- Extend this skill by adding personalization logic or localized greetings if needed.
