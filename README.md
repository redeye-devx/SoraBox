# SoraBox

SoraBox is a clean, modern Android proxy client concept powered by **sing-box v1.14.0**.

## Project status

This repository is the starting point for SoraBox. The first milestone is the Android UI/UX implementation, followed by the official sing-box Android bridge and runtime integration.

## Design direction

SoraBox uses a dark navy interface with cyan and violet accents. The Home screen focuses on connection state, the active profile, Download/Upload speed, Inbound/Outbound traffic, Latency, Uptime, and a compact live traffic chart.

## Planned screens

- **Home:** Connection status, active profile, network metrics, and live traffic chart.
- **Profiles:** Import, edit, delete, and activate proxy profiles.
- **Routing:** Routing mode, DNS mode, TUN mode, and rule configuration.
- **Settings:** Theme, notifications, auto-connect, diagnostics, and core information.

## Core target

The target core line is **sing-box v1.14.0**. The UI is intended to remain separate from the core bridge so that the design can evolve without coupling presentation code to runtime internals.

## License

SoraBox is distributed under the GNU General Public License v3.0. See [LICENSE](LICENSE).

## Branding

- App name: **SoraBox**
- Android application ID: `dev.redeye.sorabox`
- Repository: `redeye-devx/SoraBox`
- Core target: `sing-box v1.14.0`
