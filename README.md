# Astra

Astra is an open-source astrophotography sequencer and imaging controller focused on intelligent automation, reliable imaging, and a modern user experience.

The goal is to automate the technical routine of astrophotography without taking control away from the user.

## What we're building

Astra is being designed as a complete imaging environment for automated and unattended astrophotography.

The project is built around a few core principles:

- Automate what can be measured
- Keep manual control available
- Make automation transparent and predictable
- Build for reliable unattended imaging
- Treat devices, rigs, and imaging workflows as first-class concepts
- Keep integrations open and extensible
- Provide a fast and modern user experience

## Planned capabilities

Astra is being developed toward support for:

- Flexible imaging sequences
- Camera and multi-rig control
- Autofocus and automatic focus calibration
- Plate solving and framing
- Guiding and dithering
- Meridian flips
- Polar alignment
- Calibration frames
- Frame quality analysis
- Session recovery
- Adaptive scheduling
- Lucky imaging
- REST, WebSocket, MQTT and webhook integrations
- Plugin and external backend support

## Automation without losing control

Astra follows an **auto-first, never auto-only** approach.

Where possible, Astra should be able to measure and determine parameters such as focus step size, filter offsets, focuser backlash, settling behavior and other calibration values automatically.

Automatic results should remain visible to the user, including their uncertainty or confidence where appropriate.

Manual configuration and fallback behavior will remain available.

## Architecture

Astra is being built primarily with **C# and .NET**.

The core runtime is designed to operate independently from the desktop interface, allowing imaging sessions to continue even when the UI is disconnected or restarted.

The architecture is centered around:

- A headless-capable runtime
- Device and rig registries
- Event-driven state management
- Resource-aware scheduling
- A flexible sequencing engine
- Shared imaging and analysis pipelines
- Open integration interfaces

The desktop application is planned around **Avalonia** for a modern cross-platform interface.

## Project status

Astra is currently in early development.

The architecture, core runtime and simulator infrastructure are being established before hardware support and higher-level imaging functionality are added.

Expect breaking changes while the foundations are being built.

## Repositories

The organization will contain the Astra application and, as the project grows, related components such as plugins, documentation and supporting tools.

## Contributing

Astra is being developed in the open.

Contribution guidelines and development documentation will be added as the project reaches a stage where external contributions can be integrated reliably.

For now, feel free to follow the project, explore the repositories and join the discussion.

---

**Astra — modern astrophotography sequencing built around intelligent automation.**
