# ELab — Electrical Laboratory

[简体中文](README.zh-CN.md)

**Learn once. Use across platforms.**

Electrical design, dynamic simulation, and virtual experiments in ELab.

Draw electrical control schematics, run experiments, and observe how circuits respond. ELab is designed for electrical and automation engineers, students, teachers, and vocational training programs.

**Windows** · In preparation | **Linux** · In preparation | **macOS** · In preparation

[Download ELab](#download-elab) · [Product demo](#product-demo) · [Explore capabilities](#core-capabilities) · [Release history](#release-history) · [Send feedback](#feedback-and-licensing)

## Download ELab

| Platform | Architecture | Public availability |
| --- | --- | --- |
| Windows | x64 | In preparation |
| Windows | ARM64 | In preparation |
| Linux | x64 | In preparation |
| Linux | ARM64 | In preparation |
| macOS | Intel x64 | In preparation |
| macOS | Apple Silicon ARM64 | In preparation |

Public desktop packages are in preparation. Each published build will list its tested operating systems, package type, version, size, and SHA-256 checksum.

[Offline documentation v1.1.0](https://github.com/Auspicore/ELab/releases/tag/docs-v1.1.0) · [Download guide](docs/download.md) · [Installation and verification](docs/installation.md)

## Core capabilities

### Draw and organize schematics

- Search and preview components such as circuit breakers, pushbuttons, contactors, and motors before placing them on a sheet.
- Draw terminal-to-terminal wiring, edit device properties and wire numbers, and use undo to revisit design changes.
- Split power, control, and indication circuits across sheets. Use cross-references to locate a device's coil and contacts on different sheets.

### Run and observe a control circuit

- Operate switches, pushbuttons, and protective devices in a live simulation. Follow changes in contacts, motors, and indicators directly on the schematic.
- Pause or step through a sequence in the Case Console. Review the event timeline to see the order in which devices changed state.
- Use the motor start/stop case to observe self-holding, then repeat the experiment with an overload trip to compare the results.

### Check, lay out, and share a design

- Run design validation to find wiring and device-reference problems. Use the reported object or drawing to inspect the issue.
- Lay out devices on a mounting plate with rails and wire ducts. Use layout checks to review overlaps and out-of-bounds placements.
- Generate searchable device, terminal, and connection lists. Export engineering reports as CSV and schematics as SVG for review or documentation.

## Product demo

**What keeps a motor running after you release Start?** Follow the circuit as the contactor energizes, its auxiliary contact holds the circuit, and Stop releases it. Repeat the experiment with a thermal overload trip and compare the event sequence. The written walkthrough includes expected results for each operation. [Motor start/stop experiment](docs/quick-start.md#try-the-motor-startstop-experiment)

## Where to use ELab

- **Electrical design review.** Divide a design into power and control sheets, trace related contacts, and bring the device and terminal lists to your review.
- **Classroom demonstration.** Ask students to predict whether the motor will keep running after Start is released, then check their prediction on the live schematic.
- **Independent troubleshooting practice.** Repeat the same run with Stop and with a thermal overload trip. Use the event timeline to compare how each operation stops the motor.

## Get started in 30 seconds

Once you have a build for your platform, create an editable copy of the motor control case in the **Case Library**. Open **Live Simulation**, close the circuit breaker, and press and release Start. Observe the motor and contactor, then press Stop. [Step-by-step guide](docs/quick-start.md)

## Release history

- **Documentation v1.1.0** covers design and simulation workflows, a worked motor-control exercise, and the platform guide. [Release notes and offline guide](https://github.com/Auspicore/ELab/releases/tag/docs-v1.1.0)
- **Documentation v1.0.0** archives the first bilingual product and quick-start guides. [Release notes and offline guide](https://github.com/Auspicore/ELab/releases/tag/docs-v1.0.0)

[All GitHub Releases](https://github.com/Auspicore/ELab/releases) · [Changelog](CHANGELOG.md)

## Feedback and licensing

Use GitHub Issues to report a problem or suggest a feature. Commercial, partnership, and educational licensing contacts are pending. [Open the issue chooser](https://github.com/Auspicore/ELab/issues/new/choose) · [Feedback guide](docs/feedback.md) · [Private vulnerability reports](SECURITY.md) · [FAQ](docs/faq.md)

## Copyright and software license

ELab is proprietary software. Use of the application is governed by the license terms supplied with the applicable release.
