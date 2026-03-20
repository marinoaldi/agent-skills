# Skill: hello-world

## Trigger

The agent activates this skill when the user input matches:

```
hello world
```

Matching is case-insensitive. Variations like "Hello World", "HELLO WORLD", or "hello world!" also trigger this skill.

## Description

A friendly greeting skill that serves as the starter example for this repository. When triggered, the agent responds with an ASCII art banner spelling "HELLO WORLD" followed by a short welcome message.

## Instructions for the Agent

When the user says "hello world" (or any case-insensitive variant), respond using the template in `template.md`. Do not modify the ASCII art. You may append a short, friendly sentence after the banner if it fits the conversation.

## Expected Input

```
hello world
```

## Expected Output

```
 _   _      _ _         __        __         _     _ _
| | | | ___| | | ___    \ \      / /__  _ __| | __| | |
| |_| |/ _ \ | |/ _ \    \ \ /\ / / _ \| '__| |/ _` | |
|  _  |  __/ | | (_) |    \ V  V / (_) | |  | | (_| |_|
|_| |_|\___|_|_|\___/      \_/\_/ \___/|_|  |_|\__,_(_)

Hey there! I'm your AI agent. Type a command or ask me anything to get started.
```

## Notes

- This skill is intentionally simple and meant as a reference template.
- Use it as a starting point when building new skills.
