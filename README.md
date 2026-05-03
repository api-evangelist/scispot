# Scispot (scispot)

Scispot is a cloud-native laboratory data platform and operating system for modern life science labs. It provides an API-first architecture combining Electronic Lab Notebook (ELN) and Laboratory Information Management System (LIMS) capabilities with over 250 pre-built instrument connectors and 7,000+ application integrations via its GLUE layer. Labs use Scispot to centralize and activate their data, automate experiment workflows, manage samples, sequences, and chemical structures programmatically, and integrate with clinical data standards including HL7 FHIR, HL7 v2, and ASTM protocols.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/apis.yml)

## Tags

- Laboratory
- Life Science
- LIMS
- ELN
- Biotech
- API First
- Scientific Data
- Healthcare

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Scispot API

The Scispot REST API provides programmatic access to all laboratory data management features including Labsheets (LIMS), Electronic Lab Notebooks (ELN), Manifests (plates, boxes, racks), and Sequences. Authenticated via personal API tokens with RBAC scoping.

**Human URL:** [https://www.scispot.com/](https://www.scispot.com/)

**Base URL:** `https://api.scispot.com/v1`

#### Tags

- Laboratory
- LIMS
- ELN
- Life Science
- Biotech
- Samples
- Sequences

#### Properties

- [Documentation](https://docs.scispot.com/)
- [OpenAPI Specification](openapi/scispot-openapi.yml)
- [Developer Portal](https://www.scispot.com/compbio)
- [Spectral Rules](rules/scispot-rules.yml)
- [Naftiko Capabilities](capabilities/lab-data-management.yaml)
- [JSON Schema - Labsheet](json-schema/scispot-labsheet-schema.json)
- [JSON Schema - Sequence](json-schema/scispot-sequence-schema.json)
- [JSON-LD Context](json-ld/scispot-context.jsonld)
- [Vocabulary](vocabulary/scispot-vocabulary.yml)

## Common Properties

- [Website](https://www.scispot.com/)
- [Documentation](https://docs.scispot.com/)
- [Developer Portal](https://www.scispot.com/compbio)

## Artifacts

### OpenAPI Specifications

- [Scispot API](openapi/scispot-openapi.yml) — Full OpenAPI 3.1 spec covering Labsheets, ELN, Manifests, Sequences, and sample barcode search.

### Spectral Rules

- [Scispot API Rules](rules/scispot-rules.yml) — Spectral ruleset enforcing API key authentication, CRUD conventions, and Scispot naming standards.

### Capabilities

- [Lab Data Management](capabilities/lab-data-management.yaml) — Unified workflow capability for lab data management with REST and MCP adapters covering all Scispot resources.

#### Shared

- [Scispot API](capabilities/shared/scispot.yaml) — Per-API consumed definition for the Scispot Laboratory API.

### JSON Schema

- [Labsheet Schema](json-schema/scispot-labsheet-schema.json) — JSON Schema for Scispot Labsheet resources.
- [Sequence Schema](json-schema/scispot-sequence-schema.json) — JSON Schema for Scispot biological sequence resources.

### JSON Structure

- [Labsheet Structure](json-structure/scispot-labsheet-structure.json) — Structural documentation for Scispot Labsheet API resources.

### JSON-LD

- [Scispot Context](json-ld/scispot-context.jsonld) — Linked data context aligning Scispot vocabulary with schema.org and life science ontologies.

### Examples

- [List Labsheets Example](examples/scispot-list-labsheets-example.json) — Example request/response for GET /v1/labsheets.
- [Add Labsheet Row Example](examples/scispot-add-labsheet-row-example.json) — Example request/response for POST /v1/labsheets/{id}/rows.

### Vocabulary

- [Scispot Vocabulary](vocabulary/scispot-vocabulary.yml) — Domain vocabulary for lab data management, LIMS/ELN concepts, and life science terminology.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
