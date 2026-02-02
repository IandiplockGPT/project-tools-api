# Mixers Australia — Risk Register

> Risk register for automation + welding plant development.
> Ratings are preliminary and will be refined during feasibility/FEED.

### Rating Guide (simple)
- **Likelihood (L):** 1 Low / 2 Medium / 3 High
- **Consequence (C):** 1 Low / 2 Medium / 3 High
- **Score:** L x C

| Ref | Risk | Cause | Impact | L | C | Score | Mitigation / Controls | Owner | Status |
|-----|------|-------|--------|---|---|-------|------------------------|-------|--------|
| R-001 | Bowl dimensions not available in time | Design delayed until mid-Sept | Layout/fixture design blocked; schedule slip | 3 | 3 | 9 | Stage-gate: lock dimensional envelope early; request interim envelope + assumptions | Mixers Australia / Mexx | Open |
| R-002 | Throughput target not achievable with single cell | 5 bowls/day implies low takt time | Underperformance, bottlenecks, missed production targets | 2 | 3 | 6 | Model takt time; plan for parallel stations or dual fixtures; design for scalability | Mexx | Open |
| R-003 | Weld quality variability | material mix (SS400/Rheemalloy/Hardox), thickness variation | Rework, defects, delays | 2 | 3 | 6 | Develop WPS per material; trial weld coupons; validate parameters early | Mexx | Open |
| R-004 | Distortion during welding | heat input on heavy sections | Poor fit-up at final assembly; scrap/rework | 2 | 3 | 6 | Control heat input, sequence planning, fixturing, preheat where needed | Mexx | Open |
| R-005 | Fit-up / alignment issues in final assembly | section tolerances, ovality, cone alignment | Poor circumferential weld quality; slow cycle time | 2 | 3 | 6 | Design robust alignment fixtures; add measurement/laser alignment; define tolerance requirements | Mexx | Open |
| R-006 | Robot reach / torch access limitations | complex cone geometry + internal helix | Incomplete weld coverage; manual touch-up | 2 | 2 | 4 | Early reach study; offline programming; fixture orientation optimisation | Mexx | Open |
| R-007 | Helix insertion automation complexity | helix stiffness, handling, interference | Slower cycle time; manual handling needed | 2 | 2 | 4 | Prototype gripper; validate insertion method; consider semi-automated first stage | Mexx | Open |
| R-008 | Material handling bottleneck | cranes / trolleys / conveyors not sized | delays between cells | 2 | 2 | 4 | Material flow design; buffer zones; define WIP staging; crane coverage study | Mexx | Open |
| R-009 | Safety risk in welding cells | robots + heavy rotating parts | injury risk; compliance failure | 2 | 3 | 6 | Risk assessment; guarding; interlocks; E-stops; safety PLC; zoning | Mexx | Open |
| R-010 | Fume extraction / ventilation inadequate | MIG welding duty cycle high | HSE non-compliance; worker exposure | 2 | 3 | 6 | Specify extraction early; confirm site airflow; integrate with cell design | Mixers Australia / Mexx | Open |
| R-011 | Long-lead equipment delays | robot, track, welder, drives | schedule delay | 2 | 3 | 6 | Identify long lead items in FEED; early procurement plan | Mexx | Open |
| R-012 | NDA / confidentiality not executed early | commercial sensitivity | risk of IP exposure / client friction | 2 | 2 | 4 | Confirm NDA status; execute before detailed exchange | Mexx Admin | Open |
| R-013 | Site power and services insufficient | welding power demand | added cost; redesign | 2 | 2 | 4 | Early site survey; confirm supply; include allowances | Mixers Australia | Open |
| R-014 | Scope creep across phases | unclear boundaries | cost blowout; delays | 2 | 3 | 6 | Lock scope per phase; stage-gate approvals; change control | Mexx | Open |
| R-015 | Commissioning complexity | multi-cell integration | extended ramp-up | 2 | 2 | 4 | Commissioning plan; staged commissioning per cell; FAT/SAT | Mexx | Open |

