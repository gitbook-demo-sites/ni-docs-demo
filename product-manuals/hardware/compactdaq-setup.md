---
description: Setup path for CompactDAQ and data acquisition hardware.
icon: wave-square
---

# CompactDAQ setup

CompactDAQ systems combine a chassis, C Series modules, sensors, and NI software to acquire and analyze measurement data.

## First signal workflow

{% stepper %}
{% step %}
Identify the chassis, module, connector block, and sensor type.
{% endstep %}

{% step %}
Install the required driver, then verify the device in MAX.
{% endstep %}

{% step %}
Create or select the physical channel and confirm expected units, range, and terminal configuration.
{% endstep %}

{% step %}
Run a test panel or a minimal LabVIEW VI to acquire the first signal.
{% endstep %}

{% step %}
Save the project configuration with product version and calibration details.
{% endstep %}
{% endstepper %}

{% hint style="warning" icon="bolt" %}
Always follow the module specifications before connecting live voltage, current, strain, pressure, or force sensors.
{% endhint %}

