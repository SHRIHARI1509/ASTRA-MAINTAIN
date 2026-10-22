# ASTRA-MAINTAIN

Predictive maintenance and asset health monitoring for ASTRA.

## Repository Structure

```
ASTRA-MAINTAIN/
└── DATASETS/
    ├── 7 PARAMETERS/
    │   ├── SOURCES.csv
    │   └── telemetry_7_sensors.csv
    └── EXTRAS/
        ├── 6.+Turbofan+Engine+Degradation+Simulation+Data+Set.zip
        ├── simulation_ground_truth.csv
        └── telemetry_14_parameters.csv
```

## Datasets Overview

### `DATASETS/7 PARAMETERS/`
Core telemetry dataset focusing on 7 operational sensor parameters:
- `telemetry_7_sensors.csv`: Sensor telemetry across operational cycles (train, validation, test splits).
- `SOURCES.csv`: Metadata, platform identity, cycle counts, subsystem mappings, and source origins for tracked assets.

### `DATASETS/EXTRAS/`
Supplementary datasets and ground-truth simulation benchmarks:
- `telemetry_14_parameters.csv`: Extended 14-parameter sensor telemetry.
- `simulation_ground_truth.csv`: Ground-truth degradation and Remaining Useful Life (RUL) simulation benchmarks.
- `6.+Turbofan+Engine+Degradation+Simulation+Data+Set.zip`: Turbofan engine degradation simulation dataset (NASA C-MAPSS benchmark).
