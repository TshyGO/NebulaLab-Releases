<div align="center">

<img src="https://raw.githubusercontent.com/TshyGO/NebulaGraph-Releases/main/assets/nebula-hero.svg" alt="Nebula Graph hero banner" width="100%" />

# Nebula Graph

### A desktop data workstation for scientific data preparation, repeatable batch processing, visualization, and Origin-ready export.

[![Latest Release](https://img.shields.io/github/v/release/TshyGO/NebulaGraph-Releases?display_name=tag&sort=semver)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows-0A66C2)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Channel](https://img.shields.io/badge/channel-Alpha-C97A1A)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)

**Built for workflows that start with raw files and end with reusable plots, clean exports, and repeatable processing chains.**

</div>

---

## What Nebula Graph Is For

Nebula Graph is designed for people working with **families of similar scientific datasets** rather than isolated one-off charts.

It is especially useful when you need to:

- import multiple CSV, TXT, and Excel files together
- organize related datasets by file, sheet, group, and sample
- clean tables before plotting
- apply the same processing chain across a whole group
- branch a subgroup from a shared workflow when only part of the data changes
- compare multiple plot contexts without replacing the previous figure
- send finished results to Origin or downstream reporting tools

At its core, Nebula Graph is about making this path feel natural:

`import -> group -> clean -> batch process -> branch -> plot -> export`

---

## Core Strengths

| Area | What it means in practice |
| --- | --- |
| **Data Preparation First** | Clean tables before plotting, instead of treating preprocessing as an afterthought |
| **Group-First Workflow** | Apply shared logic to related samples without repeating the same operations one by one |
| **Controlled Branching** | Split a subgroup or one special sample from a shared pipeline when the workflow diverges |
| **Plot Context Preservation** | Create multiple plot tabs without overwriting the previous working view |
| **Desktop Delivery** | Use signed Windows installers, in-app update feeds, and a packaged local engine |

---

## What You Can Do Today

### Data Prep Workspace

- import multiple files and Excel workbooks
- auto-group related datasets by file
- browse `File -> Sheet -> Group -> Sample`
- delete rows, delete columns, and edit cell values directly
- replay table edits across group or sheet scope

### Shared Processing

- use **groups** as the default working unit
- apply shared processing steps to similar data
- branch from a chosen step into a subgroup
- detach a sample when it needs a custom path

### Plot Workspace

- create multiple plot tabs
- keep separate X / Y mappings by plot context
- move from data prep to plotting without losing the workflow state

### Export and Interop

- export single samples to Origin
- download signed Windows builds
- receive in-app reminders when a newer build is available

---

## Typical Workflow

1. Import a batch of similar files.
2. Let Nebula Graph auto-group them by file.
3. Clean the current table in Data Prep.
4. Apply a shared pipeline to the current group.
5. Branch a subgroup when one subset needs special treatment.
6. Send the current group or selection to a new plot tab.
7. Export the result or continue iterating.

---

## Download

Get the latest Windows build from the [latest release](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest).

### Recommended for most users

- Windows setup installer (`.exe`)

### Alternative installer

- Windows MSI package (`.msi`)

### Asset guide

| Asset | Purpose |
| --- | --- |
| `setup.exe` | Recommended installer for most users |
| `msi` | Windows Installer package |
| `*.sig` | Updater signatures used by the packaged desktop app |
| `latest.json` | Update feed metadata used by in-app updates |

---

## Quick Start

1. Download the latest installer from Releases.
2. Install Nebula Graph on Windows.
3. Import a batch of related data files.
4. Organize and clean them in Data Prep.
5. Apply a shared workflow to the current group.
6. Open one or more plot tabs.
7. Export the result when the workflow is ready.

---

## Best Fit

Nebula Graph is a strong fit for:

- spectroscopy and signal-processing datasets
- workbook-based experiment outputs
- repeated measurement batches
- table-driven preprocessing before visualization
- technical workflows where the same logic is reused across many similar samples

---

## Product Direction

Nebula Graph is currently centered on these ideas:

- **data preparation before plotting**
- **group-first workflows**
- **shared pipelines with controlled branching**
- **desktop-first scientific workbench UX**
- **reusable project templates and presets**

---

## FAQ

### Is Nebula Graph open source?

The public `NebulaGraph-Releases` repository is the distribution channel for desktop builds. The application source repository is private at the moment.

### Why do GitHub Releases still show `Source code (zip)` and `Source code (tar.gz)`?

Those archives are generated automatically by GitHub for every public Release. They are snapshots of this public distribution repository, not the private application source repository.

### What stage is the product in?

Nebula Graph is currently in an active **Windows alpha** stage. The core workflow is usable, while packaging, updater polish, and the product surface are still evolving quickly.

