
# Mobile Game Testing Project

This repository contains beginner-friendly Game Testing projects for mobile games: Pokémon GO and Clash of Clans. Each folder contains test plans, test cases, sample bug reports, and a final project summary you can attach to applications or interviews.

/pokemon-go/
  ├─ README.md
  ├─ test_plan.md
  ├─ test_cases.md
  ├─ bug_reports.md
  └─ project_summary.md

/clash-of-clans/
  ├─ README.md
  ├─ test_plan.md
  ├─ test_cases.md
  ├─ bug_reports.md
  └─ project_summary.md


Use these files as-is or edit them with your real observations. To push to GitHub, follow the instructions below the file contents.


# File: /pokemon-go/README.md

# Pokémon GO — Manual Game Testing Project

This folder includes test plan, test cases, and sample bug reports for a manual QA project on Pokémon GO. Use this to demonstrate game testing knowledge.

# File: /pokemon-go/test_plan.md

## Test Plan — Pokémon GO

Objective: Test GPS/map accuracy, encounters, AR behavior, UI, notifications, and basic performance.

Scope: Manual testing on Android/iOS devices; no code required.

Tools: Screen recorder, Google Sheets, Postman (if needed), OBS.

Deliverables: test_cases.md, bug_reports.md, project_summary.md

# File: /pokemon-go/test_cases.md

## Test Cases — Pokémon GO

TC-PG-01 | Map Loading Accuracy | Open app, wait for map to load | Player appears at correct location

TC-PG-02 | Player Drift | Stand still for 2 minutes | Player should not drift

TC-PG-03 | Encounter Trigger | Tap Pokémon on map | Encounter screen loads

TC-PG-04 | AR Mode Anchor | Enable AR during encounter | Pokémon anchors on surface

TC-PG-05 | Pokéball Throw | Throw normal & curve | Throw animation works & catch probability accurate

TC-PG-06 | Gym Battle Load | Start gym battle | Battle UI loads and functions

TC-PG-07 | Item Usage | Use Potion/Revive | HP updates correctly

TC-PG-08 | Notifications | Trigger adventure sync | Notification appears correctly

# File: /pokemon-go/bug_reports.md

## Sample Bug Reports — Pokémon GO

BUG-PG-001
Title: Player Drift When Idle
Severity: Medium
Steps to Reproduce:
1. Open Pokémon GO.
2. Stand still for 2 minutes.
3. Observe player marker.
Actual Result: Player marker drifts 5-20 meters away.
Expected Result: Player marker remains at actual position.
Notes: Observed on Android 11 (Pixel 3a).

BUG-PG-002
Title: AR Mode Crash on Older Devices
Severity: High
Steps:
1. Start encounter.
2. Enable AR.
Actual: App crashes to home screen.
Expected: Stable AR mode.

# File: /pokemon-go/project_summary.md

## Project Summary — Pokémon GO

I performed an independent manual testing project on Pokémon GO focused on GPS/map accuracy, AR mode, encounters, item usage, and UI flows. I authored 8+ test cases and documented reproducible bugs, including player drift and AR crashes. This helped me practice exploratory testing, bug reporting, and writing clear test cases.

---

# File: /clash-of-clans/README.md

# Clash of Clans — Manual Game Testing Project

Contains test plan, test cases and sample bug reports for a manual QA project on Clash of Clans.

# File: /clash-of-clans/test_plan.md

## Test Plan — Clash of Clans

Objective: Test base building, troop training, battles, clan features, and resource tracking.

Tools: Screen recorder, Google Sheets, OBS.

Deliverables: test_cases.md, bug_reports.md, project_summary.md

# File: /clash-of-clans/test_cases.md

## Test Cases — Clash of Clans

TC-CC-01 | Building Placement | Place new building near others | No overlap, valid placement

TC-CC-02 | Troop Training Queue | Add troops to queue | Queue processes in order

TC-CC-03 | Resource Collection | Collect gold/elixir | Resources update immediately

TC-CC-04 | Matchmaking | Start an attack | Opponent found within expected time

TC-CC-05 | Battle Replay | View replay after battle | Replay matches actual battle

TC-CC-06 | Clan Chat | Send message in clan chat | Message displays for all clan members

TC-CC-07 | Hero Ability | Activate hero ability | Ability triggers and shows cooldown

TC-CC-08 | Push Notification | Complete troop training | Notification received

# File: /clash-of-clans/bug_reports.md

## Sample Bug Reports — Clash of Clans

BUG-CC-001
Title: Troop Count Mismatch After Refresh
Severity: Medium
Steps to Reproduce:
1. Train 10 archers.
2. Close app and reopen.
Actual Result: Display shows 8 archers trained.
Expected Result: Display shows 10 archers.

BUG-CC-002
Title: Replay Damage Desync
Severity: High
Steps:
1. Attack base.
2. Save and view replay.
Actual: Replay shows different damage numbers.
Expected: Replay matches actual battle.

# File: /clash-of-clans/project_summary.md

## Project Summary — Clash of Clans

I conducted manual QA testing for Clash of Clans focusing on base building, troop management, battle mechanics, and clan features. I wrote multiple test cases and submitted reproducible bug reports such as troop count mismatch and replay desync. This project strengthened my test design, reporting, and exploratory testing skills.
