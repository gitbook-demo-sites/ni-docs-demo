---
description: PXI system setup and validation guidance.
icon: server
---

# PXI test systems

PXI systems are used for high-performance automated test, validation, and measurement. A docs experience for PXI should connect chassis setup, instrument manuals, software drivers, and maintenance guidance.

## System layers

```mermaid
flowchart TB
    App[Test application] --> Driver[Drivers and APIs]
    Driver --> Controller[PXI controller]
    Controller --> Chassis[PXI chassis]
    Chassis --> Modules[Instrument modules]
    Modules --> DUT[Device under test]
```

## Validation checklist

| Check | Why |
| --- | --- |
| Chassis and controller compatibility | Avoid unsupported module or bandwidth configurations |
| Driver version | Keep software validated with deployed test sequences |
| Calibration status | Ensure measurement accuracy and audit readiness |
| Thermal and power budget | Prevent intermittent behavior during long runs |

