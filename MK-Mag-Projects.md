# MK-Mag Projects

The single source of truth for my software projects: completed work, the current project, accepted next projects, and ideas that may be worth building.

> **Project standard:** Every project must solve a real problem, give me a compelling reason to reopen and use it months after completion, be distinctive rather than generic, teach meaningful engineering, and have room to grow through real use. I prefer lasting products over disposable portfolio demos.

## Currently

### Process Detective
**Stack:** Go, giu, gopsutil  
A lightweight Windows-first desktop system monitor for exploring running processes, CPU and memory usage, and parent-child relationships. Linux support is planned.

## Complete

### Project Jumper
**Stack:** Go, Cobra, embedded Turso  
A CLI launcher for saving named project directories and opening them in a configured editor.  
Repository: https://github.com/MK-Mag/Project-Jumper

### Organizer
**Stack:** Go, Gio, fsnotify  
A desktop file organizer that watches selected folders and sorts files using configurable rules.  
Repository: https://github.com/MK-Mag/Orginzer

### GitHub Finder
**Stack:** Go, Wails, Vue  
A desktop app for looking up GitHub users and exploring their repositories and language information.  
Repository: https://github.com/MK-Mag/GitHub-Finder

### Wordle CLI
**Stack:** Go, terminal  
A terminal word-guessing game built to practice Go fundamentals.  
Repository: https://github.com/MK-Mag/Wordle_Cli_game

## Next

These projects are accepted candidates for after Process Detective. They are not active yet; the order can change based on real needs and available hardware.

### YouTube Companion
**Stack direction:** Go, Turso, YouTube Data API, Gemini API, embeddings, lightweight RAG  
Turn videos and available transcripts into a searchable research library. Support summaries, topic extraction, source-grounded questions, comparisons across videos, and learning checks. Transcript availability and API terms will shape the implementation.

### FileSense
**Stack direction:** Go, Turso, document parsers, embeddings, lightweight RAG  
A local document-intelligence tool that indexes personal files, supports semantic search, and answers questions with references to source documents. The focus is useful retrieval across a growing file collection, not a generic chatbot.

### Bug Diary — Automated Debugging & Incident Intelligence
**Stack direction:** Go, background services, OS/process monitoring, structured logs, Turso, Gemini API  
An automated incident investigator rather than a manual bug journal. It should monitor selected applications or processes, capture crashes/errors/logs and relevant environment/project context, normalize and deduplicate incidents, correlate recurring failures, and use AI to explain likely causes and connect new incidents to previous evidence and fixes. The user should not need to manually write an issue every time something fails. Privacy, user-controlled capture scope, and local-first storage are important.

### Release Radar
**Stack direction:** Go, GitHub Releases API, scheduled workers, Turso, Gemini API  
Monitor releases and changelogs for selected software and dependencies. Highlight changes relevant to installed tools or project dependencies, summarize them, and flag possible breaking changes with links to original release notes.

### Device Sync Hub
**Stack direction:** Go, HTTP APIs, Turso/libSQL or another suitable storage layer  
A personal device backend for exchanging and synchronizing selected data, events, and status across Windows, Linux, and future Raspberry Pi devices. Deferred until more than one device is available.

## Maybe

Ideas worth keeping visible, but not commitments. Each must pass the project standard before being promoted to Next.

### Where Space Went
**Direction:** Go, filesystem, CLI  
A disk-usage analyzer that makes it easy to discover where storage space is being used and which folders are responsible.

### Command Ghost
**Direction:** Go, CLI, shell history  
A fast command-history search and recovery tool for finding commands when the exact syntax has been forgotten.

### Webhook Replay Engine
**Direction:** Go, HTTP, PostgreSQL or Turso evaluation  
A tool for capturing webhook requests, inspecting delivery history, and replaying events to help debug integrations. Its scope and storage choice should be driven by actual usage and write patterns.

### DB Benchmark Lab
**Direction:** Go, databases, benchmarking  
A repeatable environment for comparing database behavior under clearly defined workloads and understanding performance trade-offs.

### Name Goblin
**Direction:** Go, naming and text tooling  
A playful utility for generating, organizing, and evaluating names for projects or other things where naming is genuinely useful. Scope and lasting use still need validation.

### MockDock
**Direction:** Go, HTTP, developer tooling  
A configurable local mock HTTP server with endpoints, response bodies/status codes, artificial latency, and request inspection. It must prove useful in actual testing workflows rather than becoming another generic mock server.

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
A personal knowledge organization and retrieval concept. It needs a clearer unique use case than a generic notes app.

### Commit Pet
**Direction:** Git integration, playful desktop utility  
A small companion that reacts to repository activity. It needs a meaningful long-term loop beyond a novelty animation.

### Dead Drop
**Direction:** To be defined  
A retained concept whose concrete problem and product behavior still need to be worked out.

---

## Roadmap discipline

- **Process Detective** is the only currently active project.
- Finish the current project before starting another; the Next list is not a parallel-work list.
- New ideas must pass the five project tests: utility, long-term use, originality, engineering depth, and growth.
- Prefer real integrations and automation where they make the product more useful.
- AI must perform a concrete job (retrieval, classification, diagnosis, extraction, or decision support), not exist just to add an AI label.
- Keep this file as the source of truth. Any project showcased in the profile README must also be listed here.
