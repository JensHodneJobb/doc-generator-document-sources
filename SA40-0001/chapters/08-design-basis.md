---
id: design-basis
title: "Design Basis"
chapter: 8
categories: [O_Basic, O_DnvDrill, O_DnvDrillN, O_AbsCds, O_NorFixed]
tags: [all]
---

# Design Basis

Design criteria given in this specification are basis for pricing, schedule and weight estimates, unless other criteria are expressly specified in the order by customer. Change of criteria after contract shall be processed as variation order according to applicable terms and conditions.

## Lifetime and Operational Conditions
- The equipment is designed and built to operate in marine offshore conditions
- Primary structural parts of the equipment are designed for a fatigue life of 20 years operation in typical drilling program cycles. Normal wear and tear shall be expected.
- Recommended services and maintenance programs must be followed
- Design basis for drilling risers is established case by case, beyond this specification.

## Temperature

The equipment is designed to operate at ambient temperatures given in {{tbl:ambient}} below, using lubricants and hydraulic fluids that suit the local seasonal climate, as advised by HMH.

Equipment in contact with drill fluids or well fluids is designed for fluid temperatures as provided.

**{{table:ambient | Ambient and design temperature for drilling equipment}}**


| Equipment | Ambient temperature (°C) | Drill or well fluids  equipment design temperature (°C) |
|---|---|---|
| Standard outdoor | From minus 20 to plus 45 | NA |
| Installed indoors *) | From 0 to plus 45 | NA |
| Choke/kill, cement and standpipe manifold | From minus 29 to plus 45 | From minus 29 to plus 121 |
| HPHT (high pressure high temperature) | From minus 29 to plus 45 | Minus 29 to plus 177 Optional for choke and kill |
| Mud reconditioning equipment | Indoor or outdoor as above | Maximum 70 |
| Drilling risers |  | Minus 29 to plus 82 |


*) Does not apply to components located inside controlled environment

## Wind Loads

If no wind information is specified in the contract, the wind speeds shown in {{tbl:wind}} are used as a basis.

**{{table:wind | Wind speed}}**


| Condition | Case | U(10m,3s) = wind speed at 10 m above sea level, 3 sec gust | U(10, 3600s) = wind speed at 10 m above sea level, 1 hour mean |
|---|---|---|---|
| All | Operation | 33 m/s | 26 m/s |
| All | Riser, BOP handling | 21 m/s (typical ⅔ of the operation wind force) | 17 m/s (typical ⅔ of the operation wind force) |
| All | Survival, 100 years | 45 m/s* | 36 m/s* |
| All | Damage, 27 degrees | 0 m/s (included in the damage heel) | 0 m/s (included in the damage heel) |


* The survival wind speed is based on recommendations in NORSOK N-003 for the Norwegian continental shelf.

The wind profiles and gust are following the formulas given in DNV-RP-C205.The average gust period used for designing the equipment is 3 seconds.

## Rig Motion Loads

If the rig motion accelerations are not given, the accelerations given in {{tbl:rig-semi}} and {{tbl:rig-drill}} are used. All values are given as single amplitude and as a fraction of gravity (g = 9.81 m/s2).

**{{table:rig-semi | Rig motions for semi-submersible}}**

| Motion condition* | Case | Horizontal acceleration | Horizontal acceleration | Heave |
|---|---|---|---|---|
| Motion condition* | Case | At Drill floor | Increases upwards | Heave |
| Normal | Operation | 0.10 g | 0.0021 g/m | 0.07 g |
|  | Riser and BOP handling | 0.07 g | 0.0014 g/m | 0.05 g |
|  | Survival, 100 years | 0.15 g | 0.0028 g/m | 0.15 g |
| High | Operation | 0.15 g | 0.0022 g/m | 0.10 g |
|  | Riser and BOP handling | 0.10 g | 0.00147 g/m | 0.07 g |
|  | Survival, 100 years | 0.25 g | 0.0051 g/m | 0.20 g |
| Damage | Accidental heel, 27 degrees | 0.45 g | NA | 0.89 g |


**{{table:rig-drill | Rig motions for drill-ship}}**

| Case | Horizontal acceleration | Horizontal acceleration | Heave |
|---|---|---|---|
| Case | At Drill floor | Increases upwards | Heave |
| Operation | 0.15 g | 0.0038 g/m | 0.15 g |
| Riser and BOP handling | 0.10 g | 0.00253 g/m | 0.10 g |
| Survival, 100 years | 0.30 g | 0.0046 g/m | 0.20 g |
| Accidental heel, 27 degrees | 0.45 g | NA | 0.89 g |


Accelerations due to wave action on fixed installations are not considered.

## Snow and Ice

This shall be considered for cranes working under exceptional conditions, and equipment which is particularly sensitive to such effects. Heat tracing devices are not included, but may be supplied as an option.

## Earthquake
- Equipment for installations on the seabed may be affected by accelerations due to earthquake.

As this type of loads can vary considerably, the seismic spectra for each specific area shall be specified in the order by the customer. HMH will consider the effect upon the equipment.
- Necessary reinforcement of the equipment due to earthquake shall be priced separately.

## Accidental Loads

Accidental heel of floating rig or vessel in damaged condition and dropped object are included in the design of the actual equipment.

Explosion loads are not likely to affect dimensioning of equipment, and is normally not accounted for in the design, except for derrick cladding, cabins and cabinets.  It will then be part of the plant design, outside the scope of this specification.
