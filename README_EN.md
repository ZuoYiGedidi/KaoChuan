# AI Time Management Assistant

An AI-powered time management tool for solo developers.

## Overview

Solo developers often juggle roles across development, design, marketing, and customer support without external structure or predictable scheduling. This leads to inaccurate task estimation and blurred work-life boundaries. The AI Time Management Assistant leverages AI-driven role detection and intelligent scheduling to help solo developers manage their time more effectively.

## Core Features

- **Automatic Role Detection**: Identifies your current role (development, design, marketing, customer support, etc.) in real time by monitoring active applications, window titles, Git commits, and calendar events, then generates a time allocation dashboard.
- **Intelligent Task Scheduling**: Dynamically schedules tasks via the Claude API based on priority, historical productivity data, calendar events, and deadlines, offering instant recommendations and time-block planning.
- **Context Switching Assistance**: One-click role switching with automatic application state snapshots (open files, browser tab groups), supporting gradual context transitions.
- **Mobile Companion**: A React Native + Expo mobile app with smart push notifications, voice/text quick-entry for tasks, and a daily time allocation dashboard.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Desktop Framework | Tauri 2.0 (Rust + React) |
| Frontend | React 19 + TypeScript + Tailwind CSS |
| Visualization | Recharts |
| State Management | Zustand |
| Backend | Rust (sysinfo, sqlx + SQLite) |
| Mobile | React Native + Expo |
| AI Engine | Claude 3.5 Sonnet API |
| Browser Extension | Chrome Extension Manifest V3 |

## Quick Start

The project is currently in the design phase. Active development has not yet begun.

Development roadmap:

- **Phase 1 (Months 1–2)**: Tauri scaffold, process/window monitoring, SQLite data logging, rule-based role detection, basic dashboard UI
- **Phase 2 (Months 3–5)**: Cloud AI integration, intelligent scheduling engine, context switching assistance, browser extension, mobile app, calendar integration
- **Phase 3 (Months 6–8)**: Advanced analytics & insights, IDE plugins (VS Code / JetBrains), public API, team collaboration, privacy enhancements, performance optimizations

For detailed system design, see the [Design Document](./2026-05-25-ai-time-management-tool-design.md).

## Contributing

Pull Requests are welcome!

- Please open an Issue to discuss the feature or bug fix before submitting a PR
- Follow the project's code style and commit conventions
- Ensure all tests pass

## License

This project is open-sourced under the [MIT License](./LICENSE).
