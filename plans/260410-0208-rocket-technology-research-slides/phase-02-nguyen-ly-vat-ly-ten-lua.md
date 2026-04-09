# Phase 02: Nguyen ly vat ly ten lua

## Context Links
- [Research Report 1 - Part 2](../reports/researcher-260410-0203-rocket-technology-comprehensive.md) (lines 498-905)

## Overview
- **Priority:** High
- **Status:** Pending
- **Description:** Core physics foundation. Newton's 3rd Law applied to rockets, Tsiolkovsky equation with worked examples, escape velocity calculation, specific impulse concept, gravity/drag losses, staging theory. Mathematical but accessible.

## Key Facts & Numbers

### Newton's Third Law
- F_action = -F_reaction
- Thrust = dm/dt x v_e (mass flow rate x exhaust velocity)
- Works in vacuum (no air needed to "push against")
- Key insight: thrust depends ONLY on mass flow rate and exhaust velocity

### Tsiolkovsky Rocket Equation (1903)
- **Dv = v_e x ln(m0 / mf)**
- Dv = velocity change, v_e = exhaust velocity, m0 = initial mass, mf = final mass
- Single-stage to LEO (9.4 km/s): mass ratio e^3.13 = 22.9 (impossible)
- Two-stage example: 1st stage Dv=2.5 km/s (ratio 2.85), 2nd stage Dv=6.9 km/s (ratio 5.15)
- 80-90% of rocket mass is propellant
- Equation is exact physics (not approximation), used by all space agencies

### Escape Velocity
- Earth: 11.2 km/s | Moon: 2.4 km/s
- Formula: v_e = sqrt(2GM/r)
- Dv budget by mission: LEO 9.4 km/s | GEO 10.9 km/s | Moon 10.9 km/s | Mars 12.3 km/s

### Specific Impulse (Isp)
- Isp = v_e / g0 (units: seconds)
- Solid rocket: 240-270s | RP-1/LOX: 260-310s | Methane/LOX: 280-360s | H2/LOX: 365-450s | Ion: 3,000s
- Higher Isp = less fuel needed = smaller rocket
- Same Dv (9.4 km/s): Isp=250s needs mass ratio 46; Isp=450s needs only 8.4

### Gravity & Drag Losses
- Gravity loss: 0.5-2.0 km/s depending on thrust-to-weight ratio
- Drag loss: 0.1-0.3 km/s
- Total Dv budget for LEO: ~10.0-10.5 km/s (not just 7.8 km/s orbital velocity)
- Breakdown: orbital velocity 7.8 + altitude 1.6 + gravity loss 1.0 + drag 0.2 + steering 0.1

### Staging Theory
- Single-stage to orbit structurally impossible (mass ratio > 100)
- Each stage sheds empty structure, recovering high mass ratio
- Falcon 9: payload fraction 0.1%, propellant 93.5%, structure 6.4%
- Stage separation: explosive bolts at ~T+160s, spring ejection
- Saturn V total Dv: ~17 km/s (Earth orbit + lunar trajectory)

## Slide Content Outline

### Slide 1: "Dinh luat Newton thu 3 va ten lua" (Newton's 3rd Law & Rockets)
- Animation concept: rocket expelling gas downward, body moves upward
- ASCII diagram from research (rocket + expelled mass)
- Formula: F = dm/dt x v_e
- Key message: "Ten lua hoat dong trong chan khong" (Rockets work in vacuum)
- Real-world: balloon analogy for audience

### Slide 2: "Phuong trinh Tsiolkovsky — Cong thuc quan trong nhat" (Most Important Formula)
- Central formula box: Dv = v_e x ln(m0/mf)
- Two worked examples side by side:
  - Single-stage to LEO: mass ratio 22.9 (IMPOSSIBLE stamp)
  - Two-stage: achievable ratios (CHECK stamp)
- Bar chart: propellant fraction (90%+ of rocket is fuel)
- Insight: "Why rockets are 90% fuel"

### Slide 3: "Van toc thoat va xung luong rieng" (Escape Velocity & Specific Impulse)
- Scale diagram: Earth vs Moon escape velocity (11.2 vs 2.4 km/s)
- Isp comparison chart: solid < kerosene < methane < hydrogen < ion
- Mission Dv ladder: suborbital -> LEO -> GEO -> Moon -> Mars
- Pie chart: Dv budget breakdown for LEO launch

## Key Concepts
- Bao toan dong luong (Conservation of momentum): fundamental principle
- Phuong trinh ten lua (Rocket equation): logarithmic relationship
- Ty so khoi luong (Mass ratio): m0/mf determines everything
- Xung luong rieng (Specific impulse): engine efficiency metric
- Ton that trong luc (Gravity loss): why high thrust matters
- Phan tang (Staging): engineering solution to physics constraint

## Visual Suggestions
1. **Newton's 3rd Law diagram:** Rocket cross-section with force arrows (action/reaction)
2. **Tsiolkovsky equation visualizer:** Interactive-style showing how Dv changes with mass ratio
3. **Isp comparison bar chart:** Color-coded by fuel type, values in seconds
4. **Dv ladder:** Vertical scale from ground to Mars, each mission marked
5. **Staging animation concept:** 3-frame: full rocket -> 1st stage drops -> 2nd stage burns
6. **Pie chart:** "What makes up a rocket's mass" (93% fuel, 6% structure, 1% payload)

## Vietnamese Terminology
| English | Vietnamese |
|---------|-----------|
| Newton's Third Law | Dinh luat 3 Newton |
| Thrust | Luc day |
| Exhaust velocity | Van toc khi xa |
| Mass ratio | Ty so khoi luong |
| Specific impulse | Xung luong rieng |
| Escape velocity | Van toc thoat |
| Gravity loss | Ton that trong luc |
| Staging | Phan tang |
| Conservation of momentum | Bao toan dong luong |
| Drag | Luc can |

## Content Depth
- Newton: Start with balloon analogy, then formalize to F=dm/dt x v_e
- Tsiolkovsky: Show derivation steps (integration of m*dv = -v_e*dm), then practical examples
- Escape velocity: Derive from v_e = sqrt(2GM/r), plug in Earth values
- Isp: Explain as "fuel efficiency" — how long 1 kg of fuel produces 1 N of thrust
- Staging: Use Falcon 9 mass breakdown as concrete example
- Emphasize: these equations are exact physics, not engineering estimates
