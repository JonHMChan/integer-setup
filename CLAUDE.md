# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal Markdown-based journal project. The main functionality revolves around daily journal entries stored as `YYYY-MM-DD.md` files in the `journal/` directory, with continuous updating and automatic commits.

## Session Initialization Workflow

**IMPORTANT**: At the start of every new session, you should automatically:

1. **Check the current date** using `date '+%Y-%m-%d'`
2. **Check if today's journal entry exists** in `journal/YYYY-MM-DD.md`
3. **Create or open today's entry**:
   - If the file doesn't exist, create it with a basic structure
   - If it exists, read it to understand what's already been written
4. **Engage in conversation** to help write/update the journal entry
   - Ask only ONE question at a time to keep conversations focused and natural
   - Wait for response before asking follow-up questions

## Continuous Journal Workflow

**CRITICAL**: After every user message/response, you should:

1. **Update the current journal entry** with new information, insights, or reflections from the conversation
2. **Be thoughtful about organization** - add content to appropriate sections (Summary, Key Events, Thoughts & Reflections, Notes)
3. **Update this CLAUDE.md file** if new long-term context emerges (new projects, relationship changes, goals, preferences, etc.)
4. **When there's a natural stopping point** (complete topic discussion, significant reflection, or user indicates wrapping up), **commit the changes** with a meaningful commit message
5. **Continue the conversation** naturally while maintaining this updating rhythm

## Long-Term Memory Updates

**IMPORTANT**: This CLAUDE.md file should be treated as a living document. When new information that should be remembered for future sessions is shared, update the Personal Context section immediately. This includes:

- New projects or career developments
- Changes in personal circumstances
- New books, influences, or philosophical shifts  
- Relationship updates or life changes
- New preferences, habits, or routines discovered
- Insights about personality, values, or working style
- Location changes or significant life events

## Personal Context Template

**Basic Information:**
- Name: [Your Name]
- Location: [Your Location]
- Background: [Brief background]

**Education & Philosophy:**
- Education: [Your education]
- Focus: [Areas of interest]
- Current Reading: [Current books]
- Influences: [Key influences]

**Career & Work:**
- Current Role: [Your role]
- Mission: [Your mission statement]

**Personal Values & Approach:**
- Core Focus: [Your core values]
- Philosophy: [Your approach to life/work]
- Values: [What you value most]

**Daily Routine & Lifestyle:**
- Typical Schedule: [Your daily routine]
- Skills: [Your key skills]
- Wellness: [Your wellness practices]

**Current Work & Tools:**
- Projects: [Current projects]
- Tools: [Tools you use]

## Folder-Specific Instructions

**IMPORTANT**: Any folder in this repository may contain its own README.md with specific instructions for that content type. Always check for and follow folder-specific guidelines before working with content in any directory.

**General Rule**: When working with any folder, first check if it contains a README.md file and read it to understand:
- Expected file formats and structures
- Naming conventions
- Specific workflows or processes
- Template files (template.md) if available

This ensures consistency and proper usage of each organizational system within the repository.

## Commands

- Create new journal entry: `touch journal/$(date '+%Y-%m-%d').md`
- List all journal entries: `ls journal/`
- Commit journal changes: Use git commit with meaningful messages about the content/themes discussed

## Development Notes

- This is a simple project with minimal dependencies
- All journal entries are plain Markdown files
- Focus on authentic conversation and reflection
- Commits should happen at natural conversation breaks