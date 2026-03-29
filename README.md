# Nebula Graph

> A desktop data workstation for scientific data preparation, repeatable group processing, visualization, and Origin-ready export.

[![Latest Release](https://img.shields.io/github/v/release/TshyGO/NebulaGraph-Releases?display_name=tag&sort=semver)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows-0A66C2)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Channel](https://img.shields.io/badge/channel-Alpha-C97A1A)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)

Nebula Graph is built for researchers and data-heavy technical workflows where one chart is never the whole job.

It is designed for the real path from raw files to usable outputs:

`import -> group -> clean -> batch process -> branch -> plot -> export`

Instead of treating each sample as an isolated object, Nebula Graph is built around **group-first workflows** so repeated operations can be shared, tracked, and reused.

## Why It Exists

Many tools are good at one step:

- quick plotting
- spreadsheet editing
- script-based processing
- export to another platform

But lab and analysis work is usually a chain, not a single action.

You often need to:

- import multiple CSV / TXT / Excel files
- switch across sheets and related samples
- clean tables before plotting
- apply the same processing chain to a whole group
- split a subgroup from a shared pipeline
- compare multiple plots without overwriting the previous figure
- export the result to Origin or downstream reporting tools

Nebula Graph is built for that full loop.

## What Nebula Graph Can Do

### Data Preparation First

- import multiple files and Excel workbooks
- auto-group datasets by file
- browse `File -> Sheet -> Group -> Sample`
- edit tables directly with row delete, column delete, and cell edits
- replay table edits across group or sheet scope

### Group-Based Processing

- use **groups** as the default working unit
- apply shared processing pipelines to similar samples
- branch from a chosen step into a subgroup
- detach a special sample when it needs a different path

### Plot Workspace

- create multiple plot tabs instead of replacing one global chart
- preserve X / Y mappings per plot context
- move from data prep to plotting without losing workflow state

### Export and Interop

- export single samples to Origin
- distribute signed Windows installers
- receive in-app update notifications when a new build is available

## Typical Workflow

1. Import a batch of similar files.
2. Let Nebula Graph auto-group them by file.
3. Clean the current table in Data Prep.
4. Apply a shared pipeline to the current group.
5. Branch a subgroup when one subset needs a different treatment.
6. Send the current group or selection to a new plot tab.
7. Export the result or keep iterating.

## Download

Get the latest Windows build from the [latest release](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest).

### Recommended

- `Nebula Graph_x.y.z_x64-setup.exe`

### Alternative

- `Nebula Graph_x.y.z_x64_en-US.msi`

## Asset Guide

| Asset | Purpose |
| --- | --- |
| `setup.exe` | Recommended installer for most users |
| `msi` | Windows Installer package |
| `*.sig` | Updater signatures used by the packaged desktop app |
| `latest.json` | Update feed metadata used by in-app updates |

## Best Fit

Nebula Graph works especially well for workflows built around families of similar structured datasets, such as:

- spectroscopy and signal-processing datasets
- workbook-based experiment outputs
- repeated measurement batches
- table-driven preprocessing before visualization

## Current Direction

The product is currently centered on:

- data preparation before plotting
- group-first workflows
- shared pipelines with controlled branching
- desktop-first scientific workbench UX
- reusable project templates and presets

## Project Status

Nebula Graph is in an active **Windows alpha** stage.

That means the core workflow is already usable, but packaging, updater polish, and the product surface are still evolving quickly.

## Notes

This repository is the **public release channel** for Nebula Graph desktop builds.

GitHub will still show `Source code (zip)` and `Source code (tar.gz)` on release pages by default. Those archives are auto-generated snapshots of this public distribution repo, not the private application source repository.
