# Teresa Torres' Claude Code Plugins

A curated collection of Claude Code plugins for research automation, writing assistance, and productivity.

## Available Plugins

### Research System
Automated research paper discovery, PDF monitoring, and AI-powered summarization for academic and technical literature.

**Features:**
- Daily arXiv and Google Scholar paper discovery
- Automated PDF monitoring and task creation
- AI-powered research paper summarization
- Intelligent filtering to remove irrelevant papers
- Obsidian-compatible markdown output

[View Plugin →](https://github.com/ttorres33/research-system)

### Task Management
Markdown-based task management with daily and weekly views, archiving, and idea
tracking.

**Features:**
- Daily `today.md` plus rolling `this-week.md` / `next-week.md` views
- Automatic archiving of completed tasks, with recurring tasks left in place
- Idea tracking by status, and an import folder for triage
- Multiple task systems on one machine, selected by working directory
- Task systems shared with another person through a synced Obsidian vault
- Runs on stock system Python — no packages to install

[View Plugin →](https://github.com/ttorres33/task-management)

### Project Docs
Maintains project documentation: `README.md` (what it is and how to use it),
`ARCHITECTURE.md` (design and patterns), `process-notes/` (per-entry work history),
and A/B test documentation.

**Features:**
- Consistent, structured process notes as a project evolves
- README and architecture docs kept in step with the code
- A plan reviewer and a code reviewer for use before implementing and before committing

[View Plugin →](https://github.com/ttorres33/project-docs)

## Installation

### Add the Marketplace

```bash
/plugin marketplace add ttorres33/teresa-torres-plugins
```

### Install a Plugin

```bash
/plugin install research-system
/plugin install task-management
/plugin install project-docs
```

## License

MIT
