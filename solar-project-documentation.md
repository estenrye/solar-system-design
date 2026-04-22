# Solar Array Project — Bloomington, MN
## Complete Conversation Documentation

**Date:** April 22, 2026  
**Location:** 8825 Columbus Ave S, Bloomington, Minnesota 55420  
**Latitude:** 44.8°N  
**Prepared with:** Claude (Anthropic)

---

## Table of Contents

1. [Project Context & Site Parameters](#1-project-context--site-parameters)
2. [Initial System Design](#2-initial-system-design)
3. [EG4 Equipment Selection](#3-eg4-equipment-selection)
4. [Energy Usage Analysis](#4-energy-usage-analysis)
5. [Second Array Added](#5-second-array-added)
6. [Bifacial Panel Upgrade](#6-bifacial-panel-upgrade)
7. [Federal Tax Credit Correction](#7-federal-tax-credit-correction)
8. [Phased Build Plan](#8-phased-build-plan)
9. [GridBOSS Integration & Generator](#9-gridboss-integration--generator)
10. [100A Service & Interior Panel Questions](#10-100a-service--interior-panel-questions)
11. [Interior Panel — Eaton-Specific Analysis](#11-interior-panel--eaton-specific-analysis)
12. [Final System Specification](#12-final-system-specification)
13. [All Dashboard Outputs](#13-all-dashboard-outputs)

---

## 1. Project Context & Site Parameters

### User Prompt
> *"I have a space in my back yard that is 22 feet by 22 feet in area. I want to build a ground mount solar array with the optimal south facing pitch. Ideally I would like to have a patio under it. I am open to buy versus build solutions, but am comfortable building the array with wood and rail mounts."*

### Follow-up Clarifications Provided
- **Location:** Bloomington, MN (44.8°N latitude)
- **Goal:** Maximize power output for complete replacement of energy consumption + on-site battery backup
- **Budget:** Meeting requirements is the concern, not budget

### Key Site Parameters Established
| Parameter | Value |
|---|---|
| Latitude | 44.8°N |
| Optimal fixed tilt | 45° (latitude-matched, winter bias) |
| Available space | 22 ft × 22 ft |
| Panel footprint at 45° | ~4.6 ft horizontal depth per row |
| Winter solar elevation (Dec) | ~22° above horizon |
| Row spacing needed (no shading) | ~12–13 ft between row bases |
| Max panels in space | 14 panels (one deep row, 2 high) |
| Patio feasibility | ✓ Yes — ~9 ft south of array |

### Structure Design (DIY Wood + Rail)
- **Posts:** 6×6 pressure-treated lumber, 4 posts in concrete footings
- **Front (south) posts:** ~6 ft tall
- **Rear (north) posts:** ~10 ft tall (creates 45° pitch)
- **Beams:** Doubled 2×10 or LVL spanning 22 ft
- **Rafters:** 2×6 or 2×8 at 24" OC, running north-south
- **Rail:** IronRidge XR100 aluminum rails on rafters
- **Patio:** White limestone gravel beneath array (~400 sq ft)

---

## 2. Initial System Design

### Solar Math
- 45° tilt at 44.8°N is optimal for annual production with winter bias
- 14 panels × 430W = **4,800W (4.8 kW)** initially estimated
- At 4.5 peak sun hours/day → ~7,800 kWh/year (below MN avg of ~9,000 kWh)
- Updated to 14 panels to achieve ~6 kW target

### Initial Inverter & Battery Recommendation
- **Inverter:** SolarEdge SE6000H (later superseded by EG4 equipment)
- **Batteries:** 2× Tesla Powerwall 3 (later superseded)
- **Minnesota Incentives Noted:**
  - Xcel Solar\*Rewards: $0.03/kWh for 10 years
  - Net metering (Xcel)
  - MN property tax exemption
  - Xcel battery incentive: $175/kWh (capped at $5,000)

---

## 3. EG4 Equipment Selection

### User Prompt
> *"I would like to use EG4 for batteries and inverters."*

### EG4 Equipment Adopted
**Inverter: EG4 18kPV Hybrid**
- 18kW PV input, 12kW continuous AC output
- 3 MPPTs (600VDC max each)
- Split-phase 120/240V output
- Supports grid sellback (UL1741 SB)
- EMP hardened
- Up to 10 units parallelable

**Batteries: EG4 PowerPro WallMount All-Weather**
- 14.3 kWh per unit (48V, 280Ah LiFePO₄)
- Self-heating for cold climates (activates below 32°F — critical for MN)
- IP65 weather-rated, outdoor-capable
- 8,000+ cycles at 80% DoD
- 10-year warranty
- Up to 64 units in parallel
- UL1973, UL9540A certified

**Recommendation: 4× PowerPro = 57.2 kWh storage**

---

## 4. Energy Usage Analysis

### User Prompt
> *User provided 24 months of Xcel Energy billing data (May 2024 – April 2026)*

### 24-Month Usage Data
| Month | Usage (kWh) | Month | Usage (kWh) |
|---|---|---|---|
| Apr 2026 | 1,112 | Apr 2025 | 968 |
| Mar 2026 | 1,137 | Mar 2025 | 1,375 |
| Feb 2026 | 1,264 | Feb 2025 | 1,516 |
| Jan 2026 | 1,103 | Jan 2025 | 1,460 |
| Dec 2025 | 984 | Dec 2024 | 1,468 |
| Nov 2025 | 874 | Nov 2024 | 1,312 |
| Oct 2025 | 1,509 | Oct 2024 | 1,645 |
| Sep 2025 | 1,402 | Sep 2024 | 1,938 |
| Aug 2025 | 2,056 | Aug 2024 | 1,997 |
| Jul 2025 | 2,066 | Jul 2024 | 1,737 |
| Jun 2025 | 1,393 | Jun 2024 | 1,544 |
| May 2025 | 1,077 | May 2024 | 1,040 |

### Key Findings
| Metric | Value |
|---|---|
| Year 1 total (May 2024–Apr 2025) | 17,284 kWh |
| Year 2 total (May 2025–Apr 2026) | 14,820 kWh |
| **2-year average annual** | **~16,052 kWh/yr** |
| Average monthly | 1,337 kWh |
| Average daily | ~44.5 kWh |
| Peak month | Jul 2025 — 2,066 kWh |
| Lowest month | Nov 2025 — 874 kWh |

**Critical insight:** Actual usage is **~78% above** the MN average of 9,000 kWh/yr assumed in early planning. Summer A/C months (Jul–Oct) dominate consumption.

### Single Array Coverage Assessment
- 6.02 kW single array → ~9,700 kWh/yr → only **60% offset**
- Net metering identified as essential to bridge the gap
- Space constraint (22×22 ft) is the binding limit — 14 panels maximum

---

## 5. Second Array Added

### User Prompt
> *"I have another 22 foot by 22 foot area that could be utilized in addition."*

### Updated System with Dual Arrays
| Metric | Single Array | Dual Array |
|---|---|---|
| Total panels | 14 | 28 |
| Combined DC | 6.02 kW | 12.04 kW |
| Annual production | ~9,700 kWh | ~19,400 kWh |
| Coverage of actual usage | 60% | 121% |
| Annual surplus | — | ~3,350 kWh |

### Updated Equipment for Dual Array
- **Panels:** 28× 430W monofacial (later upgraded to bifacial)
- **Inverters:** 2× EG4 18kPV (one per array, parallel to shared battery bank)
- **Batteries:** 6× EG4 PowerPro (85.8 kWh total)
- **Rationale for 2 inverters:** Redundancy — if one fails, the other keeps running

---

## 6. Bifacial Panel Upgrade

### User Prompt
> *"Do these arrays take into account bi-facial panels?"*

### Answer: No — and They Should Be Used

The prior analysis used standard monofacial production figures. Bifacial panels were identified as highly beneficial for this specific setup due to:

1. **Ground mount with clearance** — rear face fully exposed (minimum 20" recommended by NREL)
2. **Minnesota snow** — fresh snow has albedo of 0.80–0.90, highest of any surface; bifacial systems in MN climate zones see ~20% winter gain from snow albedo
3. **White gravel patio** — intentional albedo boost (0.40–0.50) year-round

### Bifacial Gain by Patio Surface
| Surface | Albedo | Bifacial Gain |
|---|---|---|
| Dark pavers | 0.10 | ~5–8% |
| Green grass | 0.22 | ~10–12% |
| Natural concrete | 0.35 | ~15–18% |
| **White limestone gravel** | **0.45** | **~20%** ← Recommended |
| White concrete pavers | 0.65 | ~22–28% |
| Fresh snow (Nov–Mar) | 0.85 | +25–30% seasonal bonus |

### Panel Upgrade: TOPCon Bifacial
- **Recommended:** LONGi Hi-MO 6 Explorer or REC Alpha Pure RB
- **Rating:** 445W (vs 430W monofacial)
- **Bifaciality factor:** 88–92% (TOPCon achieves 85–95% vs PERC at 65–75%)
- **Degradation rate:** 0.3–0.4%/yr (vs 0.5%/yr for monofacial glass-backsheet)
- **Price premium:** Only 3–8% over equivalent monofacial in 2026

### Bifacial Production Estimates (Dual Array)
| Scenario | Per Array | Combined |
|---|---|---|
| Monofacial baseline | 9,700 kWh/yr | 19,400 kWh/yr |
| Bifacial + white gravel (20% gain) | 11,640 kWh/yr | 23,280 kWh/yr |
| + MN snow bonus (~5% annual avg) | ~11,700 kWh/yr | ~23,400 kWh/yr |

### Bifacial Mounting Requirements
- **Min ground clearance:** 20–24" from bottom panel edge to gravel surface
- **Row gap:** 3–5" between stacked portrait rows (snow shed + albedo contribution)
- **Racking:** IronRidge XR100 is open-frame — rear surface fully exposed ✓
- **Wiring:** Route all DC wiring along front face of rafters/posts — never across rear of panels

### Upgrade Cost vs. Benefit
| Item | Cost |
|---|---|
| 28× monofacial 430W → bifacial TOPCon 445W | +~$560 |
| White limestone gravel (2× ~400 sq ft) | +~$600 |
| **Total upgrade cost** | **+~$1,160** |
| Additional annual production value | ~$840–990/yr |
| **Upgrade payback** | **~1.2–1.4 years** |

---

## 7. Federal Tax Credit Correction

### User Prompt
> *"There is no federal tax credit at this time."*

### Confirmed Finding
The **30% residential Investment Tax Credit (Section 25D)** expired **December 31, 2025** under the *One Big Beautiful Bill* signed July 4, 2025. All prior dashboards incorrectly showed a 30% federal deduction — this was corrected in all subsequent outputs.

### Current Federal Status
- ❌ **Residential 30% ITC** — expired Dec 31, 2025. Not available for 2026 installs.
- ✅ **Commercial/third-party ITC** — still available through 2027 for leases/PPAs only
- ❌ **Battery incentive (residential)** — also expired Dec 31, 2025

### Remaining Minnesota Incentives (2026)
| Incentive | Value | Notes |
|---|---|---|
| **Xcel Solar\*Rewards** | $0.03/kWh × all production × 10 yrs | ~$698/yr for dual bifacial system |
| **Xcel Battery Incentive** | $175/kWh, capped at $5,000 | Applied to battery bank at install |
| **MN Sales Tax Exemption** | 6.875% on all equipment | Panels, inverters, batteries, racking |
| **Net Metering (Xcel)** | Credit at avg utility rate | ~$976/yr surplus credit (dual array) |
| **MN Property Tax Exemption** | 100% exempt | Added home value from solar not taxed |

---

## 8. Phased Build Plan

### User Prompt
> *"Can you also produce a parallel plan where I build the single array system using bifacial panels and expand to a second array?"*

### Plan A — Full Dual Array Build
Build both arrays simultaneously. Lower total cost, one permit, one contractor mobilization.

### Plan B — Phased Build
**Phase 1:** Single array + GridBOSS + full infrastructure (73% offset)  
**Phase 2:** Add second array — plugs into pre-wired GridBOSS port 2 (completes to 145% offset)

### Key Pre-Sizing Items for Phase 1 (if doing phased)
| Item | Purpose | Cost to Do in Phase 1 | Saved vs. Phase 2 |
|---|---|---|---|
| 200A service panel | Required for GridBOSS | Included in scope | N/A |
| Empty conduit home-run | Phase 2 DC wiring path | ~$300–500 | ~$600–900 |
| Battery busbar for 6 units | Populate 4 now, add 2 later | Minimal | ~$200 |
| Panel breaker slots | Phase 2 inverter connection | ~$0 incremental | ~$400 |

### Plan Comparison
| | Plan A (Full Build) | Plan B Phase 1 | Plan B Phase 2 |
|---|---|---|---|
| Gross cost | ~$47,210 (Opt 3) | ~$28,680 (Opt 3) | ~$21,080 |
| MN sales tax saving | ~$2,444 | ~$1,445 | ~$1,000 |
| Battery incentive | −$5,000 | −$5,000 | $0 (cap used) |
| Net cost | ~$39,766 | ~$22,235 | ~$20,080 |
| Annual savings (full) | ~$3,841/yr | ~$1,931/yr | +$1,910/yr |
| Production | 23,280 kWh/yr | 11,640 kWh/yr | 23,280 kWh/yr |
| Offset | 145% | 73% | 145% |
| Permits | 1 | 2 | — |

---

## 9. GridBOSS Integration & Generator

### User Prompt
> *"Can we modify the plan to include the use of a grid Boss to allow for expansion and integration of a generator?"*

### EG4 GridBOSS MID v3.1
The GridBOSS is a Microgrid Interconnect Device (MID) — a single hub replacing up to 10 separate components (transfer switch, subpanel, combiner, interlock, etc.).

**Key Specifications:**
| Spec | Value |
|---|---|
| Service entrance rating | 200A / 22kAIC |
| Hybrid inverter ports | 3× @ 90A each |
| Generator port | 125A, 2-wire auto-start |
| Smart load ports | 4× (125A / 80A / 60A / 60A) |
| Operating temp | −40°F to 113°F |
| NEMA rating | 3R (outdoor-rated) |
| Certifications | UL1741, UL67, UL869A |
| Required main breaker | Eaton CSR2200N (200A) — sold separately |
| Compatible inverters | EG4 12kPV, 18kPV, FlexBOSS18, FlexBOSS21 only |
| Estimated install savings | ~$3,000–7,500 vs. traditional architecture |

**Generator Integration — How It Works:**
1. Grid fails OR battery SOC drops below set threshold
2. GridBOSS sends 2-wire dry-contact signal → generator starts
3. Programmable warm-up delay (60–120 sec typical)
4. Transfer switch engages → generator powers loads + charges batteries
5. When batteries reach target SOC, generator disconnects
6. Programmable cool-down before shutdown

### Inverter Upgrade: 18kPV → FlexBOSS21
Adding the GridBOSS triggered an inverter recommendation change:

| | EG4 18kPV | EG4 FlexBOSS21 |
|---|---|---|
| PV input | 18kW | 21kW usable / 24kW max |
| AC output (no PV) | 12kW | 12kW |
| **AC output (with PV)** | **12kW** | **16kW** ← key advantage |
| MPPTs | 3× 600V | 3× (26A/26A/15A) — 5 strings |
| GridBOSS breaker | 70A | 90A |
| GridBOSS native | Partial | ✓ Designed together |
| Price delta | baseline | ~$0–200/unit more |

### Smart Port Uses
- **Port 1 (125A):** EV charger Level 2 — bypasses interior panel entirely
- **Port 2 (80A):** HVAC / heat pump load shedding
- **Port 3 (60A):** Pool / hot tub / subpanel
- **Port 4 (60A):** Water heater / programmable load
- **3rd inverter port:** Reserved for future expansion beyond Phase 2

### Recommended Generator (not included in BOM)
- Generac 14kW Air-Cooled Standby (~$4,500–6,000 + ~$2,000–3,000 install)
- Kohler 14RESAL LP/NG (~$4,000–5,500 + install)
- With 85.8 kWh batteries, generator activates rarely — mainly during multi-day winter overcast

---

## 10. 100A Service & Interior Panel Questions

### User Prompt
> *"My current energy usage... Also my residence currently has 100-AMP electrical service, do I need to upgrade that to 200-AMP?"*

### Answer: Yes — 200A Service Is Required

The GridBOSS requires a 200A service entrance with the Eaton CSR2200N 200A main breaker. There is no code-compliant workaround maintaining UL certification at 100A service.

**Reasons:**
- GridBOSS is rated as a 200A service entrance device — its Eaton CSR2200N main breaker is a 200A unit
- Two FlexBOSS21 units at 90A each = 180A of inverter capacity alone
- The GridBOSS replaces your main service entrance panel — it must match utility feed ampacity

**Good news:** The GridBOSS IS the new 200A panel. You're not buying a 200A panel AND a GridBOSS — the GridBOSS serves as the service entrance.

### Interior Panel Question
> *"Do I need to replace my 100A breaker panel inside my house or can the GridBoss feed it?"*

**Answer: No replacement required.** The GridBOSS feeds the existing interior panel as a subpanel via its Backed-Up Loads output. The one required change: the neutral-ground bond moves from the interior panel to the GridBOSS (standard subpanel conversion, ~30 min).

**Wiring topology:**
```
Xcel Meter (200A service)
    ↓ 200A service conductors
EG4 GridBOSS MID  ←→  FlexBOSS21 × 2, Batteries, Generator
    ↓ Backed-Up Loads output
    ↓ 100A feeder wire
Existing interior panel (now a subpanel)
    ↓ All existing circuits — unchanged
```

---

## 11. Interior Panel — Eaton-Specific Analysis

### User Prompt
> *"My current load center in my house is an Eaton load center certified up to 225 Amps Max with a Eaton CSR 25k 100 AMP Circuit breaker. It has 32 breakers and is full. I would like room for expansion."*

### Key Insight: Panel Bus Is Already 225A

Your panel box is already rated to 225A — the **100A CSR25K breaker is the only limiting factor**, not the panel hardware. This is a significantly better starting point than a standard 100A panel.

**Your Panel:**
- Bus rating: 225A ✓
- Current main breaker: 100A CSR25K (limiting factor)
- Spaces: 32 — all full
- Breaker type: Eaton Type BR (1-inch)
- CSR family: Same family as GridBOSS's required CSR2200N

### Three Options Analyzed

**Option 1 — Keep As-Is ($0 incremental)**
- Bond relocation only (~1 hr)
- 100A ampacity limit remains
- 0 open spaces — panel stays full
- Good for: minimal budget, no new circuits needed

**Option 2 — Swap Main Breaker (~$250)**
- Replace CSR25K 100A with CSR2225 225A (same bolt-on form factor)
- Removes 100A ceiling, utilizes full 225A bus
- 0 open spaces — still full
- Good for: remove amp ceiling without space needs

**Option 3 — New 42-Space Panel (~$850) ✓ RECOMMENDED**
- Replace panel box with **Eaton BR4242B225**
  - Catalog #: `BR4242B225` or `BRP42BC225`
  - 42 spaces / 84 circuits
  - 225A bus rating
  - ~$170 at Lowes/Home Depot
- Install **CSR2225 225A** main breaker (~$100)
- All 32 existing Eaton BR breakers re-land — no replacements
- Results in **10 open spaces** for expansion
- Total incremental: ~$720–850
- As standalone project later: ~$1,800–2,500 → **save ~$1,000–1,600 by doing it now**

### Option 3 Space Allocation Plan
With 42 spaces and 32 existing circuits re-landed, 10 open spaces enable:
- Dedicated monitoring circuit (solar/GridBOSS)
- Future heat pump circuit
- Future EV charger (backup to smart port)
- AFCI/GFCI code upgrades
- Any additional appliance circuits

---

## 12. Final System Specification

### Complete Equipment List

| Component | Model | Qty | Est. Cost |
|---|---|---|---|
| Solar panels | TOPCon 445W Bifacial (LONGi Hi-MO 6 or REC Alpha Pure RB) | 28 | ~$8,960 |
| Inverters | EG4 FlexBOSS21 | 2 | ~$6,200 |
| GridBOSS MID | EG4 GridBOSS v3.1 | 1 | ~$1,800 |
| GridBOSS breakers | 90A Eaton × 2 + gen/smart port breakers | — | ~$600 |
| Batteries | EG4 PowerPro WallMount All-Weather 14.3kWh | 6 | ~$19,800 |
| Racking | IronRidge XR100 kit (open-frame, bifacial-compatible) | 2 | ~$1,200 |
| Structures | PT Wood Pergola (6×6 posts, LVL beams, 45° rafters, concrete) | 2 | ~$3,000 |
| Patio surface | White limestone gravel (~400 sq ft each) | 2 | ~$600 |
| Interior panel | Eaton BR4242B225 + CSR2225 225A breaker | 1 | ~$850 |
| Electrical/labor | Licensed electrician (200A service, GridBOSS, permits, interconnect) | — | ~$7,800 |
| **Gross Total** | | | **~$51,810** |
| MN Sales Tax Exemption (6.875% on equipment) | | | −~$2,669 |
| Xcel Battery Incentive (capped) | | | −$5,000 |
| Federal ITC | | | **$0 (expired)** |
| **Net Cost After MN Incentives** | | | **~$44,141** |

### System Performance Summary
| Metric | Value |
|---|---|
| Total DC capacity | 12.46 kW |
| Annual production (bifacial + white gravel + snow) | ~23,280 kWh/yr |
| Your annual consumption | ~16,052 kWh/yr |
| **Annual surplus to grid** | **~7,228 kWh/yr** |
| **System offset** | **145%** |
| Battery storage | 85.8 kWh (6× EG4 PowerPro) |
| Battery coverage — avg day | ~1.9 days |
| Battery coverage — winter day | ~2.2 days |
| Battery coverage — summer peak | ~1.3 days |
| Xcel Solar\*Rewards (10 yr) | ~$698/yr |
| Net metering surplus credit | ~$976/yr |
| **Total annual savings** | **~$3,841/yr** |
| Simple payback | ~11.5 years |
| 25-year net savings (3% escalation) | ~$55,000+ |

### Electrical Architecture
```
Xcel Energy Grid (200A service after upgrade)
    ↓
Eaton CSR2200N 200A breaker
    ↓
EG4 GridBOSS MID v3.1 (service entrance)
    ├── Inverter Port 1 (90A) → FlexBOSS21 #1 → Array 1 (14× 445W, 6.23kW DC)
    ├── Inverter Port 2 (90A) → FlexBOSS21 #2 → Array 2 (14× 445W, 6.23kW DC)
    ├── Inverter Port 3 (90A) → RESERVED (future expansion)
    ├── Generator Port (125A) → Auto-start propane/NG standby generator
    ├── Smart Port 1 (125A) → EV charger / HVAC
    ├── Smart Port 2 (80A)  → Available
    ├── Smart Port 3 (60A)  → Available
    ├── Smart Port 4 (60A)  → Available
    ├── Backed-Up Loads (200A) → Eaton BR4242B225 interior panel (42-space, 225A)
    │       └── All 32 existing circuits (unchanged) + 10 open spaces
    └── Non-Backed-Up Loads → Non-essential circuits

Battery Bank: 6× EG4 PowerPro 14.3kWh = 85.8kWh
    └── Connected to both FlexBOSS21 inverters via shared 225A busbar
```

### Minnesota-Specific Notes
- **Xcel interconnection:** File Solar\*Rewards application + net metering interconnection agreement
- **City of Bloomington permits:** Building permit (ground mount structure) + electrical permit required
- **System sizing rule:** Must not exceed 120% of historical energy usage under ideal conditions (Xcel requirement) — 12.46kW is well within limits
- **Cold weather:** EG4 PowerPro self-heating activates below 32°F — no cold weather performance degradation
- **Snow:** Bifacial panels continue producing through front-face snow accumulation via rear-face albedo; row gap allows snow shedding

---

## 13. All Dashboard Outputs

The following interactive HTML dashboards were generated during this conversation. Download each file and open in any web browser.

### Dashboard 1 — Initial Single Array Analysis
**File:** `solar-analysis.html`  
**Contents:** Monthly usage vs. single-array production, season balance, system sizing, Minnesota incentives, initial BOM with previous federal ITC (now expired — see Dashboard 5+)

---

### Dashboard 2 — Dual Array Analysis (Monofacial)
**File:** `solar-analysis-dual.html`  
**Contents:** Combined dual-array production vs. actual usage, season breakdown, Plan A (full build) vs. Plan B (phased) comparison, financial analysis  
*Note: Used monofacial production figures and included 30% federal ITC — both superseded by later dashboards*

---

### Dashboard 3 — Bifacial Dual Array Analysis
**File:** `solar-analysis-bifacial.html`  
**Contents:** Updated production with 20% bifacial gain + 5% snow albedo bonus, albedo surface guide, bifacial mounting requirements, updated BOM  
*Note: Still included 30% federal ITC — superseded by Dashboard 4+*

---

### Dashboard 4 — Dual Plan (No Federal ITC, No GridBOSS)
**File:** `solar-plans-final.html`  
**Tabs:**
- **A** — Full dual bifacial array build
- **B** — Phase 1 single array
- **B2** — Phase 2 expansion
- **C** — Side-by-side comparison  

*Correct MN incentives, no federal ITC. Does not include GridBOSS — superseded by Dashboard 5*

---

### Dashboard 5 — Complete Final Dashboard (Current)
**File:** `solar-gridboss-final.html`  
**Tabs:**
- **A** — Plan A: Dual array + GridBOSS + Generator (full build)
- **B** — Plan B: Phase 1 single array + GridBOSS
- **B2** — Plan B Phase 2: Expansion
- **C** — Side-by-side comparison
- **D** — 100A → 200A service upgrade details
- **E** — Interior Panel Decision (3-option toggle: keep 100A / swap breaker / new 42-space panel)

**Interactive Features:**
- Live 3-way panel option toggle in Tabs A and B — updates all costs, payback, and 25-year savings in real time
- Monthly production vs. usage charts with bifacial + snow bonus
- Season-by-season balance analysis
- Complete BOM with MN incentives applied
- Correct financials: no federal ITC, MN sales tax exemption, Xcel battery incentive

**Default State:** Option 3 (New 42-space 225A Eaton BR panel) pre-selected as recommended

---

## Key Decisions Log

| Decision Point | Options Considered | Choice Made | Rationale |
|---|---|---|---|
| Inverter brand | SolarEdge, various | EG4 | User specified EG4 ecosystem |
| Initial inverter model | EG4 6000XP, 12000XP, 18kPV | 18kPV | Grid sellback required |
| Final inverter model | EG4 18kPV, FlexBOSS21 | FlexBOSS21 | GridBOSS native; 16kW w/PV vs 12kW |
| Battery count | 2×, 4×, 6× PowerPro | 6× (85.8 kWh) | Dual array charging rate + winter resilience |
| Panel type | Monofacial 430W, bifacial TOPCon 445W | Bifacial TOPCon 445W | MN snow albedo ideal; ~1.3yr upgrade payback |
| Patio surface | Concrete, grass, gravel | White limestone gravel | Best albedo/cost/function balance |
| Arrays | 1× (22×22), 2× (22×22) | 2× | Required for full offset of actual usage |
| Build approach | Full buy, full DIY, hybrid | Hybrid: DIY structure + buy equipment | Cost savings + electrician for compliance |
| Phasing | All at once vs. phased | Either (both planned) | Plan A saves ~$1,500; Plan B spreads cash |
| Service entrance | Keep 100A, upgrade 200A | Upgrade 200A | Required by GridBOSS hardware |
| Interior panel | Keep/swap breaker/new panel | New 42-space Eaton BR4242B225 | Only option providing expansion room |

---

## Vendor & Procurement Notes

- **EG4 Equipment (primary source):** Signature Solar — [signaturesolar.com](https://signaturesolar.com) — EG4's primary authorized distributor
- **EG4 alternate sources:** Current Connected, Unbound Solar, altE Store
- **Panels:** CivicSolar, Unbound Solar, or altE Store for wholesale pricing
- **Racking:** IronRidge XR100 — available through solar distributors
- **Interior panel (Eaton BR4242B225):** Lowes, Home Depot, or electrical supply houses (~$170)
- **Xcel Solar\*Rewards application:** [xcelenergy.com/solarrewards](https://www.xcelenergy.com)
- **Xcel interconnection application:** Submit before system energization
- **City of Bloomington permits:** Required — building + electrical

---

*Document generated April 22, 2026 via Claude (Anthropic)*  
*All cost estimates are approximate and subject to change. Consult a licensed electrician for final design and permitting.*
