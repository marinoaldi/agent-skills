# agent-skills

A public collection of reusable skills for AI agents — clean, well-documented, and easy to extend.

---

## What Is This Repository?

**agent-skills** is an open collection of plug-and-play skills designed for AI agents. Each skill encapsulates a specific behavior: an input trigger, an output template, and a short explanation of how the skill works. The goal is to build a shared library that developers can drop into their own agents with minimal effort.

---

## What Is a Skill?

A **skill** in this repository is a self-contained unit of agent behavior. It typically includes:

| File | Purpose |
|------|---------|
| `skill.md` | Defines the skill: trigger, description, and expected output |
| `template.txt` | The output template the agent uses when the skill fires |
| `README.md` | Short documentation explaining how the skill works |

Skills are intentionally simple and focused on a single responsibility.

---

## Folder Structure

```
agent-skills/
├── skills/
│   └── hello-world/
│       ├── skill.md        # Skill definition (trigger + instructions)
│       ├── template.txt    # ASCII art output template
│       └── README.md       # Skill documentation
├── LICENSE
└── README.md
```

---

## Getting Started

1. **Browse** the [`/skills`](./skills) folder and pick the skill you want.
2. **Read** the skill's `README.md` to understand the trigger and expected output.
3. **Copy** the `skill.md` content into your agent's prompt or instruction set.
4. **Use** the `template.txt` as the output format your agent should return.

No dependencies, no build step — just copy, paste, and adapt.

---

## Available Skills

| Skill | Trigger | Description |
|-------|---------|-------------|
| [hello-world](./skills/hello-world/) | `hello world` | Greets the user with a friendly ASCII art banner |

---

## Next Ideas

Future skills planned for this repository:

- **date-time** — Returns the current date and time in a formatted response
- **joke** — Tells a short, developer-friendly joke
- **weather-summary** — Summarizes weather data in plain language
- **motivational-quote** — Returns a random motivational quote
- **code-explainer** — Explains a given code snippet step by step
- **todo-list** — Helps the user manage a simple to-do list

---

## Contributing

Contributions are welcome! To add a new skill:

1. Create a folder under `/skills/your-skill-name/`
2. Add a `skill.md` file with the trigger and output instructions
3. Add a `template.txt` if the skill uses a fixed output format
4. Add a `README.md` explaining how the skill works
5. Update the **Available Skills** table in the root `README.md`
6. Open a pull request with a clear description

Please keep skills focused, English-only, and well-documented.

---

## License

This project is licensed under the [MIT License](./LICENSE).
