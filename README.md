# Fakhriyya Vazirova

BSc Artificial Intelligence student at King's College London. I build full-stack software around operational problems: systems where the data model, the concurrency rules and the numbers have to be right, not only the interface.

## Projects

| Project | Problem solved | Main technologies | Status | Repository / demo |
|---|---|---|---|---|
| **SUFRA — Restaurant Platform** | Runs a restaurant's reservations, floor, orders, kitchen, stock, HR and accounts on one database, and lets guests pick and book a real table in a live 3D model of the venue | Python, FastAPI, SQLModel, SQLite, WebSockets, three.js | Working prototype | [sufra-restaurant-platform](https://github.com/madmaxfv0/sufra-restaurant-platform) · [guest demo](https://sufra-360.fly.dev) |
| **CORE — Causal Operations & Recovery Engine** | Estimates what oil-well interventions actually changed, using counterfactual baselines instead of before/after, then builds a job programme under budget and crew limits | Python, FastAPI, pandas, SciPy, PuLP, DuckDB, React, TypeScript | Proof of concept | [core-causal-operations-engine](https://github.com/madmaxfv0/core-causal-operations-engine) · [demo](https://core-demo.fly.dev) |
| **Antarctic Ecosystem Simulation** | Agent-based predator–prey model where life-cycle traits are inherited, crossed over and mutated | Java, JavaFX | Coursework, complete | [antarctic-ecosystem-simulation](https://github.com/madmaxfv0/antarctic-ecosystem-simulation) |
| **DEPTHS — Ocean Defence** | Arcade shooter drawn entirely in code, built on two small class hierarchies | Java, JavaFX | Coursework (pair project), complete | [depths-ocean-defence](https://github.com/madmaxfv0/depths-ocean-defence) |
| **Tidy-Up Robot** | A TurtleBot3 that finds misplaced objects with YOLOv4 and carries them to the right room, as a SMACH state machine | Python, ROS 1, actionlib, SMACH, YOLOv4 | Coursework, complete | [tidy-up-robot](https://github.com/madmaxfv0/tidy-up-robot) |

## What to look at first

- **SUFRA** for system design: two applications sharing one source of truth, a booking path that stays correct under simultaneous requests, role-based access control, and a real-time 3D front end.
- **CORE** for analytical engineering: causal inference with validation against a planted truth, a mixed-integer optimiser, and data provenance carried through to every number on screen.

## Technical areas

Python · Java · TypeScript · FastAPI · React · SQL (SQLite, DuckDB) · three.js / WebGL · ROS · optimisation and statistics with NumPy, SciPy and PuLP
