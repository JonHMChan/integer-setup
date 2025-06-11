# AI Second Brain

A personal Markdown-based journal project designed for daily writing, reflection, and continuous documentation with AI assistance. This project serves as a "second brain" that captures thoughts, insights, and experiences while building long-term memory through structured journaling.

## Overview

This project combines the simplicity of Markdown with the power of AI-assisted journaling. Daily entries are stored as dated files with a consistent structure, allowing for easy reflection and pattern recognition over time.

## Project Structure

```
ai-second-brain/
├── journal/           # Daily journal entries (YYYY-MM-DD.md)
├── CLAUDE.md         # AI assistant instructions and personal context
└── README.md         # This file
```

## Journal Entry Format

Each journal entry follows a structured format:

```markdown
# YYYY-MM-DD

## Summary
[Brief overview of the day]

## Key Events
[Important things that happened]

## Thoughts & Reflections
[Personal insights, feelings, or observations]

## Notes
[Any additional notes or reminders]
```

## Key Features

- **Daily Structure**: Consistent YYYY-MM-DD.md naming convention
- **AI Integration**: Built-in support for Claude Code assistance
- **Continuous Updates**: Real-time journal updating during conversations
- **Long-term Memory**: Personal context preserved across sessions
- **Git Integration**: Automatic commits at natural conversation breaks
- **Minimal Dependencies**: Simple Markdown files, no complex setup

## Usage

### Creating Journal Entries

Create a new journal entry for today:

```bash
touch journal/$(date '+%Y-%m-%d').md
```

List all journal entries:

```bash
ls journal/
```

### AI-Assisted Journaling

The project includes `CLAUDE.md` which provides instructions for AI assistance:

- **Session Initialization**: Automatically checks for today's entry
- **Continuous Workflow**: Updates entries during conversations
- **Personal Context**: Maintains long-term memory between sessions
- **Natural Conversation**: Focused, one-question-at-a-time approach

## Workflow

1. **Daily Check**: AI assistant checks for today's journal entry
2. **Conversation**: Natural dialogue about the day's events and thoughts
3. **Real-time Updates**: Journal entry updated throughout the conversation
4. **Reflection**: Structured capture of insights and experiences
5. **Commit**: Changes committed at natural stopping points

## Benefits

- **Consistency**: Daily writing habit with structured format
- **Reflection**: Organized capture of thoughts and insights
- **Memory**: Long-term context preservation across sessions
- **Simplicity**: Plain Markdown files, easy to read and backup
- **Flexibility**: Adaptable structure for different types of content

## Getting Started

1. Clone or download this repository
2. Start a conversation with Claude Code in this directory
3. The AI will automatically initialize today's journal entry
4. Begin writing and reflecting with AI assistance

This project transforms daily journaling from a solitary activity into an interactive, AI-enhanced experience that builds your personal knowledge base over time.