# Chiki加固 Internal Security

Chiki加固 is a private Android protection framework made for internal apps, proprietary systems, and controlled environments.

It is not an open-source project, and it is not meant to be a public security product.  
This repository is only here to introduce the project at a high level.

![Chiki Banner](https://raw.githubusercontent.com/ridhoae303/Chiki-Internal-Security/main/banner/chiki-banner.jpg)

The name **“Chiki”** comes from **Chihiro** and **Maki**, two members of Veritas from Blue Archive — a programming and security-focused club that helped inspire the theme of this project.

## What is Chiki加固?

Chiki加固 is an internal Android protection layer focused on making tampering, runtime modification, and hostile runtime behavior harder to pull off.

The goal is simple:

> Keep the app aware of its own environment and react when something does not look right.

This project was built with small-team development in mind.  
It is designed to stay practical, lightweight, and maintainable instead of trying to be a huge all-in-one commercial protector.

## Why it exists

Android apps can run in a lot of different environments, and not all of them are clean.

Chiki加固 was created to help protect internal Android applications from common modification attempts, unsafe runtime conditions, and unwanted interference.

It is mainly intended for:

- Internal company apps
- Private Android deployments
- Proprietary application environments
- Projects that need an extra protection layer before release

## What it does

Chiki加固 uses a layered approach instead of relying on one single check.

At a high level, it includes:

- App integrity validation
- Runtime environment checks
- Native-side protection
- Tamper response handling
- Suspicious behavior monitoring
- Lightweight runtime re-checking
- Protection support for apps using additional hardening tools

Some parts run early when the app starts.  
Some parts continue checking while the app is still running.

The idea is not to make the app heavy.  
The idea is to catch unsafe conditions without slowing down normal users.

## Privacy and normal user behavior

Chiki加固 is not designed to punish normal users for normal device setups.

For example, things like VPNs or proxies are not treated as malicious by themselves.  
The framework looks for stronger signs before making a decision.

The focus is on suspicious combinations, not random single signals.

## What is not documented

Some internal details are intentionally not listed here.

That includes:

- Exact detection rules
- Internal response paths
- Runtime validation details
- Native implementation details
- Private indicators and internal logic

This README is only a public introduction, not a technical manual.

## Additional Notes

> [!NOTE]
> Chiki加固 does not include a DexVM or direct code encryption system.
> For dex hiding and additional hardening, it can be used alongside Dex Protect (DPT) as part of a larger protection workflow.

> [!IMPORTANT]
> This project is private.  
> The repository only provides a general overview and does not include the internal implementation.

## Open Source?

**No.**

Chiki加固 is a private internal framework developed for proprietary environments and internal use only.

This repository is only meant to introduce the project and give a small look at its direction.

## Status

Active internal project.  
Currently used only in private and proprietary environments.

## Built by

<p align="center">
  <a href="https://github.com/ridhoae303">
    <img src="https://img.shields.io/badge/Built%20by-@ridhoae303-111111?style=for-the-badge&logo=github">
  </a>
</p>

> Internal Android protection framework powered by native runtime validation and anti-tampering systems.

<p align="center">
  <sub>Chiki加固 — Internal Use Only</sub>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:232526,100:414345&height=120&section=footer"/>
