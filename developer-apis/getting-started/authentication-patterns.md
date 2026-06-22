---
description: Authentication patterns for SystemLink integrations and web applications.
icon: key
---

# Authentication patterns

SystemLink integrations may use API keys, user credentials, or service identities depending on deployment model and security policy.

{% tabs %}
{% tab title="Server integration" %}
Use a service-owned credential stored in a secure secret manager. Rotate credentials on a schedule and scope access to required APIs.
{% endtab %}

{% tab title="Web application" %}
Use an API key or delegated identity appropriate for the SystemLink environment and user permissions.
{% endtab %}

{% tab title="Local automation" %}
Use environment-specific credentials and avoid hard-coding secrets in scripts, notebooks, or test assets.
{% endtab %}
{% endtabs %}

