# JMA Wireless — 5G Antenna Mechanical Design Projects

Mechanical design and structural/CFD engineering work on JMA Wireless NWAV™ panel antenna
product lines, covering base station antenna structures used in 4G/5G network deployments.

As a Mechanical Engineer II in R&D/NPD at JMA Wireless, my work on these product lines spans
structural FEA (vibration/wind load correlation per IEC 60068-2), CFD-driven radome drag
reduction, topology optimization for mass reduction, GD&T/DFMA, and full NPI/ECN cycle
management from concept through production release.

> Datasheets included here are publicly available JMA Wireless product literature, added for
> reference context. No proprietary or confidential design data is included in this repository.

## Projects

| Product | Type | Frequency Range | Notes |
|---|---|---|---|
| [DX10FRO260-20/-26](./DX10FRO260-20-26) | 2F Panel Antenna, 10-port | 698–3980 MHz | Small cell, pole/wall mount |
| [MX08FIT665-02E](./MX08FIT665-02E) | X-Pol 8-Port Antenna | 698–4200 MHz | 6 ft macro panel, Smart Bias-Ts |
| [MX06FRO660-02E](./MX06FRO660-02E) | X-Pol Hex-Port, Fast Roll-Off | 698–2200 MHz | FRO pattern for SINR improvement |
| [MX06FHG665-HG](./MX06FHG665-HG) | X-Pol Hex-Port, High Gain | 698–2180 MHz | High-gain low/mid-band variant |

## My Contribution Areas
*(edit per product — suggested structure below)*
- Structural FEA: wind/vibration load validation, mounting bracket and radome structural sign-off
- CFD: drag coefficient reduction across radome profile iterations (Ansys Fluent)
- Topology optimization: mass reduction while meeting wind survival ratings (up to 150 mph / 241 km/h)
- GD&T & DFMA: tolerance stack-up for RF connector alignment, manufacturability reviews
- NPI/ECN: design releases, engineering change management through production ramp

## Repo Structure
Each product folder contains:
- `README.md` — product overview, mechanical specs, and my specific design contribution
- `datasheet/` — official JMA product datasheet (PDF)
