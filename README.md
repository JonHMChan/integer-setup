# AI Second Brain

A personal Markdown-based journal project designed for daily writing, reflection, and continuous documentation with AI assistance. This project serves as a "second brain" that captures thoughts, insights, and experiences while building long-term memory through structured journaling.

## Getting Started

### Prerequisites

- **Claude Code**: Download from [claude.ai/code](https://claude.ai/code)
- **Git**: For version control (optional but recommended)

### Setup

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/ai-second-brain.git
   cd ai-second-brain
   ```

2. **Start Claude Code** in the project directory:
   ```bash
   claude-code
   ```

3. **Begin journaling**: Claude will automatically initialize today's journal entry and start a conversation to help you reflect and write.

### First Session

When you first start Claude Code in this directory:
- It will check for today's journal entry (`journal/YYYY-MM-DD.md`)
- Create the file if it doesn't exist
- Begin asking thoughtful questions to help you capture your day
- Update the journal in real-time as you share thoughts and experiences

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

This project is designed to work primarily through **Claude Code**, Anthropic's AI coding assistant. The journaling experience is interactive and AI-guided.

### Starting a Journaling Session

1. Open Claude Code in this project directory
2. The AI will automatically:
   - Check for today's journal entry
   - Create one if it doesn't exist
   - Begin a natural conversation to help you reflect and write

### AI-Assisted Features

- **Session Initialization**: Automatically checks for today's entry
- **Continuous Workflow**: Updates entries during conversations  
- **Personal Context**: Maintains long-term memory between sessions
- **Natural Conversation**: Focused, one-question-at-a-time approach
- **Automatic Commits**: Saves progress at natural conversation breaks

### Manual Commands (Optional)

If you prefer manual file management:

```bash
# Create a new journal entry for today
touch journal/$(date '+%Y-%m-%d').md

# List all journal entries
ls journal/
```

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

This project transforms daily journaling from a solitary activity into an interactive, AI-enhanced experience that builds your personal knowledge base over time.