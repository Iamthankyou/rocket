# Phase 03: Cau tao va nhien lieu ten lua

## Context Links
- [Research Report 1 - Part 3](../reports/researcher-260410-0203-rocket-technology-comprehensive.md) (lines 1001-1599)

## Overview
- **Priority:** High
- **Status:** Pending
- **Description:** Rocket structural components (payload, stages, interstage, engines) and propellant types (solid, LOX/RP-1, LOX/LH2, LOX/Methane, hypergolic). Engine cycles, nozzle design, regenerative cooling. Engineering-focused section.

## Key Facts & Numbers

### Major Components (Bottom to Top)
- **First stage:** 70-85% of total mass, 1-9 large engines, high thrust
- **Interstage adapter:** Explosive separation bolts
- **Upper stage:** 10-20% of total mass, 1-5 smaller engines, high Isp
- **Payload:** 0.1-1% of launch mass (satellites, capsules)
- Falcon 9 breakdown: 72% 1st stage fuel, 21% 2nd stage fuel, 4% payload, 3% structure

### Propellant Types

| Type | Isp (vacuum) | Characteristics |
|------|-------------|-----------------|
| Solid (APCP) | 270s | Simple, high thrust, no throttle, no restart |
| LOX/RP-1 | 310s | Proven (Falcon 9, Saturn V), dense, sooting |
| LOX/LH2 | 450s | Highest Isp, clean exhaust (water), cryogenic 20K |
| LOX/Methane | 360-380s | Emerging standard, ISRU on Mars, cheaper than H2 |
| Hypergolic | 300-330s | Self-igniting, toxic, room temp, satellite thrusters |

### Key Engines

| Engine | Vehicle | Fuel | Thrust | Isp (vac) |
|--------|---------|------|--------|-----------|
| F-1 | Saturn V S-IC | LOX/RP-1 | 1,522 kN | 263s |
| J-2 | Saturn V S-II | LOX/LH2 | 1,020 kN | 421s |
| Merlin 1D | Falcon 9 | LOX/RP-1 | 934 kN | 310s |
| RS-25 | SLS | LOX/LH2 | 2,110 kN | 453s |
| Raptor | Starship | LOX/CH4 | 510 kN | 380s |
| BE-4 | Vulcan | LOX/CH4 | 1,916 kN | 380s |

### Engine Cycles
- **Gas-generator:** Most common (Merlin). Separate combustion drives turbopump, exhaust dumped
- **Expander:** Most efficient (SSME). Hot gas from cooling jacket drives turbine
- **Pressure-fed:** Simplest (small rockets). Inert gas pressurizes tanks, low performance
- **Full-flow staged combustion:** Most advanced (Raptor). Both propellants drive separate turbines

### De Laval Nozzle
- Converging section: accelerates flow to Mach 1 at throat
- Diverging section: further expansion to Mach 3-5 (3,000-5,000 m/s)
- Expansion ratio (Aexit/Athroat): 40-100:1 for rocket engines
- SSME: 210 bar chamber pressure, 77.5:1 expansion ratio, 450s Isp

### Regenerative Cooling
- Problem: combustion temp 3,600K exceeds metal melting point 2,300K
- Solution: cold propellant circulates through jacket around chamber
- RP-1 enters at 300K, exits at 800K, keeps wall below 600-800K
- All modern liquid engines use this

### Materials
- Tanks: Aluminum 2014-T6 or 2219-T87, 3-6mm thick
- Engine mount: Titanium or steel
- Grid fins (reusable): Titanium, survives 1,200+ K
- Welding: Friction-stir welding (FSW) for tank seams

## Slide Content Outline

### Slide 1: "Cau tao ten lua — Anatomy of a Rocket"
- Full cutaway diagram of multi-stage rocket (Falcon 9 style)
- Labels: payload fairing, 2nd stage, interstage, 1st stage, engines, grid fins, landing legs
- Mass breakdown pie chart: 72% fuel (1st), 21% fuel (2nd), 4% payload, 3% structure
- Key message: "94% cua ten lua la nhien lieu" (94% of rocket is fuel)

### Slide 2: "Nhien lieu ten lua — Tu ran den long" (Propellants — Solid to Liquid)
- Four-column comparison: Solid | LOX/RP-1 | LOX/LH2 | LOX/Methane
- Each column: Isp bar, advantages bullet, key engine example, use case
- Highlight LOX/Methane as future standard (Mars ISRU connection)
- Chemical reactions shown simply: 2H2 + O2 -> 2H2O (cleanest)

### Slide 3: "Dong co ten lua — Trai tim cua phuong tien" (Rocket Engine — Heart of Vehicle)
- De Laval nozzle cross-section with pressure/velocity/temp profiles
- Engine cycle comparison: gas-generator vs full-flow (simple diagram)
- Regenerative cooling concept: fuel flowing through jacket
- Engine comparison table: F-1 vs Merlin vs Raptor (evolution of design philosophy)

## Key Concepts
- Phan tang (Staging): why first stage is large/powerful, upper stage is efficient
- Voi phun De Laval (De Laval nozzle): converging-diverging shape creates supersonic flow
- Lam mat tai sinh (Regenerative cooling): propellant cools engine before burning
- Bom turbo (Turbopump): heart of liquid engine, 20,000-40,000 RPM
- Ty trong nhien lieu (Propellant density): affects tank size and rocket diameter

## Visual Suggestions
1. **Rocket cutaway diagram:** Full-height with callouts for each component
2. **Propellant comparison infographic:** 4 columns with Isp bars, temp indicators
3. **Nozzle cross-section:** Pressure curve from chamber to exit, Mach number labels
4. **Engine cycle flow diagrams:** Gas-generator vs full-flow side by side
5. **Cooling jacket cutaway:** Show fuel channels around combustion chamber
6. **Engine size comparison:** F-1 (huge) vs Merlin (small) vs Raptor — to scale with human silhouette

## Vietnamese Terminology
| English | Vietnamese |
|---------|-----------|
| Propellant | Nhien lieu day |
| Solid fuel | Nhien lieu ran |
| Liquid fuel | Nhien lieu long |
| Combustion chamber | Buong dot |
| Nozzle | Voi phun |
| Turbopump | Bom turbo |
| Oxidizer | Chat oxy hoa |
| Thrust | Luc day |
| Regenerative cooling | Lam mat tai sinh |
| Payload fairing | Vom bao ve tai trong |

## Content Depth
- Structure: Explain why tanks are paper-thin (3-6mm for 3.7m diameter) — structural optimization
- Solid: Good for boosters (SLS SRBs: 11,600 kN each), cannot throttle or restart
- LOX/RP-1: Workhorse fuel, dense, proven, but carbon deposits
- LOX/LH2: Best performance but nightmare handling (20K, explosive 4-75% in air, low density)
- LOX/Methane: Future standard — producible on Mars via Sabatier reaction (CO2 + H2 -> CH4 + H2O)
- Nozzle: Counter-intuitive — diverging section increases velocity above Mach 1
- Turbopump: Most complex component (SSME had 10,000+ parts, SpaceX simplified)
