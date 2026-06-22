---
description: Programmatic access to test results and measurement data.
icon: vial-circle-check
---

# Test results

Test result APIs support analytics, dashboards, traceability, and operational reporting across labs and production systems.

## Retrieval flow

```mermaid
sequenceDiagram
    participant App as Internal app
    participant API as SystemLink API
    participant Data as Test data store
    App->>API: Query results by product, station, or time
    API->>Data: Fetch matching measurements
    Data-->>API: Results and metadata
    API-->>App: Structured response
```

## Good docs examples

{% tabs %}
{% tab title="Python" %}
```python
from nisystemlink.clients import core

# Authenticate with the configured SystemLink environment.
client = core.HttpClient()
```
{% endtab %}

{% tab title="HTTP" %}
```bash
curl -H "Authorization: Bearer $SYSTEMLINK_TOKEN" \
  "$SYSTEMLINK_URL/api/test-results"
```
{% endtab %}
{% endtabs %}

