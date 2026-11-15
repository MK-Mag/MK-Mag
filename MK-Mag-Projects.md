# MK-Mag Projects

A record of the software I've completed, the projects I'm working on, the ideas I want to keep, and the experiments I've tried. Nothing is removed from this list unless I explicitly decide to remove it.

## Currently Building

### Process Detective
**Idea:** A lightweight Windows-first desktop system monitor for inspecting running processes, CPU and memory usage, and parent-child relationships. I want a clear, responsive way to understand what's happening on my own machine, with Linux support as a future step.  
**Tools:** Go, giu (Dear ImGui), gopsutil.

## Completed

### Project Jumper
**Idea:** A personal CLI launcher for saving project directories under memorable names and opening them in a configured editor. It saves me from repeatedly navigating through folders to get to the projects I work on.  
**Tools:** Go, Cobra, embedded Turso/libSQL.  
**Repository:** https://github.com/MK-Mag/Project-Jumper

### Organizer
**Idea:** A desktop file organizer that watches selected folders and sorts files automatically using configurable rules, reducing repetitive manual cleanup.  
**Tools:** Go, Gio, fsnotify.  
**Repository:** https://github.com/MK-Mag/Orginzer

### GitHub Finder
**Idea:** A desktop application for looking up GitHub users and exploring their repositories and programming-language information in one place.  
**Tools:** Go, Wails, Vue, GitHub API.  
**Repository:** https://github.com/MK-Mag/GitHub-Finder

### Wordle CLI
**Idea:** A terminal word-guessing game and a small project for practicing Go fundamentals, input handling, and game logic.  
**Tools:** Go, standard library, terminal UI.  
**Repository:** https://github.com/MK-Mag/Wordle_Cli_game

## Paused

### Steam Judge
**Idea:** A group game-voting application where friends vote on which game to play and the winner can be launched through Steam. This project is paused for now, but I intend to continue it later. It is not canceled.  
**Tools:** Python, Flet, planned Steam integration.

## Project Ideas

These ideas are all part of my project list. They are not ranked and do not imply a fixed order. Some are large personal tools, some are developer utilities, and some may evolve as I learn more.

### Personal Cloud
**Idea:** A personal cloud for managing, storing, and accessing my own files and data across devices. The goal is to have control over my data and a dependable way to reach it from my devices.  
**Tools:** Go, HTTP APIs, file storage, authentication, synchronization, database (to be decided).

### AI Video Editor
**Idea:** An AI-assisted video editing application focused on useful editing workflows: understanding footage, helping organize clips, and assisting with editing decisions and repetitive tasks.  
**Tools:** Python, FFmpeg, media processing, AI APIs (final stack to be decided).

### Developer Portfolio
**Idea:** A personal home for presenting my software projects, technical interests, experiments, and progress as a developer. It should feel like a real representation of my work rather than a generic template.  
**Tools:** To be decided; GitHub integration may be useful.

### Forge CLI
**Idea:** A Go project generator and manager. The original concept includes commands such as `forge create`, `forge list`, and `forge version`, with a consistent project structure and optional interactive setup.  
**Tools:** Go, Cobra, optional Bubble Tea TUI.

### RAG AI Assistant
**Idea:** An assistant that can work with private files and selected sources. It retrieves relevant passages before answering and should provide references to where the information came from. This is a broader assistant concept; focused tools such as FileSense and YouTube Companion explore more specific use cases.  
**Tools:** Go, Turso, document/source ingestion, embeddings, vector search, retrieval-augmented generation, AI API.

### YouTube Companion
**Idea:** A research and learning companion for videos. It turns available transcripts into searchable material, helps find concepts across videos, compares explanations, creates learning checks, and answers questions with references to original passages and timestamps.  
**Tools:** Go, Turso, YouTube Data API, Gemini API, embeddings, vector search, lightweight RAG.

### FileSense
**Idea:** A local document-intelligence tool that indexes personal files and makes them searchable by meaning. It can answer questions across documents and point back to the exact passages it used, becoming more useful as the collection grows.  
**Tools:** Go, Turso, PDF/DOCX/TXT parsers, embeddings, vector search, full-text search, lightweight RAG.

### Bug Diary — Automated Debugging & Incident Intelligence
**Idea:** An automated investigator for software failures, rather than a journal where I manually write down bugs. It monitors selected applications or processes, captures available errors, crashes, logs, and environment details, groups recurring incidents, and uses AI to suggest likely causes based on earlier evidence and fixes.  
**Tools:** Go, background workers, OS/process monitoring, structured log ingestion, Turso, Gemini API.

### Release Radar
**Idea:** A release tracker for the software and dependencies I actually use. It follows releases and changelogs, highlights changes that matter to my projects, and points out possible breaking changes before I upgrade.  
**Tools:** Go, GitHub Releases API, official changelog feeds, scheduled workers, Turso, Gemini API.

### Device Sync Hub
**Idea:** A personal backend for sharing and synchronizing selected data, events, and device status across my Windows and Linux machines and, eventually, Raspberry Pi devices. This becomes more useful once I have more than one device.  
**Tools:** Go, HTTP APIs, Turso/libSQL, synchronization workers, device identity, conflict resolution.

### StateTrail
**Idea:** A state-change investigator for a project or service. It keeps a timeline of configuration changes, versions, and important events, then helps trace what changed before a problem appeared. The goal is to reconstruct how a system reached its current state, not just collect logs.  
**Tools:** Go, Turso, append-only event history, HTTP API, background workers, timeline and state-diff engine.

### Where Space Went
**Idea:** A disk-usage investigator that compares scans, spots unusually large or fast-growing folders, and shows where storage is disappearing over time instead of giving only a one-time size report.  
**Tools:** Go, filesystem APIs, SQLite/Turso, CLI or lightweight desktop UI.

### Command Ghost
**Idea:** A command-history search tool that helps recover commands using partial phrases and context, even when I can't remember the exact syntax.  
**Tools:** Go, shell-history parsers, fuzzy search, Turso/SQLite, CLI.

### Webhook Replay Engine
**Idea:** A tool for capturing incoming webhook deliveries, inspecting headers and payloads, keeping a delivery history, and replaying selected events against a development endpoint.  
**Tools:** Go, HTTP server, PostgreSQL or Turso (depending on workload), background workers, request inspection.

### DB Benchmark Lab
**Idea:** A repeatable workbench for comparing database behavior under the same workloads, recording results, and understanding trade-offs in queries, concurrency, and storage.  
**Tools:** Go, database drivers, SQL, Turso, SQLite, PostgreSQL, benchmark/reporting utilities.

### Name Goblin
**Idea:** A naming workbench for generating candidates, checking them against constraints, saving shortlists, and comparing names for projects or tools instead of returning endless random words.  
**Tools:** Go, text-processing libraries, optional naming APIs, Turso for saved candidates and history.

### MockDock
**Idea:** A local mock HTTP server with reusable endpoints, configurable response bodies and status codes, artificial latency, and request inspection. It would make it easier to test software that depends on external services.  
**Tools:** Go, net/http, Turso or local SQLite for saved configurations and request history, CLI.

### Repo Archaeologist
**Idea:** A way to explore how a repository evolved by connecting commits, file changes, dependencies, and structural shifts into a navigable history of the codebase.  
**Tools:** Go, Git plumbing/CLI, repository parsers, Turso for indexed history, optional embeddings.

### Command Vault
**Idea:** A searchable library of useful commands and workflows, including when to use them, required context, safe examples, and what to expect when they run.  
**Tools:** Go, CLI, shell integration, Turso, full-text search.

### Clipboard Memory
**Idea:** A private clipboard history that lets me search and recover copied text across sessions, with exclusions, automatic expiry, and controls for sensitive information.  
**Tools:** Go, Windows clipboard APIs, background service, Turso or encrypted local storage.

### Memory Palace
**Idea:** A personal knowledge-retrieval system that connects saved concepts and references by meaning and relationships. The exact use case still needs to become more distinctive before it is worth building.  
**Tools:** Go, Turso, full-text search, embeddings, vector search.

### Commit Pet
**Idea:** A small desktop companion that reacts to meaningful repository activity and makes long-term project maintenance feel more rewarding than watching a commit counter.  
**Tools:** Go, Git hooks or repository polling, desktop UI, Turso for activity history.

### Dead Drop
**Idea:** A private, time-delayed way to leave a note or small file for another device or for myself in the future, with expiry and retrieval rules.  
**Tools:** Go, HTTP API, Turso, background expiry workers, optional client-side encryption.

## Experiments

### Multiplayer Whiteboard
**Idea:** An early collaborative drawing prototype built around shared rooms and real-time updates. Development is stopped for now, but it remains documented as an experiment.  
**Tools:** Go, WebSocket/realtime communication, frontend prototype.  
**Repository:** https://github.com/MK-Mag/Multiplayer-WhiteBored
