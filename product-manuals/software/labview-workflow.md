---
description: A representative LabVIEW workflow for test, measurement, and control.
icon: flask
---

# LabVIEW development workflow

LabVIEW is systems engineering software for applications that require test, measurement, and control with rapid access to hardware and data insights.

## Workflow

```mermaid
flowchart LR
    Install[Install LabVIEW and drivers] --> Create[Create project]
    Create --> Connect[Connect NI hardware]
    Connect --> Acquire[Acquire data]
    Acquire --> Analyze[Analyze and visualize]
    Analyze --> Automate[Automate test sequence]
    Automate --> Publish[Publish results]
```

## Quick checklist

{% stepper %}
{% step %}
Install LabVIEW and the required device drivers, such as NI-DAQmx for data acquisition devices.
{% endstep %}

{% step %}
Open or create a project and add the devices, channels, and dependencies for the test system.
{% endstep %}

{% step %}
Verify hardware communication in MAX before building the full measurement application.
{% endstep %}

{% step %}
Capture, analyze, and save measurement results with a documented version of the software stack.
{% endstep %}
{% endstepper %}

