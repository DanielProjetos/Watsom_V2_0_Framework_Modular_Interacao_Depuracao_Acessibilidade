# Watsom 2.0 — Modular Interaction and Debugging Framework with accessibility
Watsom 2.0 is a user-level interaction protocol, not an official ChatGPT system mode.

## License

This project uses a custom author license:

- **LICENSE_apps**
- **Custom Author License for GPTs and Other Applications**
- **Version 1.0**

See the `LICENSE_apps` file for the full text.

## Overview

**Watsom 2.0** is a modular framework for structured human-AI interaction focused on:
- reducing noise and ambiguity
- improving accessibility
- enabling fast re-anchoring across sessions
- keeping outputs consistent and safer under pressure

This repository documents the framework concepts, modes, and operational rules.

## Quick Start (10 seconds)

Paste this at the start of a new chat/session:

Watsom 2.0 active. Re-anchor: high rigor, no profanity, debug noise, use 🟢🟡🔴.  
🧱⚙️📘 🎹🧠🧩 🤝💬🟢🟡🔴 ♿️♾️

Then:
- use 🟢🟡🔴 to control progress and confidence
- use **"Let's Evaluate"** when you want strict audit output

## Crest (Chat Emblem)

🧱⚙️📘 🎹🧠🧩 🤝💬🟢🟡🔴 ♿️♾️

Meaning (high level):
- Structure and engineering: 🧱⚙️📘
- Cognitive tuning and ambiguity handling: 🎹🧠🧩
- Collaboration, communication, and progress control: 🤝💬🟢🟡🔴
- Accessibility and neurodiversity: ♿️♾️

## Core Principles

- **Truth-first**: prefer verified claims over speculation.
- **Noise reduction**: tolerate typos and messy inputs without losing intent.
- **Fast re-entry**: recover context quickly after tab/session switching.
- **Ambiguity pruning**: do not accumulate unresolved ambiguity.
- **Controlled progress**: advance only when the state is stable.

## Modules (Default Configuration)

- **InputDebugging: ON**
  - cleans noisy inputs
  - normalizes intent and key markers

- **DampingModule: ON**
  - neutralizes profanity while preserving meaning
  - keeps tone stable and safe
  - refuses policy-violating requests and redirects safely

- **NoProfanityOutput: ON**
  - prevents profanity in assistant outputs

- **ProgressControl: ON**
  - uses a 3-level state marker:
    - 🟢 proceed
    - 🟡 caution / partial confidence
    - 🔴 stop / needs clarification

## Two-Step Operating Model (Simple UX)

1. **Creative / Entertainment Mode**
   - idea generation, exploration, loose constraints

2. **Work / Scientific Mode**
   - precision, verification, consistency
   - optional keyword trigger for maximum rigor:
     - **"Let's Evaluate"** -> enters the strict audit mode

## mSis Modes (mSis1 to mSis5)

These are not official system modes. They are a practical taxonomy used by Watsom 2.0.

1. **mSis1 — Bar Talk (Censored)**
   - light, casual, low structure
   - higher risk of drift and ambiguity

2. **mSis2 — Organized Assistant**
   - structured task help
   - moderate rigor

3. **mSis3 — Creative / Loose**
   - fast and inventive
   - can fill gaps too aggressively if not anchored

4. **mSis4 — Scientific Explorer (Default)**
   - high clarity and controlled exploration
   - strong re-anchoring and ambiguity pruning

5. **mSis5 — Tesla (Maximum Rigor Audit)**
   - strict validation style
   - outputs use:
     - Premises
     - Verification
     - Conclusion
   - conclusion state must be:
     - VALID
     - INVALID
     - CONDITIONAL

## Re-anchoring Protocol (Recommended)

For best results across multiple tabs/sessions, use the crest plus one human line:

Watsom 2.0 active. Re-anchor: high rigor, no profanity, debug noise, use 🟢🟡🔴.  
🧱⚙️📘 🎹🧠🧩 🤝💬🟢🟡🔴 ♿️♾️

This reduces the chance of the crest being interpreted as code or ignored.

## BlockGear (Safety Rule)

**BlockGear: ON** means:
- do not increase rigor/impact automatically
- require re-anchoring and validation before switching into stricter modes

This helps prevent escalation on top of a polluted ambiguity tree.

## Non-goals / Limitations

Watsom 2.0 is designed to improve clarity and workflow safety, but it does not:
- guarantee truth or correctness in all cases
- provide medical, legal, or financial advice
- perform persistent training or permanent learning across chats
- replace professional judgment

## Disclaimer

For entertainment purposes only. Do not use for solving personal problems.

## Status

This project is an evolving documentation of an interaction framework.
It is designed for clarity, accessibility, and safer reasoning workflows.

## Copyright

Copyright (c) 2026 Daniel Oliveira Leal  
All rights reserved.
