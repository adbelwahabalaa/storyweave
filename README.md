# Storyweave

> An AI agent skill that builds story outlines through guided conversation, using classic narrative templates.

![Skill Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-OpenClaw%20%7C%20Claude%20Code%20%7C%20Cursor%20%7C%20通用Agent-blue)

## What is Storyweave?

Storyweave is an AI-powered story outline generator that helps writers, game designers, and content creators build structured story frameworks through an interactive Q&A conversation.

Instead of staring at a blank page, Storyweave guides you through a series of thoughtful questions to extract the core elements of your story—theme, characters, conflict, world—then maps everything onto proven narrative structures.

## Features

### 🎯 Guided Q&A Framework
- Progressive information gathering (1-2 questions at a time)
- No overwhelm—build the outline gradually
- Captures灵感碎片 (inspirational sparks) from any conversation

### 📚 10 Classic Story Templates
| Template | Best For |
|----------|----------|
| Three-Act Structure | General-purpose storytelling |
| Hero's Journey | Adventure, fantasy, coming-of-age |
| Save the Cat! (15 beats) | Film scripts, commercial fiction |
| Scene Structure (Sheaf) | Scene-level detailing |
| Minimal 5-Point | Short stories, proof-of-concept |
| Seven-Point | Serial stories with hooks |
| Non-linear | Time loops, flashbacks |
| Three-Act Five-Stage | Traditional drama, Chinese opera |
| Escalating Stakes | Thriller, mystery |
| Kishotenketsu | Artistic, experimental (East Asian) |

### 👤 5 Character Arc Types
- Positive Arc (growth)
- Negative Arc (fall)
- Flat Arc (belief changes world)
- Fall and Rise
- Circular Arc

## Platform Compatibility

Storyweave is a universal skill that works with any AI agent framework that supports skills:

- **OpenClaw / WorkBuddy** — Install to `~/.workbuddy/skills/`
- **Claude Code** — Install to `~/.claude/skills/`
- **Cursor** — Install to `.cursor/skills/` or `~/.cursor/skills/`
- **Other frameworks** — Any agent that reads `SKILL.md` from a designated skills directory

## Installation

### For OpenClaw / WorkBuddy Users
```bash
cp -r storyweave ~/.workbuddy/skills/
```
1. Download `storyweave.zip` from this repository
2. Place it in your skills directory:
   ```bash
   cp storyweave.zip ~/.workbuddy/skills/
   ```
3. Restart your agent to activate.

### For Claude Code Users
```bash
cp -r storyweave ~/.claude/skills/
```

### For Cursor Users
```bash
cp -r storyweave ~/.cursor/skills/
```

### For Developers
```bash
git clone https://github.com/ShiyangZheng/storyweave.git
```

## Usage

### In Conversation
Simply tell WorkBuddy what you want to write:

> "I want to write a sci-fi novel about a linguist who discovers aliens communicate through music."

> "Help me outline a murder mystery set in a small coastal town."

> "I'm developing a game narrative about a child searching for their lost memories."

### The Process

1. **Q&A Phase**: Storyweave asks targeted questions about your story's genre, theme, characters, and conflict.

2. **Template Selection**: Based on your story type, Storyweave recommends the most suitable narrative structure.

3. **Outline Generation**: A complete, detailed outline is generated with all story beats mapped.

4. **Iteration**: Deep-dive into specific scenes, characters, or arcs as needed.

### Example Output Structure

```markdown
# Story Title

## Basic Info
- Genre: Sci-Fi Thriller
- Theme: Communication & Connection
- Target Audience: Adult fiction readers

## World

## Characters
- Protagonist: [Name, identity, desire, fear]
- Antagonist: [Name, role, relationship]
- Mentor: [Name, function]
- Allies: [Names and roles]

## Story Structure: Hero's Journey

## Detailed Outline

### Act 1: Departure
- **Ordinary World**: ...
- **Call to Adventure**: ...
- ...

## Inspiration Fragments
[Your scattered ideas, mapped to potential positions]

## Next Steps
[Suggestions for further development]
```

## Templates Deep Dive

### Three-Act Structure
```
Act 1 (25%)     → Setup, Catalyst, First Turn
Act 2 (50%)     → Fun & Games, Midpoint, Crisis
Act 3 (25%)     → Climax, Resolution
```

### Hero's Journey (12 Stages)
```
Ordinary World → Call → Refusal → Mentor → Threshold
→ Tests → Cave → Ordeal → Reward → Return → Resurrection → Elixir
```

### Save the Cat! (15 Beats)
```
Opening Image → Theme → Setup → Catalyst → Debate
→ Break Into Two → B-Story → Fun & Games → Midpoint
→ Bad Guys Close In → All Is Lost → Dark Night → Break Into Three
→ Finale → Final Image
```

## Philosophy

- **Flexibility over rigidity**: Templates are tools, not cages. Adjust beats as your story demands.
- **Completion over perfection**: A rough but complete outline beats a perfect concept.
- **Capture everything**: Those midnight灵感碎片? They're gold. Storyweave saves them all.
- **Progressive depth**: Start with the skeleton, flesh out details later.

## File Structure

```
storyweave/
├── README.md                    # This file
├── SKILL.md                     # Skill definition (works with any agent framework)
└── references/
    └── story_templates.md        # All 10 narrative templates + 5 character arcs
```

## Contributing

Contributions welcome! Feel free to:
- Add new story templates
- Improve existing templates
- Translate documentation
- Report issues or suggestions

## License

MIT License - Free to use, modify, and distribute.

## Acknowledgments

Built with inspiration from:
- Joseph Campbell's *The Hero with a Thousand Faces*
- Christopher Vogler's *The Writer's Journey*
- Blake Snyder's *Save the Cat!*
- Dan O'Neill's Scene Structure

---

*Storyweave—where stories begin.*
