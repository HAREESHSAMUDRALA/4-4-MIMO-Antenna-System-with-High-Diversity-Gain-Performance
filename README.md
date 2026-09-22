# Design of a Compact 4x4 MIMO Antenna System with High-Diversity Gain Performance

**Mini Project II (EC399)** — B.Tech, Electronics and Communication Engineering
National Institute of Technology, Andhra Pradesh — April 2024

**Guide:** Dr. N. Praveena | **Project In-charge:** Mr. Sanath Kumar Tulasi | **HoD:** Dr. S. Yuvaraj

## Abstract

A compact, four-element, dual-band MIMO antenna system built on an FR-4 substrate with a plus-sign-shaped ground structure, designed for high isolation and low channel capacity loss. The design covers two frequency bands: **1550–2650 MHz** and **3350–3650 MHz**, achieving isolation greater than **10 dB** and **19 dB** respectively.

## Objective

Design a compact 4-element dual-band MIMO antenna optimized for the widely used 2.4 GHz and 5 GHz bands, evaluated using bit error rate (BER), channel capacity loss, and signal-to-noise ratio (SNR) to ensure reliable communication under noise and interference.

## Methodology

- Substrate: **FR-4** (permittivity 4.3)
- Radiating elements & feed: **PEC** material with chamfered patch/feed for refined performance
- Ground plane: plus-sign-shaped structure with strips/pads to enhance radiation
- Feed structure: inner + outer components, surrounded by **PTFE** for low dielectric loss
- Design refined through slot introduction (Slot 1, Slot 2) and a parametric sweep over **substrate height** and **patch length**
- Simulated and validated in **CST Studio Suite** (electromagnetic simulator)

## Key Results

| Parameter | Value |
|---|---|
| Overall dimensions | 58 × 60 × 1.6 mm³ |
| Lower band | 1550–2650 MHz (2G/3G/4G/5G) |
| Upper band | 3350–3650 MHz (5G, ~3.5 GHz) |
| Isolation (lower / upper band) | > 10 dB / > 19 dB |
| Channel Capacity Loss (CCL) | < 0.4 bits/s/Hz (both bands) |
| Envelope Correlation Coefficient (ECC) | < 0.08 (lower band), < 0.02 (upper band) |
| Optimized patch length | 3.8 cm |
| Optimized substrate height | 0.36 cm |

The design meets diversity and isolation requirements for both 4G and 5G wireless communication systems.

## Future Scope

- Extend bandwidth for multi-band operation (5G, Wi-Fi 6E, and beyond)
- Scale to massive MIMO configurations with more antenna elements
- Integrate mmWave technology for higher throughput
- Field trials in real-world deployment scenarios

## References

1. Deng, C., Liu, D., & Lv, X. (2019). *Tightly Arranged Four-Element MIMO Antennas for 5G Mobile Terminals.* IEEE TAP, 67(10), 6353–6361.
2. Chen, S. C., Chiang, C. W., & Hsu, C. I. G. (2019). *Compact four-element MIMO antenna system for 5G laptops.* IEEE Access, 7, 186056–186064.
3. Abdulkawi, W. M. et al. (2021). *Design of a compact dual-band MIMO antenna system with high-diversity gain performance.* Micromachines, 12(4).
