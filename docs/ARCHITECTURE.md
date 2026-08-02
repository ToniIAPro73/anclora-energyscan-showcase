# Architecture

Anclora EnergyScan separates presentation, workflow orchestration, assessment
rules, documents, commercial flows, persistence and integrations.

## Conceptual layers

- Presentation: landing, wizard, results and dashboards.
- Application: orchestration, permissions and workflow state.
- Domain: property characteristics, categories, confidence and scenarios.
- Documents: uploads, OCR, vision and Premium reports.
- Commercial: checkout, providers, partners, leads and credits.
- Persistence: users, assessments, payments and audit information.
- Integrations: Catastro, Stripe, storage, email, maps and analytics.

## Principles

- Explainable outcomes.
- Explicit confidence and missing-data signals.
- Idempotent payment processing.
- Least-privilege access.
- Controlled external-service costs.
- Clear separation between orientation and official certification.
