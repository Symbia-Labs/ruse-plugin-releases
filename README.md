# Ruse example plugins

Free Audio Unit and CLAP effect plugins that Symbia Labs built with [Ruse](https://github.com/Symbia-Labs/ruse), the open source framework for building audio plugins with an AI agent.

This repository holds the downloads and release notes. The "Source code" archives GitHub attaches to each release contain only this README.

**[Download the plugins](https://github.com/Symbia-Labs/ruse-plugin-releases/releases)**. The newest release is at the top. Every release carries all six plugins.

## Plugins

| Plugin | What it does |
| --- | --- |
| Env Auto Wah | A resonant band-pass filter that sweeps with the input level, driven by an envelope follower with separate attack and release. |
| Env Saturator | A waveshaper whose drive rises or falls with the input level, driven by an envelope follower with separate attack and release. |
| Fractal Delay | Every echo spawns a smaller copy of the whole delay pattern, four levels deep. |
| Bus Compressor | A feed-forward compressor with a soft knee, a parallel mix and a gain reduction meter. |
| Harmonic EQ | Parametric bands placed on the harmonics of one fundamental. |
| Warm Saturator | A soft or hard clipper followed by a one-pole low-pass. |

Controls and ranges for each plugin are on the [examples page](https://www.symbia-labs.com/ruse/plugins/examples/).

## Requirements

- A Mac with Apple silicon, running macOS 11 or later.
- A host that loads Audio Unit v2 or CLAP plugins, such as Logic.

## Installing

The plugins are signed with our Developer ID and notarized by Apple, so they open without a Gatekeeper warning.

1. Unzip a download. Each zip holds an Audio Unit (`.component`) and a CLAP (`.clap`).
2. Copy the `.component` to `~/Library/Audio/Plug-Ins/Components` and the `.clap` to `~/Library/Audio/Plug-Ins/CLAP`.
3. Rescan plugins in your host.

Each release lists SHA-256 checksums in `SHA256SUMS.txt`.

## Questions and requests

Open an issue here or write to hello@symbia-labs.com. To ask for a plugin, use the same address with the subject "Plugin request".
