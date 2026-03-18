# Thermodynamic Preference of Fe2+ for a C-Terminal Coordination Site in Human Frataxin

This repository contains multi-scale simulation datasets for the investigation of Fe²⁺ coordination to human frataxin (PDB: 1EKG). 

### Computational Methodology
Simulations were conducted using an accelerated sampling protocol on high-performance Blackwell-architecture GPU resources (NVIDIA RTX 5090 equivalent cluster). This high-throughput environment achieved a production rate of ~1890 ns/day, enabling an aggregate sampling time of 3.4 µs.

### Key Findings
- Identification of an uncharacterized C-terminal coordination site (Pocket 2).
- Thermodynamic preference over the acidic ridge (ΔΔG = -16.85 ± 9.5 kJ/mol).
- Transfer Entropy analysis validates causality flow from the hydrophobic core to the iron-binding sites.

### Data Audit
Technical logs (`md_1_5us_sampling.log` and `nmr_correlation_audit.log`) provide hardware-level verification of simulation performance and experimental cross-validation.
