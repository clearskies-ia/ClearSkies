# ClearSkies

**ClearSkies** is a youth-led air quality initiative building low-cost, continuous environmental sensing tools and applied research projects. This repository showcases the work of interns from California, Texas, New York, and Iowa, spanning two tracks: **Research** and **Engineering**.

What started as a state-wide initiative to monitor radon has grown into a nationwide effort to use innovative technologies to monitor all kinds of air quality metrics and build impactful, real-world projects.

`microcontrollers` `machine-learning` `air-quality` `iot` `environmental-sensing` `time-series-forecasting` `computer-vision` `cad` `esp32` `radon-monitoring`

---

## Repository Structure

```
clearskies/
├── README.md
├── research/
└── engineering/
```

---

## Research Track

The research track covers a range of applied machine-learning projects aimed at closing gaps in air-quality data, from hyper-local pollution mapping to indoor air optimization. Scope and direction vary by intern and are still evolving, but general areas of exploration include:

- Spatiotemporal deep learning for high-resolution pollution mapping (e.g. ConvLSTM, graph-based models)
- Sensor calibration and drift correction for low-cost sensor networks
- Computer vision approaches to estimating air quality from imagery
- Source attribution and inverse modeling for pollution events
- Time-series forecasting for multi-pollutant health risk prediction
- Wildfire smoke and plume trajectory modeling
- Traffic-to-pollution simulation using graph and temporal networks
- Reinforcement learning for indoor air quality and HVAC optimization

These projects are not fixed. The `research/` folder is organized to accommodate new experiments and approaches as they develop, with each project kept self-contained (data, code, notebooks, results) for clarity and reproducibility.

## Engineering Track

The engineering track is confirmed to focus on the **redesign of a protective case for a radon sensor**, with version-controlled iterations rather than a single static design. The `engineering/` folder is structured to support:

- Ongoing CAD revisions for the radon sensor case, with a clear history of changes across versions
- Export-ready files for fabrication (e.g. printing)
- Future integration of microcontroller and firmware code for the radon sensor, kept as a separate but adjacent component

As the engineering track expands, this structure is designed to scale cleanly from a single hardware redesign into a fuller hardware and firmware system.

---

## About

This repository is maintained collaboratively by ClearSkies research interns as part of an ongoing effort to build accessible, open air quality monitoring tools.
