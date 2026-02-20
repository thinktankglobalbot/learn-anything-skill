# Learn Anything 🧠

An OpenClaw skill that helps anyone learn any topic efficiently using proven learning science methods.

## What It Does

- **Generate Learning Paths** — Break any topic into logical milestones
- **Curate Resources** — Find the best free learning materials
- **Quiz for Retention** — Create practice questions for active recall
- **Track Progress** — Update learning journal with spaced repetition
- **Anki Export** — Generate flashcards for spaced repetition apps

## Quick Start

```
"Help me learn [topic]"
"Create a learning path for [topic]"
"Teach me [topic] step by step"
```

## Installation

### Via ClawHub (recommended)
```bash
clawhub install learn-anything
```

### Manual
```bash
git clone https://github.com/your-username/learn-anything-skill.git
cp -r learn-anything-skill ~/.openclaw/skills/learn-anything
```

## Skill Structure

```
learn-anything/
├── SKILL.md                        # Core skill instructions
├── references/
│   ├── learning-methods.md         # Deep dive on learning science
│   ├── anki-export.md              # Flashcard integration guide
│   └── topic-templates.md          # Templates by topic type
├── scripts/
│   └── generate-quiz.py            # Quiz generator
└── assets/
    └── learning-path-template.md   # Progress tracker template
```

## Example Usage

**Input:** "Help me learn Python basics"

**Output:** 4-milestone learning path with:
- Resources (free courses, books, videos)
- Key concepts for each milestone
- Practice exercises
- Quiz questions
- Spaced repetition schedule

## Learning Methods Used

- **Spaced Repetition** — Review at optimal intervals
- **Feynman Technique** — Explain in simple terms
- **Active Recall** — Quiz yourself, don't just re-read
- **Interleaving** — Mix related topics
- **Pomodoro** — Focused 25-min sessions

## Topic Types Supported

| Type | Example Topics |
|------|----------------|
| Programming | Python, JavaScript, Rust |
| Languages | Tagalog, Japanese, Spanish |
| Technical | Trading, Design, Data Science |
| Academic | Economics, Psychology, Math |
| Physical | Guitar, Tennis, Drawing |

## Contributing

Issues and PRs welcome! Areas to improve:
- More quiz types
- Additional topic templates
- Progress tracking improvements
- Integration with more flashcard apps

## License

MIT — use freely, modify, share.

---

Built with 🦀 for OpenClaw
