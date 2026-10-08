# ai-daily-planner

### FOUNDER — AI Daily Planner
A self-hosted automation that turns a plain-English to-do list into a
time-blocked day and emails it to you at 6 AM — then rebuilds the schedule as
you reply `done` / `skip` / `add:`.

- **LLM task parsing** — Groq turns natural language into structured, schedulable tasks
- **Full email loop** — Gmail SMTP for sending, IMAP for reading replies
- **Deterministic scheduling** — locked events never move; deep work lands in your focus window
- **Learns from history** — adjusts durations to your real pace, cushions tasks you struggle with
- **Runs itself** — a macOS launchd agent runs it hourly; optional wake/sleep via `pmset`
- **Zero dependencies** — pure Python standard library
- Weekly digest, self-hosted HTML dashboard, and a live "now / next" SSE web view
