---
description: APIs, clients, and automation guidance for NI software-connected test systems.
icon: code
layout:
  width: wide
  tableOfContents:
    visible: true
  outline:
    visible: true
---

# Developer APIs

Developer APIs covers SystemLink automation, client libraries, API conventions, and agent-readable documentation.

{% columns %}
{% column width="55%" %}
Use this space when you need to integrate NI systems with internal tools, automate asset workflows, pull test results, or build web applications on top of SystemLink services.
{% endcolumn %}

{% column width="45%" %}
{% hint style="success" icon="code" %}
SystemLink has public OpenAPI documents and Python client documentation. In a production GitBook migration, these references should be generated directly from source specs.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

## Start here

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody>
<tr><td><h3><i class="fa-key" style="color:$primary;">:key:</i></h3></td><td><strong>Authentication</strong></td><td>API keys, service users, and environment-specific access.</td><td><a href="getting-started/authentication-patterns.md">auth</a></td></tr>
<tr><td><h3><i class="fa-boxes-stacked" style="color:$primary;">:boxes-stacked:</i></h3></td><td><strong>Asset management</strong></td><td>Track assets, calibration state, location, and system presence.</td><td><a href="systemlink-api/asset-management.md">assets</a></td></tr>
<tr><td><h3><i class="fa-vial-circle-check" style="color:$primary;">:vial-circle-check:</i></h3></td><td><strong>Test results</strong></td><td>Retrieve and analyze test data from managed systems.</td><td><a href="systemlink-api/test-results.md">results</a></td></tr>
<tr><td><h3><i class="fa-robot" style="color:$primary;">:robot:</i></h3></td><td><strong>Agent access</strong></td><td>Make docs usable by AI coding agents, copilots, and support assistants.</td><td><a href="agent-access/agent-ready-docs.md">agents</a></td></tr>
</tbody></table>

