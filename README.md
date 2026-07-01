# pyTDR

The repository hosts the source code and data used within the framework of "Spatiotemporal dynamics of capillary rise in shallow groundwater table areas revealed by spatial TDR" (https://doi.org/10.1016/j.jhydrol.2026.135957) research paper:
```
Chrysanthopoulos, E., Perdikaki, M., Nondas Floros, E., Kallioras, A., Spatiotemporal
dynamics of capillary rise in shallow groundwater table areas revealed by spatial TDR, Journal of Hydrology
(2026), doi: https://doi.org/10.1016/j.jhydrol.2026.135957
```
Documentation on the source code (InverseTDR/Model.py – InverseTDR/ModelPlotter.py) is explicitly provided within the Text S7 of Supplementary Material.

### Repository Structure
```text
├── Field_Data
│   ├── Groundwater
│   │   └── groundwater.csv
│   ├── Point_sensors
│   │   ├── soilmoist10cm.csv
│   │   └── soilmoist50cm.csv
│   └── Waveforms
│       ├── SP1_combined.csv
│       ├── SP2_combined.csv
│       ├── SP3_combined.csv
│       ├── SP4_combined.csv
│       └── SP5_combined.csv
├── InverseTDR
│   ├── Examples
│   │   ├── Data
│   │   │   └── dry_sand.csv
│   │   └── dry_sand.ipynb
│   ├── Model.py
│   └── ModelPlotter.py
├── LICENSE
└── requirements.txt
```
### UML Diagram of Python classes
<img width="468" height="325" alt="εικόνα" src="https://github.com/user-attachments/assets/8aaa5450-9907-4363-9f2b-f31acc503dd4" />

### Python Package versions

For a complete list, refer to the [requirements.txt](requirements.txt) file.

### Citing the code

Efthymios Chrysanthopoulos, Kallioras, A., & Floros, E. (Nondas) . (2026). efthymios19/pyTDR: pyTDR (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.20787058
