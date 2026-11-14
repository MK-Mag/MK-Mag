# MK-Mag Projects

A complete working inventory of my software projects, experiments, and future ideas.

> **Project rule:** A project must solve a real problem, have a reason to be reopened and used months after completion, feel distinctive rather than generic, teach meaningful engineering, and have room to grow through real use. I prefer fewer lasting products over disposable portfolio demos.

## Current

### Process Detective
**Status:** In progress  
**Stack:** Go, giu, gopsutil  
A lightweight Windows-first desktop system monitor for exploring processes, CPU and memory usage, and parent-child relationships. Linux support is planned.

## Completed

### Project Jumper
**Status:** Completed  
**Stack:** Go, Cobra, embedded Turso  
A CLI launcher for saving named project directories and opening them in a configured editor.  
Repository: https://github.com/MK-Mag/Project-Jumper

### Organizer
**Status:** Completed  
**Stack:** Go, Gio, fsnotify  
A desktop file organizer that watches selected folders and sorts files using configurable rules.  
Repository: https://github.com/MK-Mag/Orginzer

### GitHub Finder
**Status:** Completed  
**Stack:** Go, Wails, Vue  
A desktop app for looking up GitHub users and exploring their repositories and language information.  
Repository: https://github.com/MK-Mag/GitHub-Finder

### Wordle CLI
**Status:** Completed small learning project  
**Stack:** Go, terminal  
A terminal word-guessing game built to practice Go fundamentals.  
Repository: https://github.com/MK-Mag/Wordle_Cli_game

## Later — selected future projects

These are accepted ideas, not active projects. They should not interrupt the current focus on Process Detective.

### YouTube Companion
**Status:** Later  
**Stack direction:** Go, Turso, YouTube Data API, Gemini API, embeddings, lightweight RAG  
Turn videos and available transcripts into a searchable research library. Support summaries, topic extraction, source-grounded questions, comparisons across videos, and learning checks. Transcript availability and API terms will shape the implementation.

### FileSense
**Status:** Later  
**Stack direction:** Go, Turso, document parsers, embeddings, lightweight RAG  
A local document-intelligence tool that indexes personal files, supports semantic search, and answers questions with references to the source documents. The focus is useful retrieval across a growing file collection, not a generic chatbot.

### Bug Diary — Automated Debugging & Incident Intelligence
**Status:** Later — approved automated direction  
**Stack direction:** Go, background services, OS/process monitoring, structured logs, Turso, Gemini API  
An automated incident investigator rather than a manual bug journal. It should monitor selected applications or processes, capture crashes/errors/logs and relevant environment/project context, normalize and deduplicate incidents, correlate recurring failures, and use AI to explain likely causes and connect new incidents to previous evidence and fixes. The user should not need to manually write an issue every time something fails. Privacy, user-controlled capture scope, and local-first storage are important.

### Release Radar
**Status:** Later  
**Stack direction:** Go, GitHub Releases API, scheduled workers, Turso, Gemini API  
Monitor releases and changelogs for selected software and dependencies. Highlight changes relevant to the user's installed tools or project dependencies, summarize them, and flag possible breaking changes with links to original release notes.

### Device Sync Hub
**Status:** Later — deferred until multiple devices are available  
**Stack direction:** Go, HTTP APIs, Turso/libSQL or another suitable storage layer  
A personal device backend for exchanging and synchronizing selected data, events, and status across Windows, Linux, and future Raspberry Pi devices. It is intentionally deferred while only one device is available.

## Maybe — retained ideas

These are possibilities, not commitments. Each must be reconsidered against the project rule before being promoted.

### Where Space Went
**Direction:** Go, filesystem, CLI  
A disk-usage analyzer that makes it easy to discover where storage space is being used and which folders are responsible.

### Command Ghost
**Direction:** Go, CLI, shell history  
A fast command-history search and recovery tool for finding commands when the exact syntax has been forgotten.

### DB Benchmark Lab
**Direction:** Go, databases, benchmarking  
A repeatable environment for comparing database behavior under clearly defined workloads and understanding performance trade-offs.

### Name Goblin
**Direction:** Go, naming and text tooling  
A playful utility for generating, organizing, and evaluating names for projects or other things where naming is genuinely useful. Scope and lasting use still need validation.

### MockDock
**Direction:** Go, HTTP, developer tooling  
A configurable local mock HTTP server with endpoints, response bodies/status codes, artificial latency, and request inspection. Deferred; it must prove useful in actual testing workflows rather than becoming another generic mock server.

### Repo Archaeologist
**Direction:** Go, Git, repository analysis  
Explore how a repository evolved by connecting its structure, commits, and changes into an understandable history.

### Command Vault
**Direction:** Go, CLI  
A searchable personal collection of useful terminal commands and snippets. Needs a distinctive workflow beyond basic bookmarking.

### Clipboard Memory
**Direction:** Desktop/system utility  
Search previously copied text and recover useful clipboard history. Privacy and sensitive-data controls would be essential.

### Memory Palace
**Direction:** Knowledge retrieval  
A personal knowledge organization and retrieval concept. Not committed; must offer a clearer unique use case than a generic notes app.

### Commit Pet
**Direction:** Git integration, playful desktop utility  
A small companion that reacts to repository activity. Needs a meaningful long-term loop beyond a novelty animation.

### Dead Drop
**Direction:** To be defined  
A retained idea whose concrete problem and product behavior still need to be worked out.

## Paused, discontinued, or retired

### Steam Judge
**Status:** Paused / not currently pursuing  
A group game-voting concept where friends vote on games and launch the winner. Not part of the active roadmap.

### Multiplayer Whiteboard
**Status:** Discontinued  
An early collaborative drawing prototype exploring real-time communication, rooms, and authentication. Not continuing.  
Repository: https://github.com/MK-Mag/Multiplayer-WhiteBored

### Forge CLI
**Status:** Retired / not currently pursuing  
A Go project generator that was considered with templates and preset stacks. It was later rejected as the next project in favor of building products with a more compelling ongoing use case.

### Generic RAG AI Assistant
**Status:** Superseded by more focused AI projects  
An earlier concept for a general assistant that answers questions over personal files using retrieval and source-linked responses. The idea has since been split into more concrete products, especially YouTube Companion and FileSense, rather than kept as a separate generic assistant.

## Explicitly dropped concepts

These were considered during brainstorming but rejected or canceled. They are not part of the roadmap:

- Personal Knowledge Vault
- Home Inventory & Tracker
- Webhook Inbox / Replay Server
- Personal Activity & Event Logger
- DailyPilot
- MailPilot
- Deal Radar
- Game Night
- Smart Download Manager

---

## Roadmap discipline

- Only **Process Detective** is the current active project.
- Later projects are not permission to start parallel work; finish the active project first.
- New ideas must pass the five project tests above.
- Prefer real integrations and automation where they make the product more useful.
- AI must perform a concrete job (retrieval, classification, diagnosis, extraction, or decision support), not exist just to add an AI label.
- Revisit the roadmap as actual needs change; do not treat every idea as a promise to build it.
