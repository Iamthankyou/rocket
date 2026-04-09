# Phase 04: Quy trinh phong ten lua

## Context Links
- [Research Report 1 - Part 4](../reports/researcher-260410-0203-rocket-technology-comprehensive.md) (lines 1606-1900+)

## Overview
- **Priority:** High
- **Status:** Pending
- **Description:** Complete launch process from T-24h countdown through orbital insertion. Covers pre-launch preparations, automated sequencer, engine ignition, liftoff, gravity turn, Max-Q, stage separation, and orbital insertion. Uses Falcon 9 as primary example.

## Key Facts & Numbers

### Countdown Timeline (Falcon 9)
- **T-24h:** Tanking begins. LOX flow ~200-300 kg/min, RP-1 ~500 kg/min. 2-3h total loading
- **T-4h:** Final checks. Avionics power-up, payload bay sealed, launch director briefing
- **T-1h:** Automated sequencer starts. Rocket computer assumes autonomous control
- **T-20min:** Personnel cleared from pad, hazard perimeter enforced
- **T-10min:** Terminal count. Hydraulic power, gimbal servo test, cryogenic chilldown
- **T-1min:** Engine ignition sequence initiated, hydraulics to 3,000 psi
- **T-45s:** Engine start — chamber pressure 250 bar in ~100ms, turbopump 20,000->36,000 RPM
- **T-3s:** All 9 engines at full thrust (13,700 kN), vehicle held by clamps
- **T-0:** Hold-down clamps released (explosive bolts), LIFTOFF

### Ascent Profile
- **Phase 1 — Vertical Ascent (T+0 to T+10s):** 0->2 km altitude, 0->200 m/s
- **Phase 2 — Gravity Turn (T+10 to T+80s):** 2->40 km, 200->2,000 m/s, pitch 30->60 deg
- **Phase 3 — Max-Q (T+60-80s):** ~15 km altitude, peak dynamic pressure 30-35 kPa
- **Phase 4 — MECO (T+162s):** Main Engine Cut-Off, 65 km altitude, 2,500 m/s
- **Phase 5 — Stage Separation (T+170s):** Explosive bolts, spring ejection
- **Phase 6 — 2nd Stage Burn (T+171 to T+530s):** To 185 km, 7,800 m/s orbital velocity
- **Phase 7 — Payload Deploy:** Fairing separation, satellite release, orbit confirmed

### Stage Separation Details
- MECO at T+162s -> interstage separation at ~T+170s
- Mechanisms: explosive bolts shear, spring pushes stages apart
- 1st stage immediately begins reentry sequence (if reusable)
- 2nd stage ignition at T+171s (vacuum-optimized Merlin)
- Critical timing: too early = wasted velocity, too late = gravity loss

### Reentry & Landing (Reusable 1st Stage)
- Boostback burn: redirects trajectory to landing site
- Entry burn: 3 engines, slows from ~1,500 m/s
- Grid fins deploy at ~70 km for aerodynamic steering
- Landing burn: 1 engine, final 30 seconds, precision <1m
- Touchdown speed: ~2 m/s on drone ship or landing pad
- 100+ successful Falcon 9 landings achieved

### Abort Criteria
- Weather: lightning within 10 nmi, high winds, cloud ceiling
- Vehicle: engine underperformance at T-3s = auto-abort
- Range safety: trajectory deviation triggers Flight Termination System
- Propellant contamination: detected during loading = scrub

## Slide Content Outline

### Slide 1: "Dem nguoc phong ten lua" (Launch Countdown)
- Vertical timeline: T-24h -> T-0, key events at each milestone
- Infographic style: clock icons, status indicators (green=go, red=hold)
- Highlight T-45s engine start sequence (staggered ignition, 9 engines)
- Photo suggestion: Falcon 9 on pad with vapor venting
- Key stat: "250 bar trong 100 mili giay" (250 bar in 100 milliseconds)

### Slide 2: "Quy dao bay — Tu mat dat den quy dao" (Flight Trajectory — Ground to Orbit)
- Curved trajectory diagram: vertical ascent -> gravity turn -> orbital insertion
- Labels at each phase with altitude, velocity, time
- Max-Q callout: "Ap suat dong cuc dai" at 15 km
- Stage separation moment with both stages diverging
- Dv budget breakdown: 7.8 orbital + 1.6 altitude + 1.0 gravity loss + 0.3 drag + 0.2 steering = 10.9

### Slide 3: "Tach tang va ha canh tai su dung" (Stage Separation & Reusable Landing)
- 4-frame sequence: separation -> boostback -> entry -> landing
- Grid fins diagram with titanium callout
- Landing precision stat: <1 meter accuracy
- Before/after cost comparison: expendable ($60M) vs reusable ($30M estimated)
- 100+ successful landings milestone

## Key Concepts
- Dem nguoc tu dong (Automated countdown): computer controls final 10 minutes
- Chuyen huong trong luc (Gravity turn): passive trajectory curving, no pilot input needed
- Max-Q (Ap suat dong cuc dai): peak structural stress, throttle-down point
- MECO: Main Engine Cut-Off — precise timing determines orbit
- Ha canh dong luc (Powered landing): 1 engine, 30-second precision descent

## Visual Suggestions
1. **Countdown infographic:** Vertical timeline T-24h to T-0 with icons
2. **Trajectory arc diagram:** Curved path from launch pad to orbit with phase labels
3. **Max-Q pressure visualization:** Dynamic pressure curve vs altitude
4. **Stage separation sequence:** 4-panel illustration showing separation moment
5. **Landing sequence:** Boostback -> entry -> grid fins -> touchdown
6. **Before/after comparison:** Expendable rocket (crash) vs reusable (landing)

## Vietnamese Terminology
| English | Vietnamese |
|---------|-----------|
| Countdown | Dem nguoc |
| Liftoff | Cat canh / Roi be phong |
| Gravity turn | Chuyen huong trong luc |
| Stage separation | Tach tang |
| Max-Q | Ap suat dong cuc dai |
| Main Engine Cut-Off | Tat dong co chinh |
| Orbital insertion | Chen quy dao |
| Payload deploy | Trien khai tai trong |
| Boostback burn | Dot chay quay ve |
| Grid fins | Canh luoi |

## Content Depth
- Countdown: Emphasize automation — human role is "Go/No-Go" decision, computer executes
- Engine start: Staggered ignition (200ms between engines) reduces structural shock
- Gravity turn: Physics explanation — gravity provides centripetal acceleration naturally
- Max-Q: Why rockets throttle down (reduce structural load), then throttle up after passing
- Separation: Millisecond precision required — spring + explosive bolts
- Landing: Engineering marvel — 1st stage returns from 65 km at 2,500 m/s to soft landing
- Abort scenarios: Automated safety systems, Flight Termination System as last resort
