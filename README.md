# Chiki加固 Protection Framework

![Chiki加固 Banner](https://raw.githubusercontent.com/ridhoae303/Chiki-Internal-Security/main/banner/chiki-banner.jpg)

Internal Android protection framework focused on runtime integrity, anti-tampering, and hostile environment detection.

Chiki加固 is a private protection system built for internal Android applications and proprietary environments.  
This framework is **not public software** and **not open source**.

The name **"Chiki"** comes from a combination of **Kagami Chihiro** and **Konuri Maki**, two characters from Veritas in Blue Archive a programming and hacking club that became one of the inspirations behind this project.

## What is Chiki加固?

Chiki加固 is a native Android protection layer designed to make runtime modification, reverse engineering, instrumentation, and tampering significantly harder in real-world environments.

This project was mainly built for:
- Internal company applications
- Proprietary Android systems

The idea behind Chiki加固 is simple:
> Detect suspicious environments early and react immediately.

## Features

Some protections included in Chiki加固:

- Runtime integrity checks
- Anti-debugging detection
- Anti-Frida detection
- Anti-hook framework detection
- Emulator and suspicious environment checks
- Package and signature verification
- Native layer protection
- Runtime scanning and monitoring
- Suspicious library detection
- Root-related environment checks
- Basic anti-repackaging protection

Some internal protections are intentionally not documented.

## Additional Notes

> [!NOTE]
> Chiki加固 does not include a DexVM or direct code encryption system.
> For dex hiding and additional application hardening, this framework uses Dex Protect (DPT) alongside the native protection layer.

## Open Source?

No.

Chiki加固 is a private internal framework and is not intended to be released as open source software.

This repository exists mainly as a project showcase and technical presence.

## Notes for Modders & Reverse Engineers

If you discover a bypass, weakness, or unexpected behavior inside the protection layer, please report it through the Issues section.

Responsible reports are appreciated.

## Status

Active internal project.  
Used only in proprietary environments.
