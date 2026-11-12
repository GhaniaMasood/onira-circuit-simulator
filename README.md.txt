# Onira

**Genetic circuit simulator. Dream. Build. Simulate.**

Live app: https://onira-psi.vercel.app/
(First load can take up to a minute while the server wakes up.)

## What it does
Onira lets you design a genetic circuit and simulate how it behaves over time, either from a library of literature-based circuit topologies or by building your own from individual parts.

- 18 circuit topologies (toggle switch, repressilator, feed-forward loops, autoregulation, quorum sensing and more), each modelled with Hill-function ODEs and linked to primary literature
- Design Mode: build circuits from a parts library on a strand canvas, with the ODE model derived from the circuit's structure by a custom rule engine
- SBOL import and export
- Design Advisor and sequence integrity checks
- Wet lab notes for taking a design to the bench
- Built-in feedback widget for early testers

## Tech stack
React + Vite (frontend), FastAPI + SciPy (simulation backend), SQLite and Supabase Postgres (data), deployed on Vercel and Render.

## Status
Soft-launched in November 2026 and currently gathering feedback from early testers.

## Source code
The source code is private. Access is available to reviewers and collaborators on request: onirabio@gmail.com

## Author
Ghania Masood

## License
Copyright (c) 2026 Ghania Masood. All rights reserved.