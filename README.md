# AzerothCore Creator

A TrinityCreator-style desktop tool built specifically for AzerothCore.

---

## About This Project

AzerothCore is one of the most stable, well-maintained 3.3.5 cores available. Over time, it became clear that while the core itself is powerful, there was no dedicated desktop application designed specifically around its database structure for streamlined content creation.

TrinityCreator proved that a structured visual workflow for database editing works extremely well. AzerothCore Creator was built with that same philosophy — but tailored exclusively to AzerothCore.

This is not a multi-core abstraction tool.
This is not a profile-based editor.

Everything is hardcoded specifically to AzerothCore’s tables and schema.

The goal is simple:

- Reduce manual SQL editing
- Lower the barrier to entry for content creators
- Provide a structured workflow for database editing
- Contribute long-term tooling to the AzerothCore ecosystem

---

## Current Status

Beta Release

The project is actively under development. Core systems are implemented, and feature parity with TrinityCreator is in progress.

Estimated completion level: ~80% of TrinityCreator’s core functionality.

---

## Features (Beta)

### Creature Editor
- Structured creature_template support
- Role preset dropdown
- Faction and flag handling
- Beginner-friendly layout
- Direct AzerothCore column mapping

### Item Editor
- Trinity-style item layout
- Toggle-based flag, class, race, and resistance controls
- Field grouping for clarity
- Structured database alignment

### Database Alignment
- Hardcoded AzerothCore table support
- No profile switching
- Direct mapping to AzerothCore schema
- SQL preview generation

### Interface
- Windows desktop application (WPF)
- Clean, organized layout
- Designed for usability without sacrificing structure

---

## Philosophy

AzerothCore Creator is designed as a contribution to the AzerothCore community.

It is not meant to replace developer workflows.
It is meant to empower:

- Server owners
- Small teams
- Content creators
- New contributors intimidated by raw SQL

The intention is long-term development with continued feature expansion.

---

## Installation

1. Go to the Releases section of this repository.
2. Download the latest `.zip` build.
3. Extract the archive.
4. Run the executable.

Make sure your AzerothCore database credentials are configured correctly before use.

---

## Important Notes

This repository contains compiled builds only.

The source repository is maintained privately during active development.

Feedback, suggestions, and feature ideas are welcome.

---

## Roadmap

- Full feature parity with TrinityCreator
- Expanded quest support
- Additional database tooling
- Workflow enhancements tailored to AzerothCore
- Continued UI refinement

---

## Acknowledgment

TrinityCreator demonstrated the value of structured database tooling. AzerothCore Creator builds on that concept and adapts it specifically for AzerothCore’s ecosystem.

Thank you to the AzerothCore team for maintaining a core worthy of dedicated tooling.

---

— Kris