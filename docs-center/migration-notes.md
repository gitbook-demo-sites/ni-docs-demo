---
description: Practical migration notes for moving a large product documentation portal into GitBook.
icon: route
---

# Migration notes

The current NI Product Documentation Center appears to be a large rendered portal with manuals, product collections, PDF downloads, and support links. A realistic migration would not hand-polish every page in the first pass.

## Recommended migration path

{% stepper %}
{% step %}
Mirror the live information architecture: software, hardware, systems, services, release notes, and support resources.
{% endstep %}

{% step %}
Bulk import representative manuals and product pages, then rebuild the anchor pages with GitBook blocks.
{% endstep %}

{% step %}
Register API specs for SystemLink and other developer surfaces so reference pages are generated from source-of-truth contracts.
{% endstep %}

{% step %}
Add translations, search analytics, broken-link checks, and AI assistant prompts after the first representative slice is live.
{% endstep %}
{% endstepper %}

## First-pass anchor pages

| Anchor | Why it matters |
| --- | --- |
| Docs center homepage | Shows global search, product routing, and translations |
| LabVIEW workflow | Represents high-volume software documentation |
| CompactDAQ setup | Represents hardware setup and troubleshooting |
| SystemLink API | Represents developer and automation workflows |
| Service requests | Represents support and account-sensitive content |

