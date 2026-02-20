---
name: learn-anything
description: Learn any topic efficiently with AI-powered learning paths, resource curation, summarization, and quizzing. Use when the user wants to learn something new, study a topic, create a learning plan, find learning resources, or get help with spaced repetition and active recall. Triggers: "help me learn X", "I want to study X", "create a learning path for X", "teach me X", "how do I learn X".
---

# Learn Anything

Learn any topic efficiently using proven learning science methods.

## Quick Start

**Basic usage:**
```
"Help me learn [topic]"
"Create a learning path for [topic]"
"Teach me [topic] step by step"
```

**Examples:**
- "Help me learn Python programming"
- "I want to understand options trading"
- "Create a learning path for Japanese"
- "Teach me about machine learning"

## Core Workflow

When the user wants to learn something:

1. **Clarify goal** — What specifically do they want to achieve? How deep?
2. **Assess level** — Beginner, intermediate, or advanced?
3. **Generate learning path** — Break topic into logical progression
4. **Curate resources** — Find best free resources (articles, videos, docs)
5. **Summarize content** — Distill key concepts
6. **Quiz for retention** — Generate questions for active recall
7. **Track progress** — Update learning journal

## Learning Path Structure

Generate paths with:
- **Milestone** — Clear checkpoint/goal
- **Resources** — 2-3 best free resources for this step
- **Key concepts** — What to understand
- **Practice** — How to apply
- **Quiz** — Self-check questions

**Example output:**
```
## Learning Path: Python for Beginners

### Milestone 1: Fundamentals (1-2 weeks)
Resources:
- Python.org tutorial (official)
- "Automate the Boring Stuff" - free online book

Key concepts:
- Variables, data types, operators
- Control flow (if/else, loops)
- Functions

Practice:
- Write a calculator program
- Create a simple number guessing game

Quiz:
1. What's the difference between a list and a tuple?
2. How do you define a function with default parameters?

### Milestone 2: Data Structures (1-2 weeks)
...
```

## Learning Methods

Apply these proven techniques:

### Spaced Repetition
- Review material at increasing intervals: 1 day → 3 days → 1 week → 2 weeks
- Suggest review schedule when user completes a milestone

### Feynman Technique
- Ask user to explain concept in simple terms
- Identify gaps in their understanding
- Refine explanation until clear

### Active Recall
- Generate quiz questions, not just summaries
- Ask user to retrieve info, not re-read
- Use flashcard-style prompts

### Interleaving
- Mix related topics rather than blocking
- E.g., alternate between Python and JavaScript concepts

### Pomodoro
- Suggest 25-min focused sessions with 5-min breaks
- Track session count for complex topics

## Commands

| Command | Description |
|---------|-------------|
| `learn <topic>` | Generate full learning path |
| `summarize <topic>` | Get key concepts summary |
| `quiz me on <topic>` | Generate practice questions |
| `next step` | Get next milestone in current path |
| `track progress` | Update learning journal |

## Learning Journal

Track progress in `learning-journal.md`:
```markdown
## [Topic] - Started [Date]

### Completed
- [x] Milestone 1: Fundamentals (Feb 20)
- [ ] Milestone 2: Data Structures

### Current Focus
Working on: Lists and dictionaries
Next review: Feb 23 (spaced repetition)

### Quiz Results
- Feb 20: 8/10 on fundamentals quiz
```

## References

For detailed learning science, see:
- `references/learning-methods.md` — Deep dive on techniques
- `references/quiz-templates.md` — Quiz generation patterns

## Scripts

- `scripts/generate-quiz.py` — Create quizzes from content
- `scripts/track-progress.py` — Update learning journal

## Tips

- **Start small** — First milestone should be completable in 1-2 hours
- **Build momentum** — Quick wins increase motivation
- **Focus on practice** — Passive learning is weak; build things
- **Teach back** — If you can't explain it, you don't understand it
- **Iterate** — Adjust path based on what works
