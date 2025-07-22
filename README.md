# Claude Code Slash Commands

This folder contains custom slash commands for use with Claude Code, an AI-powered coding assistant. These commands provide specialized workflows and enhanced capabilities for common development tasks.

## What are Slash Commands?

Slash commands are pre-configured prompts that you can invoke in Claude Code by typing `/` followed by the command name. They provide Claude with specific instructions and context to handle particular types of tasks more effectively.

## Available Commands

### `/bug-find`
A systematic bug investigation workflow that helps diagnose issues through methodical questioning and analysis. Guides you through triage, reproduction, root cause analysis, and fix planning without jumping to conclusions.

### `/draft-pr-body`
Generates well-formatted pull request descriptions for the `posit-dev/positron` repository. Automatically looks up the related GitHub issue and creates a PR body with proper structure, release notes, and QA instructions.

### `/feature-execute`
Implements features based on existing implementation plans. Follows a systematic approach to execute pre-planned changes, tracking progress and ensuring adherence to the documented plan.

### `/feature-plan`
A comprehensive feature planning workflow that guides you through discovery, requirements gathering, and implementation planning. Creates detailed documentation before any code is written.

### `/pr-checklist`
An extensive pre-submission checklist for the Positron project. Runs automated checks for code cleanliness, style compliance, testing, and generates PR descriptions. Helps ensure your code meets all project standards.

### `/reflect`
Analyzes your recent chat history and current project instructions to identify improvements. Helps optimize Claude's performance by refining instructions based on actual usage patterns.

### `/review-changes`
Provides an in-depth code review before PR submission. Analyzes changes for complexity, performance, maintainability, and architectural concerns. Offers specific improvement suggestions organized by severity.

### `/spec-driven-dev`
A minimalist approach to software development that emphasizes understanding the problem deeply before writing code. Creates requirements, design, and implementation documents with a focus on simplicity.

## Usage

To use a command, simply type the slash followed by the command name in your Claude Code session:

```
/bug-find
/feature-plan
/pr-checklist
```

Some commands accept arguments. For example:
```
/draft-pr-body 12345
```

Claude will then follow the specialized workflow defined in that command file.

## Contributing

These commands are stored as markdown files in this directory. To create a new command or modify existing ones, edit the corresponding `.md` file with your enhanced instructions.