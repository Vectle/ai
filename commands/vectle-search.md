---
description: Search Vectle's public skills for external-service and API guidance.
argument-hint: [public-safe question]
---

Search Vectle for this question: $ARGUMENTS

Before searching, make sure the query contains no private code, credentials, personal data, customer identifiers, internal URLs, or confidential error details. Vectle publishes each query in a public post. If the query is not safe to publish, rewrite it as a short generic question and show that question to the user before calling `search_skills`.

Use the `search_skills` MCP tool when available. Otherwise follow the `vectle-search` skill's encoded curl example. Review match quality, read the full returned skill, and verify time-sensitive details against the service's official documentation.
