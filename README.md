# SIM-Authentication-OS

> Research Project (Concept Stage)

## Overview

SIM-Authentication-OS is a research project proposing an operating-system-level anti-theft security framework for smartphones.

Instead of relying only on lock screens or cloud services, the operating system registers one user-selected SIM card as the **Trusted SIM**.

Once enabled, the operating system continuously verifies the presence of the Trusted SIM.

## Project Concept

### Trusted SIM Registration
- User manually enables the feature.
- One SIM becomes the Trusted SIM for the device.

### Continuous Authentication
- The operating system continuously checks that the Trusted SIM is present.

### SIM Removal Protection
If the Trusted SIM is removed:
- Device enters Anti-Theft Mode.
- A loud emergency alarm starts.
- The alarm ignores silent mode and user volume settings.
- The alarm continues until the original Trusted SIM is inserted again.

### Factory Reset Protection (Research Goal)
The long-term goal is to investigate whether OS-level integration can prevent unauthorized factory reset attempts when the Trusted SIM is absent.

> This feature is currently a research objective and must be validated against Android bootloader and recovery architecture.

## Objectives

- Reduce smartphone theft.
- Increase difficulty of reusing stolen devices.
- Research OS-level SIM authentication.
- Explore integration with Android Open Source Project (AOSP).

## Current Status

Phase 1 — Research and Architecture

## Repository Structure

- docs/          Documentation
- research/      Technical notes
- design/        Diagrams and workflows
- prototype/     Early prototypes
- src/           Future implementation
- assets/        Images and logos

## Contributors

- Giri A  (@hackerG3121)
- Dhatchanamoorthy V (@dhatchanamoorthy444)

## License

MIT License
