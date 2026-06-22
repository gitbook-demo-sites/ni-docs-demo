---
description: How the NI catalog maps into GitBook spaces and sections.
icon: sitemap
---

# Catalog model

The NI documentation center has to support several reader intents at once: a technician with hardware on a bench, a LabVIEW user building a measurement workflow, an enterprise admin operating SystemLink, and a developer looking for an API contract.

```mermaid
flowchart LR
    Home[Docs center] --> Product[Product manuals]
    Home --> API[Developer APIs]
    Home --> Services[Services and learning]
    Product --> Software[Software manuals]
    Product --> Hardware[Hardware setup]
    Product --> Systems[System architectures]
    API --> SystemLink[SystemLink API]
    API --> SDKs[SDKs and clients]
    Services --> Calibration[Calibration and repair]
    Services --> Training[Training paths]
```

{% hint style="success" icon="sparkles" %}
The demo keeps NI's current product-led catalog, but the navigation is grouped by reader job instead of by one flat index.
{% endhint %}

## Space strategy

| Space | Purpose | Example reader |
| --- | --- | --- |
| Product Manuals | Install, configure, and operate NI products | Test engineer or lab technician |
| Developer APIs | Integrate with SystemLink and automate workflows | Software engineer |
| Services and Learning | Get help, calibrate hardware, and build team capability | Operations owner or lab manager |
| Docs Center | Global homepage, search, translations, and migration story | Any visitor |

