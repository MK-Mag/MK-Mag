# MK-Mag Projects

The canonical inventory of my software projects. Every project showcased in the profile README must be listed here.

> **Project standard:** Every project must solve a real problem, give me a compelling reason to reopen and use it months after completion, be distinctive rather than generic, teach meaningful engineering, and have room to grow through real use. I prefer lasting products over disposable portfolio demos.

## Currently

### Process Detective
**Core idea:** A lightweight Windows-first desktop system monitor that helps me inspect running processes, CPU and memory usage, and parent-child relationships. The goal is to understand what is happening on my own machine through a focused, responsive tool. Linux support is planned.  
**Tools:** Go, giu (Dear ImGui), gopsutil.

## Complete

### Project Jumper
**Core idea:** A personal CLI launcher for saving project directories under memorable names and opening them in a configured editor, so I can jump between projects without repeatedly navigating folders.  
**Tools:** Go, Cobra, embedded Turso/libSQL.  
**Repository:** https://github.com/MK-Mag/Project-Jumper

### Organizer
**Core idea:** A desktop file organizer that watches selected folders and automatically sorts files using configurable rules, reducing repetitive manual cleanup.  
**Tools:** Go, Gio, fsnotify.  
**Repository:** https://github.com/MK-Mag/Orginzer

### GitHub Finder
**Core idea:** A desktop application for looking up GitHub users and exploring their repositories and programming-language information without manually browsing multiple profile pages.  
**Tools:** Go, Wails, Vue, GitHub API.  
**Repository:** https://github.com/MK-Mag/GitHub-Finder

### Wordle CLI
**Core idea:** A terminal word-guessing game built as a compact way to practice Go fundamentals, input handling, and game logic.  
**Tools:** Go, standard library, terminal UI.  
**Repository:** https://github.com/MK-Mag/Wordle_Cli_game

## Next

These four are the main planned projects after Process Detective. They are accepted candidates, not parallel active work.

### YouTube Companion
**Core idea:** Turn videos and available transcripts into a searchable research library. Find concepts across videos, compare explanations, generate summaries and learning checks, and ask questions with answers grounded in source passages and timestamps.  
**Tools:** Go, Turso, YouTube Data API, Gemini API, embeddings, vector search, lightweight RAG.

### FileSense
**Core idea:** A local document-intelligence system that indexes personal files, supports semantic search, answers questions across documents, and points back to the exact source passages. Its value should increase as the document collection grows.  
**Tools:** Go, Turso, PDF/DOCX/TXT parsers, embeddings, vector search, full-text search, lightweight RAG.

### Bug Diary — Automated Debugging & Incident Intelligence
**Core idea:** An automated incident investigator, not a manual bug journal. It monitors user-selected applications or processes, captures available crashes/errors/logs and environment context, groups duplicate incidents, correlates recurring failures, and uses AI to suggest likely causes linked to previous evidence and fixes. Capture must be scoped and privacy-conscious; platform-specific crash collection should be implemented realistically rather than assumed to work universally.  
**Tools:** Go, background workers, OS/process monitoring, structured log ingestion, Turso, Gemini API.

### Release Radar
**Core idea:** Follow the software and dependencies I actually use. Track releases and changelogs, identify changes relevant to my projects, summarize them, and flag possible breaking changes with links to the original release notes.  
**Tools:** Go, GitHub Releases API, official changelog feeds, scheduled workers, Turso, Gemini API.

## Maybe

These are retained ideas, not commitments. The four marked in the profile README are simply a rotating showcase from this list.

### Where Space Went
**Core idea:** A disk-usage investigator that explains where storage is going, highlights unusually large or fast-growing directories, and helps compare scans over time instead of only showing a one-time folder-size list.  
**Tools:** Go, filesystem APIs, SQLite/Turso, CLI or lightweight desktop UI.

### Command Ghost
**Core idea:** Search and recover commands from shell history using fuzzy matching and context, so I can find a command even when I remember only part of what it did.  
**Tools:** Go, shell-history parsers, SQLite/Turso, fuzzy search, CLI.

### Webhook Replay Engine
**Core idea:** Capture incoming webhook deliveries, inspect headers and payloads, preserve delivery history, and replay selected events against a development endpoint to debug integrations.  
**Tools:** Go, HTTP server, PostgreSQL or Turso (choose after workload testing), background workers, request inspection.

### DB Benchmark Lab
**Core idea:** A repeatable benchmark workbench for running comparable database workloads, recording results, and explaining trade-offs across query patterns, concurrency, and storage configurations.  
**Tools:** Go, database drivers, SQL, Turso, SQLite, PostgreSQL, benchmark/reporting utilities.

### Name Goblin
**Core idea:** A playful naming workbench that generates candidate names, checks them against chosen constraints, stores shortlists, and helps compare names for projects or tools rather than returning an endless random word list.  
**Tools:** Go, text-processing libraries, optional naming APIs, Turso for saved candidates and history.

### MockDock
**Core idea:** A configurable local mock HTTP server with named endpoints, response bodies and status codes, artificial latency, request inspection, and reusable scenarios for testing software that depends on external services.  
**Tools:** Go, net/http, Turso or local SQLite for saved configurations and request history, CLI.

### Repo Archaeologist
**Core idea:** Explore how a repository evolved by connecting commits, file changes, dependencies, and structural shifts into a navigable explanation of why the codebase looks the way it does.  
**Tools:** Go, Git plumbing/CLI, repository parsers, Turso for indexed history, optional embeddings.

### Command Vault
**Core idea:** A searchable command and workflow library that stores not just snippets but when to use them, required context, safe examples, and the result of running them.  
**Tools:** Go, CLI, shell integration, Turso, full-text search.

### Clipboard Memory
**Core idea:** Search and recover previously copied text across sessions with explicit exclusions, expiration, and sensitive-data controls.  
**Tools:** Go, Windows clipboard APIs, background service, Turso/local encrypted storage.

### Memory Palace
**Core idea:** A personal knowledge-retrieval system that connects saved concepts and references by meaning and relationships, with a clear focus to be defined before implementation.  
**Tools:** Go, Turso, full-text search, embeddings/vector search.

### Commit Pet
**Core idea:** A small desktop companion that reacts to meaningful repository activity and turns long-term maintenance into a playful feedback loop, without reducing it to a generic commit counter.  
**Tools:** Go, Git hooks or repository polling, desktop UI, Turso for activity history.

### Dead Drop
**Core idea:** A private, time-delayed handoff for notes or small files between my own devices or future self, with expiry and retrieval rules. The exact product scope still needs validation.  
**Tools:** Go, HTTP API, Turso, background expiry workers, optional client-side encryption.

### Device Sync Hub
**Core idea:** A personal backend for exchanging and synchronizing selected data, events, and device status across Windows, Linux, and future Raspberry Pi devices. It becomes useful once more than one device is available.  
**Tools:** Go, HTTP APIs, Turso/libSQL, synchronization workers, device identity and conflict-resolution logic.

## Paused

### Steam Judge
**Core idea:** A group game-voting concept where friends vote on which game to play and the winner can be launched through Steam. It is paused and is not part of the current build plan.  
**Tools:** Python, Flet, Steam integration (planned).

### Multiplayer Whiteboard
**Core idea:** An early collaborative drawing prototype exploring shared rooms and real-time updates between users. Work has stopped; this is kept here for project-history completeness, not as a planned restart.  
**Tools:** Go, WebSocket/realtime communication, frontend prototype.  
**Repository:** https://github.com/MK-Mag/Multiplayer-WhiteBored

---

## Roadmap discipline

- **Process Detective** is the only currently active project.
- Finish the current project before starting another; the Next list is not a parallel-work list.
- New ideas must pass the five project tests: utility, long-term use, originality, engineering depth, and growth.
- Prefer real integrations and automation where they make the product more useful.
- AI must perform a concrete job (retrieval, classification, diagnosis, extraction, or decision support), not exist just to add an AI label.
- This file is the source of truth. Any project showcased in the profile README must also be listed here.
