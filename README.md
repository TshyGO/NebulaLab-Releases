# Nebula Graph

> A desktop data workstation for scientific data preparation, batch processing, visualization, and Origin-ready export.

[![Latest Release](https://img.shields.io/github/v/release/TshyGO/NebulaGraph-Releases?display_name=tag&sort=semver)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Windows](https://img.shields.io/badge/platform-Windows-0A66C2)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Status](https://img.shields.io/badge/status-Alpha-C97A1A)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)

Nebula Graph is built for people who work with batches of similar scientific datasets and need something stronger than a quick plotting script, but lighter and more workflow-focused than a heavyweight analysis suite.

It helps you go from **raw files** to **grouped datasets**, **repeatable processing pipelines**, **plot tabs**, and **export-ready outputs** inside one desktop app.

## Why Nebula Graph

Many data tools are good at one isolated step: importing, plotting, or exporting. Real lab work is not isolated.

You usually need to:

- import multiple CSV / TXT / Excel files
- switch across sheets and related samples
- clean tables before plotting
- apply the same processing chain to a group
- branch part of the workflow for a subgroup or one special sample
- compare multiple plots without overwriting the previous figure
- send the result to Origin or downstream reporting tools

Nebula Graph is designed around that full workflow.

## What It Can Do

### Data Preparation First

- import multiple files and Excel workbooks
- auto-group related datasets by file
- browse `File -> Sheet -> Group -> Sample`
- edit tables directly with row delete, column delete, and cell edits
- batch-replay table edits to a group or sheet scope

### Group-Based Processing

- treat **groups** as the main working unit, not just single samples
- apply shared processing pipelines across similar data
- branch from a chosen step into a subgroup
- detach a single sample when it needs a special path

### Plot Workspace

- create multiple plot tabs instead of constantly overwriting one chart
- preserve X / Y mappings per plot context
- move from data prep to plotting without losing workflow state

### Export and Interop

- export single samples to Origin
- generate signed desktop installers and updater metadata
- receive in-app update notifications for newer builds

## Typical Workflow

1. Import a batch of similar files.
2. Let Nebula Graph auto-group them by file.
3. Clean tables in Data Prep.
4. Apply a shared pipeline to the current group.
5. Branch a subgroup when one subset needs special treatment.
6. Send the current group or selection to a new plot tab.
7. Export the result to Origin or keep iterating.

## Download

Get the latest Windows build from the [latest release](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest).

### Recommended

- `Nebula Graph_x.y.z_x64-setup.exe`

### Alternative

- `Nebula Graph_x.y.z_x64_en-US.msi`

## Asset Guide

- `setup.exe`: recommended installer for most users
- `msi`: Windows Installer package
- `*.sig`: updater signatures used by the packaged desktop app
- `latest.json`: update feed metadata used by in-app updates

## Current Product Direction

Nebula Graph is being built around these ideas:

- **data prep before plotting**
- **group-first workflows**
- **shared pipelines with controlled branching**
- **desktop-first scientific workbench UX**
- **repeatable, reusable project templates**

## Best For

Nebula Graph is especially suited to workflows where you repeatedly process families of similar structured datasets, such as lab-generated spectra, tabular measurements, and workbook-based experiment outputs.

## Notes

This repository is the **public release channel** for Nebula Graph desktop builds.

GitHub will still show `Source code (zip)` and `Source code (tar.gz)` on release pages by default. Those archives are auto-generated snapshots of this public distribution repo, not the private application source repository.