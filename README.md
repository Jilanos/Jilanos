# Paul Mondou

Head of Electronics in e-mobility. I run the electrical side of an electric vehicle: wiring harness, CAN network, battery and power-electronics suppliers, homologation.

Ph.D. in imaging and medical physics, signal processing focus (CEA, Université Paris-Saclay): focused ultrasound, real-time FPGA control, in vitro and in vivo experiments.

I turn field problems into working tools, fast. I use AI-assisted development held to real standards: tests, CI, tagged releases, and apps that actually run in production on [paulmondou.fr](https://paulmondou.fr).

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## Live apps

| App | What it does |
|---|---|
| [CanTraceDiag](https://cantracediag.paulmondou.fr) | CAN trace workstation in the browser: ASC/TRC/BLF/MF4, DBC decoding, synchronized plots. The trace stays local. |
| [Kapsule](https://kapsule.paulmondou.fr) | Knowledge-card decks with quizzes and SM-2 spaced repetition. |
| [ClaimLens](https://claimlens.paulmondou.fr) | Turns a YouTube video into a sourced analysis brief, claims checked against PubMed. |
| [F1 Datas](https://f1.paulmondou.fr) | Static race analytics for the 2026 season: positions, tyre strategy, gaps. |
| [Gnosis](https://gnosis.paulmondou.fr) | Builds Kapsule decks from a list of technical topics. |
| [Canto](https://canto.paulmondou.fr) | Practice singing in tune: visual piano and real-time pitch curve. |
| [Pays du jour](https://pays.paulmondou.fr) | Daily country fiche in French, with server-rendered charts and maps. |
| [SommeilEnOr](https://sommeil.paulmondou.fr) | Mobile journal of the daily context around each night of sleep. |

All of them are self-hosted on one VPS behind Caddy.

## Featured projects

### CAN & embedded tooling

- [CanTraceDiag](https://github.com/Jilanos/CanTraceDiag): local CAN trace workstation, DBC decoding, synchronized plots and A/B cursors.
- [PeakLive](https://github.com/Jilanos/peaklive): Windows CAN workstation on PEAK PCAN: live acquisition, DBC decoding, plots, recording and export.
- [electrical-plan-editor](https://github.com/AlexAgo83/electrical-plan-editor): contributor to an open-source editor for electrical plans and wiring networks.
- [tapis_roulant](https://github.com/Jilanos/tapis_roulant): read-only BLE monitor for FTMS treadmills: Python CLI, Web Bluetooth page and Android app.

### Learning & content apps

- [Kapsule](https://github.com/Jilanos/Kapsule): PWA of knowledge-card decks with quizzes and spaced repetition, JSON import, multi-device.
- [Gnosis](https://github.com/Jilanos/Gnosis): generates Kapsule card and quiz decks from a list of technical topics.
- [ClaimLens](https://github.com/Jilanos/ClaimLens): sourced analysis brief from a YouTube video, with claim checks on PubMed.
- [Canto](https://github.com/Jilanos/Canto): local-first PWA to practice singing in tune.
- [pays-du-jour](https://github.com/Jilanos/pays-du-jour): daily country reader in French, charts and maps rendered on the server.
- [StopScroll](https://github.com/Jilanos/StopScroll): Android app that limits time spent in apps, no account and no internet access.

### Data & analysis

- [cashflow-lab](https://github.com/Jilanos/cashflow-lab): import bank CSV exports, review monthly spending, forecast 3 to 12 months of cash flow.
- [world_cup_predictor](https://github.com/Jilanos/world_cup_predictor): World Cup match outcomes (1X2) with a calibrated ML model.
- [scrappy](https://github.com/Jilanos/scrappy): job-offer triage with explainable scoring, XLSX review and skill-gap analysis.
- [Pinguino](https://github.com/Jilanos/Pinguino): local research workbench for FX strategies, read-only MT5 import, auditable exports.
- [SommeilEnOr](https://github.com/Jilanos/SommeilEnOr): mobile sleep-context journal with full JSON/CSV export.
- [Ogame_conseiller](https://github.com/Jilanos/Ogame_conseiller) and [gwendalavir-map](https://github.com/Jilanos/gwendalavir-map): a game-economy optimizer and a reproducible map-colorization pipeline.

### AI dev tooling

- [orchestia](https://github.com/Jilanos/orchestia): human-supervised workflow for AI-assisted development, with Git and Logics keeping the evidence.
- [Orchestrato](https://github.com/Jilanos/Orchestrato): local CLI supervisor for coding agents: deterministic routing, approvals, SQLite state.
- [codex-task-planner](https://github.com/Jilanos/codex-task-planner), [codex-task-harness](https://github.com/Jilanos/codex-task-harness), [codex-task-supervisor](https://github.com/Jilanos/codex-task-supervisor): plan, run and benchmark atomic coding tasks for Codex.

## How I build

- Local-first by default: private data stays on the device or on my own server.
- Tests, CI and tagged releases before anything goes live.
- Automation under human supervision, with an audit trail.

## Contact

[paulmondou.fr](https://paulmondou.fr) · [LinkedIn](https://www.linkedin.com/in/paul-mondou-865a98260/) · Ph.D. publications on [paulmondou.fr](https://paulmondou.fr/#science)
