# GI-CardSort-preT1

Asynchronous card-sorting interface for preT1 baseline elicitation in participatory GI retrofitting research.

## Features

- Session-locked participant IDs
- Forced-distribution Q-grid (-2 to +2) with real-time slot enforcement
- Auto-filtered Top-k depth evaluation (≥1 pro, ≥1 con)
- Timestamped JSON export for audit trails

## Workflow

1. Enter researcher-assigned ID
2. Preview all 10 GI evidence cards
3. Drag cards into Q-grid
4. Write rationales for Top-k cards
5. Submit → JSON auto-download

## Data Schema

`placement` (grid coordinates), `feedback` (Top-k pros/cons), `actionLog` (timestamped events), participant metadata.

## Research Context

Asynchronous counterpart to the Boardmix-based synchronous Q-H Canvas. Developed for doctoral research on greening interventions for China's existing residential buildings in the HSWW zone.
