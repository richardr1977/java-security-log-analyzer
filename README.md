# Java Security Log Analyzer & Alert Manager

An object-oriented Java command-line utility built to model, filter, and triage security log alerts by severity and event type for faster root-cause investigation.

## Project Structure
- **`App.java`** — Entry point that initializes sample security alert records and runs diagnostic triage routines.
- **`SecurityAlert.java`** — Data model encapsulating core alert attributes (severity level, event type, source, and status).
- **`SecurityAlertManager.java`** — Filtering and reporting engine using modern Java collections and stream operations to isolate high-priority events.

## How to Run
Compile and run from the root directory using standard JDK tools:

```bash
javac *.java
java App
```

## Tech Stack
- Java (Standard Edition)
- Object-Oriented Design
- Java Collections & Stream API
