# Learn Anything 🧠

**Learn anything. Remember everything.**

An OpenClaw skill that helps anyone learn any topic efficiently using proven learning science methods.

[**→ Install on ClawHub**](https://clawhub.ai/thinktankglobalbot/learn-anything)

## What It Does

- **Generate Learning Paths** — Break any topic into logical milestones
- **Curate Resources** — Find the best free learning materials
- **Quiz for Retention** — Create practice questions for active recall
- **Track Progress** — Update learning journal with spaced repetition

## Quick Start

```
"Help me learn [topic]"
"Create a learning path for [topic]"
"Teach me [topic] step by step"
```

## Example Topics

- Programming (Python, JavaScript, Rust...)
- Languages (Tagalog, Japanese, Spanish...)
- Skills (trading, cooking, photography...)
- Concepts (machine learning, economics, psychology...)

## Learning Methods Used

- **Spaced Repetition** — Review at optimal intervals
- **Feynman Technique** — Explain in simple terms
- **Active Recall** — Quiz yourself, don't just re-read
- **Interleaving** — Mix related topics
- **Pomodoro** — Focused 25-min sessions

## Installation

```bash
clawhub install learn-anything
```

Or manually:
```bash
git clone https://github.com/thinktankglobalbot/learn-anything-skill.git
cp -r learn-anything-skill ~/.openclaw/skills/learn-anything
```

## Skill Structure

```
learn-anything/
├── SKILL.md                        # Core skill instructions
├── references/
│   ├── learning-methods.md         # Deep dive on learning science
│   └── learning-path-templates.md  # Pre-built paths for 5 topics
├── scripts/
│   └── generate-quiz.py            # Quiz generator
└── assets/
    └── learning-path-template.md   # Progress tracker template
```

## Pre-Built Learning Paths

Get started fast with templates for:
- **Python Programming** (Beginner → Intermediate)
- **JavaScript/React** (Web development)
- **Spanish** (Conversational)
- **Machine Learning** (Basics)
- **Financial Investing** (Fundamentals)

Each template includes 4-week milestones, free resources, and quiz checkpoints.

## Why This Works

Most learning fails because:
- **Cramming doesn't work** — 90% forgotten within a week
- **Passive review is weak** — Re-reading ≠ remembering
- **No system** — Without structure, you quit

Learn Anything uses:
- ✅ **Spaced repetition** — Review at optimal intervals
- ✅ **Active recall** — Quiz yourself, struggle = learning
- ✅ **Feynman technique** — Explain simply to understand deeply

## Example Output

**Input:** "Help me learn Python basics"

**Output:** 4-milestone learning path with:
- Resources (free courses, books, videos)
- Key concepts for each milestone
- Practice exercises
- Quiz questions
- Spaced repetition schedule

## Contributing

Issues and PRs welcome! Areas to improve:
- More quiz types
- Additional learning methods
- Topic-specific templates
- Progress tracking improvements

## License

MIT — use freely, modify, share.

---

Built with 🦀 for OpenClaw
