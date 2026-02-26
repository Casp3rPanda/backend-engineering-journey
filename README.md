# backend-engineering-journey

Day 1 I cleaned my machine. Day 2 I learned how to read it.
This repo is my proof of work. 540 days. No shortcuts.

## Who I am
ghostnode | Casp3rPanda
Building toward Cloud Security Backend Engineering from scratch.
Ubuntu 24 | Python | Go | Linux

## The stack
- Python 3.12.3
- Go 1.24.0
- Linux CLI → Backend Systems → Cloud Security

## The timeline
Started: February 21, 2026
Target: August 13, 2027
Current: Phase 1 - Linux CLI Mastery (Days 1-90)

## The vibe
"The Man Who Moves A Mountain Begins By Carrying away Small Stones" --Confucius


DAY 3 COMPLETE
Date: February 25, 2026 | Day 3 of 540
What I thought would be a 10 minute drill turned into a 2 hour deep dive. That's how this works — you pull one thread and the whole system opens up. No shortcuts today.
SYSTEM CLEANED:

Stopped, disabled, and fully removed cups + cups-browsed — print services with no business running on a dev machine
Stopped, disabled, and fully removed modemmanager + orphaned dependencies libmbim-utils + libqmi-utils
Units reduced from 426 → 422
Total space freed: ~35MB

KEY LESSONS:

apt remove alone isn't enough — cups.socket respawned the service after removal. Always kill at the systemd level first
stop ≠ disable — one kills it now, one removes it from boot. You need both
Package names are lowercase in apt. Service names are not. Know the difference
Read confirmation prompts before hitting Y. Every time.

MISTAKE OF THE DAY:
Typing accuracy cost me multiple failed commands. Slow down before hitting enter.
QUOTE:
"Fast is slow. Slow is fast." — Brad Pitt, F1
COMMIT: docs: Day 3 - systemctl mastery, attack surface reduced

