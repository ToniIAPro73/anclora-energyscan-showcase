<div align="center">

<img
  src="./assets/brand/anclora-energy-scan.webp"
  alt="Anclora EnergyScan"
  width="132"
/>

# Anclora EnergyScan

### Residential energy pre-assessment with explainable results

A professional case study covering guided property intake, traceable scoring,
improvement scenarios, Premium reports and product-oriented full-stack
architecture.

<br />

![Case study](https://img.shields.io/badge/type-case%20study-00DC82)
![Energy](https://img.shields.io/badge/vertical-residential%20energy-00DC82)
![Architecture](https://img.shields.io/badge/focus-product%20engineering-111827)
![License](https://img.shields.io/badge/license-proprietary%20portfolio-7C3AED)

<br />

**English** · [Español](./README.es.md) · [Deutsch](./README.de.md)

</div>

---

> [!IMPORTANT]
> This reduced public repository does not contain the operational source code,
> scoring formulas or production integrations.
>
> EnergyScan does not issue an official Energy Performance Certificate or any
> document with administrative validity.

## At a glance

| User need | Product response |
|---|---|
| Fragmented property information | Structured residential wizard |
| Difficult-to-interpret results | Explainable score, confidence and gap |
| Complex renovation decisions | Comparable improvement scenarios |
| Heterogeneous documents | Controlled attachment workflow |
| Report monetisation | Premium report unlock |
| From assessment to action | Traceable provider handoff |

## Product context

Homeowners often know only part of the information relevant to energy
performance: insulation, windows, heating systems, consumption or existing
documentation.

Anclora EnergyScan was designed to transform that incomplete context into:

- an understandable orientation;
- confidence and missing-data signals;
- comparable improvement scenarios;
- indicative savings and priorities;
- a reviewable Premium report;
- a controlled handoff to qualified providers.

## Conceptual workflow

```text
Property information
        ↓
Validation and normalisation
        ↓
Category-based assessment
        ↓
Score + confidence + gap
        ↓
Improvement scenarios
        ↓
Orientative report
        ↓
Controlled provider handoff
```

## Complete-product capabilities

- guided intake for envelope, systems, renewables, climate and property type;
- category-based, traceable scoring;
- confidence levels and missing-data detection;
- improvement and indicative-savings scenarios;
- multilingual PDF reports in English, Spanish and German;
- Catastro lookup and parcel mapping;
- OCR and vision-assisted document analysis;
- authentication and user accounts;
- Stripe Checkout;
- provider, partner, lead and credit workflows;
- professional dashboards and metrics;
- controlled attachment storage;
- automated testing and production builds.

## Conceptual architecture

```text
Landing / Wizard
       ↓
Application services
       ↓
Assessment domain
       ↓
Scoring and scenarios
       ↓
Premium report / provider handoff
       ↓
Persistence and integrations
```

## Engineering decisions

### Explainable scoring

The result is presented through categories, confidence indicators and missing
evidence rather than as an unexplained number.

### Pre-assessment, not certification

Product language and workflow clearly separate automated orientation from
official energy certification.

### Idempotent monetisation

Premium access is designed around a traceable and repeat-safe payment flow.

### Controlled document processing

Documents are subject to file validation, storage limits and explicit OCR and
vision cost controls.

### Decoupled integrations

Catastro, storage, email, payments, analytics, maps and vision services remain
behind replaceable boundaries.

## Privacy and security

The complete product was designed around data minimisation, strict form and
file validation, authenticated ownership, role restrictions, secrets outside
source control, idempotent payment webhooks, controlled attachment storage and
synthetic demonstration data.

See [Security and privacy](./docs/SECURITY_AND_PRIVACY.md).

## Quality strategy

The private implementation included static analysis, TypeScript validation,
assessment-domain tests, API and persistence tests, authentication, payments,
reports, document processing, production builds and dependency auditing.

See [Quality strategy](./docs/QUALITY.md).

## Complete-product technology profile

| Area | Technologies |
|---|---|
| Frontend | Next.js, React, TypeScript and Tailwind CSS |
| Data | Prisma and PostgreSQL |
| Authentication | Auth.js / NextAuth |
| Forms | React Hook Form and Zod |
| Reports | React PDF |
| Payments | Stripe Checkout |
| Documents | PDF.js, OCR and vision |
| Maps | MapLibre |
| Storage | Vercel Blob |
| Email | Resend |
| Testing | Jest and Testing Library |

## Documentation

- [Case study](./docs/CASE_STUDY.md)
- [Architecture](./docs/ARCHITECTURE.md)
- [Security and privacy](./docs/SECURITY_AND_PRIVACY.md)
- [Quality strategy](./docs/QUALITY.md)
- [Portfolio notice](./NOTICE.md)

## Public scope

This repository demonstrates product definition, domain modelling, explainable
scoring, document generation, payments, integrations, privacy and full-stack
architecture.

It does not contain enough implementation detail to execute, reproduce or
deploy the operational product.

---

<div align="center">

### Antonio Ballesteros

Product-oriented developer focused on business automation, applied AI and
traceable digital systems.

[GitHub · ToniIAPro73](https://github.com/ToniIAPro73)

</div>
