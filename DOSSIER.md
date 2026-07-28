# Athlete Training Dossier & Performance Roadmap

**Dossier Version:** v1.1.1  
**Protocol Compatibility:** Section 11 v11.6+  
**Date:** 2026-07-24  
**Primary Source Systems:** Intervals.icu | [Other platforms]

This document serves as a reference template for endurance athletes using the deterministic AI-coaching framework defined in Section 11.

---

## Quick Start

1. Fill in your athlete profile (Section 1)
2. Document your equipment (Section 2)
3. Define your training schedule and goals (Section 3)
4. Enter your current performance metrics (Section 4)
5. Set up your nutrition/fueling protocol (Section 5)
6. Link this dossier to your JSON data mirror (see Section 11 for protocol)

---

## 1. Athlete Overview

### Athlete Profile

| Field | Value |
|-------|-------|
| Name | Rodrick Borg |
| Age | 38 |
| Height | 175cm |
| Current Weight | 78.7 kg |
| Target Weight | 75 kg |
| Location | Affoltern am Albis, Switzerland |

**Weigh-in Protocol:** [e.g., Once weekly, Friday morning, after bathroom, before food/drink]

### Medications & Supplements (Optional)

| Time | Items |
|------|-------|
| [Time] | [List medications/supplements] |
| [Time] | [List medications/supplements] |

### Sport Focus

| Type | Description |
|------|-------------|
| Primary | Cycling Big Days in the mountains - Endurance |
| Secondary | Running, Rowing, Swimming, Strength Training, Flexibility and Mobility |

### Goals

| Goal | Target Date |
|------|-------------|
| Grimsel - Susten - Nufenen passes | 2027 |
| [Secondary goal] | [Year] |
| [Tertiary goal] | [Year] |

**Current Phase:** Aerobic build + threshold development  
**Training Style:** 80/20 Polarized (80% Zone 1–2 Low Intensity / 20% Zone 5+ High Intensity)

---

## 2. Equipment & Environment

### Indoor Training Setup

| Component | Details |
|-----------|---------|
| Trainer/Bike | Elite Suito |
| Platform | auuki |
| Cooling | Fan |
| Sensors | HRM, power meter, cadence |
| Pedals | Shimano spd |

### Outdoor Setup

| Component | Details |
|-----------|---------|
| Bike | S-Works Crux - 54, Ritchey Outback |
| Power Meter | SRAM FORCE AXS Powermeter Single sided |
| Head Unit | Garmin Edge 530 |
| HRM | Polar H9 |

### Other Modalities

| Modality | Equipment | Purpose |
|----------|-----------|---------|
| Rowing Machine | DOMYOS WOODROWE | Aerobic |
| Running / Trail Running | Shoes, watch | Active recovery, aerobic |
| Strength | Dumbbells (Adjustable weight), weight bench | Core stability, Full body strength and conditioning |

### Environment

| Factor | Details |
| :--- | :--- |
| **Indoor** | Self-hosted home lab / training space. Dedicated indoor smart trainer setup. Controlled ventilation (fan setup), ambient indoor temp maintained ~18°C–21°C year-round. |
| **Outdoor** | **Location:** Affoltern am Albis / Knonauer Amt, Canton Zurich, Switzerland (~490m elevation).<br>**Terrain:** Rolling pre-alpine hills, steep local pitches (e.g., Albis Pass), gravel forestry tracks, and surrounding valleys.<br>**Climate/Temp Range:** Temperate Central European climate. Summer highs ~20°C–28°C (occasional heatwaves >30°C); Winter lows ~-2°C to 5°C with seasonal damp/fog (Bise winds). High summer humidity/rain showers, cool autumn/spring shoulder seasons. |
| **Calibration** |  |

---

## 3. Training Schedule & Framework

### Weekly Volume Target

**Baseline:** 8 hours/week (± 4 hours)  
**Peak phases:** Up to 15 hours (requires RI ≥ 0.8, HRV within 10%)  
**Intensity Distribution:** 80/20 Polarized (80% < LT1 / 20% > LT2)

### Normal Weekly Schedule

| Day | Primary Session | Duration | Secondary |
|-----|-----------------|----------|-----------|
| Sunday | [Workout type] | [Duration] | [Optional] |
| Monday | [Workout type] | [Duration] | [Optional] |
| Tuesday | [Workout type] | [Duration] | [Optional] |
| Wednesday | [Workout type] | [Duration] | [Optional] |
| Thursday | [Workout type] | [Duration] | [Optional] |
| Friday | [Workout type] | [Duration] | [Optional] |
| Saturday | [Workout type] | [Duration] | [Optional] |

### Session Details

| Session Type | Target Power/HR | Duration | Purpose |
|--------------|-----------------|----------|---------|
| VO₂Max | [W or % FTP] | [Duration] | [Purpose] |
| Endurance | [W or % FTP] | [Duration] | [Purpose] |
| Sweetspot | [W or % FTP] | [Duration] | [Purpose] |
| Long Ride | [W or % FTP] | [Duration] | [Purpose] |
| Recovery | [W or % FTP] | [Duration] | [Purpose] |

### Recovery Protocol

**Recovery Triggers (Auto-Deload):**
- HRV ↓ > 20% → [Response]
- RHR ↑ ≥ 5 bpm → [Response]
- Feel ≥ 4 → [Response]
- Two+ triggers → [Response]

**Feel Scale:**
| Score | Meaning |
|-------|---------|
| 1 | Excellent (fully recovered) |
| 2 | Good (normal fatigue) |
| 3 | Moderate (manageable tiredness) |
| 4 | Fatigued (reduced readiness, deload trigger) |
| 5 | Exhausted (complete rest required) |

### Performance Objectives

| Year | Phase | Focus | Primary KPI |
|------|-------|-------|-------------|
| [Year] | [Phase name] | [Focus area] | [Target metrics] |
| [Year] | [Phase name] | [Focus area] | [Target metrics] |
| [Year] | [Phase name] | [Focus area] | [Target metrics] |

---

## 4. Performance Metrics

### Current Power Zones

| Zone | % of FTP | Power (W) | Notes |
|------|----------|-----------|-------|
| Z1 | 0–70% | 1 - 168W | Active Recovery |
| Z2 | 71–83% | 169 - 199W | Endurance (Base) |
| Z3 | 84–91% | 200 - 218W | Tempo (Zone X) |
| Z4 | 92–100% | 219 - 240W | Threshold |
| Z5 | 101–102% | 241 - 244W | VO₂max (Zone Y) |
| Z6 | 103–110% | 245 - 264W | Anaerobic |
| Z7 | 111%+ | 265W+ | Neuromuscular |
| SS | 84–97% | 201 - 232W | Sweetspot |

**Current FTP:** 240 W (Indoor: 240 W, eFTP: 259 W)  
**Max HR:** 184 bpm  
**Threshold HR:** 166 bpm

### Current Fitness Markers

| Metric | Value | Notes |
|--------|-------|-------|
| FTP (Outdoor) | 240 W | |
| FTP (Indoor) | 240 W | Adjusted for indoor conditions |
| LT2 Power (MLSS) | 240 W | ≈100% of FTP |
| LT2 HR | 166 bpm | Threshold Heart Rate |
| LT1 (AeT) | ~199 W | HR ≈ 135–140 bpm (Top of Z2) |
| VO₂max Interval Power | 241 – 264 W | Zones Z5–Z6 |
| Sweetspot Target | 201 – 232 W | |
| Weekly Volume | 8–10 hours | ~500–715 TSS |

### Weight Tracking

**Protocol:** Daily morning weigh-in, recorded at ~79 kg.  
**Adjustment Control:** Weight adjustments only permitted during readiness-positive periods (DI ≥ 0.95, HR drift ≤ 3%, RI ≥ 0.8)

---
## 4. Performance Metrics

### Current Power Zones

| Zone | % of FTP | Power (W) | Notes |
|------|----------|-----------|-------|
| Z1 | 0–70% | 1 - 168W | Active Recovery |
| Z2 | 71–83% | 169 - 199W | Endurance (Base) |
| Z3 | 84–91% | 200 - 218W | Tempo (Zone X) |
| Z4 | 92–100% | 219 - 240W | Threshold |
| Z5 | 101–102% | 241 - 244W | VO₂max (Zone Y) |
| Z6 | 103–110% | 245 - 264W | Anaerobic |
| Z7 | 111%+ | 265W+ | Neuromuscular |
| SS | 84–97% | 201 - 232W | Sweetspot |

**Current FTP:** 240 W (Indoor: 240 W, eFTP: 259 W)  
**Max HR:** 184 bpm  
**Threshold HR:** 166 bpm

### Current Fitness Markers

| Metric | Value | Notes |
|--------|-------|-------|
| FTP (Outdoor) | 240 W | |
| FTP (Indoor) | 240 W | Adjusted for indoor conditions |
| LT2 Power (MLSS) | 240 W | ≈100% of FTP |
| LT2 HR | 166 bpm | Threshold Heart Rate |
| LT1 (AeT) | ~199 W | HR ≈ 135–140 bpm (Top of Z2) |
| VO₂max Interval Power | 241 – 264 W | Zones Z5–Z6 |
| Sweetspot Target | 201 – 232 W | |
| Weekly Volume | 8–10 hours | ~500–715 TSS |

### Weight Tracking

**Protocol:** Daily morning weigh-in, recorded at ~79 kg.  
**Adjustment Control:** Weight adjustments only permitted during readiness-positive periods (DI ≥ 0.95, HR drift ≤ 3%, RI ≥ 0.8)

---

## 5. Nutrition / Fueling

### Training Fuel Recipe

Standard High-Carb Mix: Maltodextrin + Fructose (1:0.8 ratio) + Electrolytes

**CHO per bottle:** 60–90 g  
**Target absorption:** 60–90 g CHO/h

### Recovery Drink Recipe

Protein + Fast-acting Carbs (e.g., 25g Whey Protein + 50g Maltodextrin/Banana)

### Fueling by Workout Type

| Workout Type | Duration | CHO Target | Setup |
|--------------|----------|------------|-------|
| Recovery / Z1–Z2 | < 1.5 h | 0–30 g/h | Water / Electrolytes |
| Endurance | 1.5–3 h | 45–60 g/h | 1 Bottle Carb Mix + Water |
| Long Endurance | 3–6 h | 60–90 g/h | 2 Bottles Carb Mix + Gels/Chews |
| Threshold / SS | 1–2 h | 60 g/h | 1 Bottle High-Carb Mix |
| VO₂ / High Intensity | 1–1.5 h | 60 g/h | 1 Bottle High-Carb Mix |
| Race / Event | 4–6 h | 80–90+ g/h | Carb Mix + Gels every 20–30 min |

### Hydration

**Target:** 500–750 ml/hour  
**Sodium:** ~500 mg/L base, + 200–300 mg/h additional for long/hot rides

---

## 6. Adaptation & Current Focus

### Current Adaptation Focus

- [x] Maintain aerobic base volume (8–10h weekly)
- [x] Manage tapering and recovery protocols around priority gravel/endurance events
- [ ] Optimize threshold power maintenance (FTP 240W → eFTP 259W conversion)
- [x] Incorporate structured polarized interval distributions (80/20)

### Next-Phase Options

Transition from event/taper phase into a post-event recovery week, followed by a dedicated base/re-build block focusing on progressive Sweetspot and VO2 Max intervals.

---

## 7. Outdoor Transition Plan (if applicable)

### Transition Timeline

| Month | Changes | Notes |
|-------|---------|-------|
| June | High-volume outdoor endurance & gravel rides | Focus on long outdoor endurance rides (e.g., 100km+ gravel) |
| July | Event Execution & Race Tapering | Primary event focus (e.g., Majestic Gravel 104km) |
| August | Structured Re-build | Balance outdoor long rides with targeted indoor interval sessions |

**General Rules:**
- Outdoor rides replace indoor 1:1
- HR < 85% of threshold = aerobic (HR < 141 bpm)
- Use HR to guide intensity early season

---

## 8. Long-Term Performance Roadmap

### Primary Objective

Build sustainable long-distance gravel and road endurance fitness while improving W/kg output.

### Progression Overview

| Year | Focus | FTP Target | W/kg Target | Key Metrics |
|------|-------|------------|-------------|-------------|
| 2026 | Base & Gravel Taper | 240–260 W | 3.0–3.3 W/kg | Current weight ~79 kg |
| 2027 | Threshold & W/kg Progression | 265–280 W | 3.4–3.6 W/kg | Target weight ~76–77 kg |

### Event-Specific Targets (Optional)

| Event/Segment | Year | Priority | Target Time | Target Power |
|---------------|------|----------|-------------|--------------|
| The Majestic Gravel (104 km) | 2026 | A | Completed | 208 W / Load 430 |

> **Race tagging for automated protocol activation:** Tag races in Intervals.icu as `RACE_A`, `RACE_B`, or `RACE_C` using the event category selector. The race-week protocol (Section 11A) activates automatically for A and B races within 7 days. C races are training races — no taper adjustments. For best results, also set expected duration (`moving_time`) in the event to enable event-type modifiers (carb loading, opener intensity, TSB targets).

## 9. Coach Notes

[Space for coach observations, athlete-specific considerations, or important reminders]

---

## 10. Operational & Data Integrity Log

### Training Timeline & Event Log

| Date | Event | Notes |
|------|-------|-------|
| [Date] | [Event] | [Details] |
| [Date] | [Event] | [Details] |

### Calibration & Data Log

| Date | Item | Action |
|------|------|--------|
| [Date] | [Equipment] | [Action taken] |
| [Date] | [Equipment] | [Action taken] |

---

## Data Mirror Configuration

### JSON Endpoint (for AI coaches)

**URL:** `https://raw.githubusercontent.com/[username]/[repo]/main/latest.json`

**Archive:** `https://github.com/[username]/[repo]/tree/main/archive`

**— OR (GitHub connector) —**

**Repo:** `[username]/[repo]` (connected via platform's GitHub integration — AI reads files directly, no URLs needed)

> **Tip:** If you commit `DOSSIER.md` to your data repo alongside `latest.json`, `history.json`, and `intervals.json`, connecting the repo gives the AI both your data and your profile in one connection. The only remaining piece is `SECTION_11.md`, which the AI can fetch from the public CrankAddict/section-11 repo or a second connector.

**— OR (local setup) —**

**Path:** `latest.json` (data directory root, alongside this dossier)

**History:** `history.json` (data directory root)

**Intervals:** `intervals.json` (data directory root — on-demand, for structured session analysis)

**Data Path (optional):** `[/path/to/training-data/]`
Only needed if the AI agent's working directory is different from where data files live (e.g., OpenClaw workspace is `~/clawd/` but data is in `~/training-data/`). Leave blank if they are the same directory.

For local setups where sync.py runs on the same machine as the AI agent, files are read directly from the filesystem — no URLs needed. See `examples/json-local-sync/SETUP.md` for the complete local pipeline.

This endpoint provides synchronized Intervals.icu metrics for deterministic AI parsing. See **Section 11** for the full AI Coach Guidance Protocol.

---

## Protocol Reference

This dossier follows the **Section 11 A/B AI Coach Guidance Protocol** for AI integration.

**Protocol Location:** [Link to your Section 11 document or repo]

---

## Changelog

### v1.0 ([Date])
- Initial dossier creation
