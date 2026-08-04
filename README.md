# Snorkel AI (snorkel-ai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
