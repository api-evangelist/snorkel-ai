# Snorkel AI (snorkel-ai)

Snorkel AI is a data-development / AI data platform built on the open-source Snorkel weak-supervision library. The enterprise Snorkel Flow platform supports programmatic labeling, data curation, model training, and evaluation, and is driven programmatically through a Python SDK that targets a per-instance REST API rather than a single public hosted endpoint. Snorkel also delivers Expert Data-as-a-Service for frontier-model training and evaluation data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/snorkel-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/snorkel-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Data Development
- Programmatic Labeling
- Weak Supervision
- Evaluation
- SDK

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Snorkel Flow SDK / Platform

The Snorkel Flow Python SDK (snorkelflow) drives the platform programmatically, connecting to a customer's Snorkel Flow instance via SnorkelFlowContext and an API key. The snorkelflow.client module wraps the instance's REST API; there is no single public hosted base URL - each deployment exposes its own per-instance endpoint (https://<your-snorkel-hostname>). Covers datasets, applications, operators, labeling functions, model training, and evaluation.

- **Human URL:** [https://docs.snorkel.ai/docs/25.3/user-guide/sdk/quick_start](https://docs.snorkel.ai/docs/25.3/user-guide/sdk/quick_start)

#### Tags

- SDK
- Platform
- Data Development

#### Properties

- [Documentation](https://docs.snorkel.ai/docs/25.3/user-guide/sdk/)
- [API Reference](https://docs.snorkel.ai/docs/0.95/sdk/)
- [OpenAPI](openapi/snorkel-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snorkel-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snorkel-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Programmatic Labeling

SDK surface (snorkelflow.studio, snorkelflow.lfs, snorkelflow.operators, snorkelflow.templates) for authoring code-based and template-based labeling functions, transformation and slicing functions, and combining them with a label model to programmatically generate training data via weak supervision.

- **Human URL:** [https://docs.snorkel.ai/docs/0.95/sdk/](https://docs.snorkel.ai/docs/0.95/sdk/)

#### Tags

- Programmatic Labeling
- Labeling Functions
- Weak Supervision

#### Properties

- [Documentation](https://docs.snorkel.ai/docs/0.93/user-guide/overview/key-concepts/)
- [API Reference](https://docs.snorkel.ai/docs/0.95/sdk/)
- [OpenAPI](openapi/snorkel-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snorkel-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snorkel-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evaluation

Platform and SDK capabilities for assessing model performance across data splits, running error and slice analysis, and building expert-curated benchmarks. Largely delivered in-platform and through the SDK against a customer's Snorkel Flow instance rather than a public REST endpoint.

- **Human URL:** [https://snorkel.ai/](https://snorkel.ai/)

#### Tags

- Evaluation
- Benchmarks
- Error Analysis

#### Properties

- [Documentation](https://docs.snorkel.ai/docs/25.3/user-guide/sdk/)
- [API Reference](https://docs.snorkel.ai/docs/0.95/sdk/)
- [OpenAPI](openapi/snorkel-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snorkel-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snorkel-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Open-Source Snorkel Library

The free, open-source snorkel Python library (Apache-2.0) for programmatically building and managing training data with weak supervision - labeling functions, the LabelModel, transformation functions, and slicing functions. Imported as a local Python dependency (pip install snorkel); not a hosted network API.

- **Human URL:** [https://github.com/snorkel-team/snorkel](https://github.com/snorkel-team/snorkel)

#### Tags

- Open Source
- Python Library
- Weak Supervision

#### Properties

- [Documentation](https://www.snorkel.org/)
- [API Reference](https://snorkel.readthedocs.io/)
- [GitHub](https://github.com/snorkel-team/snorkel)
- [Postman Collection](collections/snorkel-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snorkel-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/snorkel-team)
- [LinkedIn](https://www.linkedin.com/company/snorkel-ai)
- [Website](https://snorkel.ai)
- [Documentation](https://docs.snorkel.ai)
- [Plans](plans/snorkel-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/snorkel-ai-rate-limits.yml)
- [Fin Ops](finops/snorkel-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
