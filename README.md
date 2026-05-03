# StackHawk

StackHawk is an application and API security testing platform that helps engineering teams find, triage, and fix security vulnerabilities in their APIs and web applications. It provides Dynamic Application Security Testing (DAST) with deep OpenAPI spec integration, CI/CD pipeline automation, AI-powered OpenAPI spec generation, and an AppSec Intelligence platform for program-level visibility across the software development lifecycle.

**Website:** [https://www.stackhawk.com/](https://www.stackhawk.com/)
**Documentation:** [https://docs.stackhawk.com/](https://docs.stackhawk.com/)
**API Docs:** [https://apidocs.stackhawk.com/docs](https://apidocs.stackhawk.com/docs)

## Tags

- API Security, Application Security, DAST, Security Testing, Vulnerability Management

## APIs

### StackHawk API
Programmatic management of applications, environments, scan configurations, results, findings, repositories, teams, policies, and security reports.

- **Base URL:** `https://api.stackhawk.com`
- **Authentication:** Bearer JWT (obtained via `/api/v1/auth/login` with API key)
- **OpenAPI Spec:** [https://download.stackhawk.com/openapi/stackhawk-openapi.json](https://download.stackhawk.com/openapi/stackhawk-openapi.json)

## OpenAPI Specifications

| Spec | Path |
|---|---|
| StackHawk API | [openapi/stackhawk-openapi.yml](openapi/stackhawk-openapi.yml) |

## Spectral Rules

| Ruleset | Path |
|---|---|
| StackHawk API Rules | [rules/stackhawk-rules.yml](rules/stackhawk-rules.yml) |

## Naftiko Capabilities

### Shared Definitions

| API | Path |
|---|---|
| StackHawk API | [capabilities/shared/stackhawk-api.yaml](capabilities/shared/stackhawk-api.yaml) |

### Workflow Capabilities

| Workflow | Description | Path |
|---|---|---|
| API Security Testing | End-to-end DAST scan management, findings triage, and policy enforcement | [capabilities/api-security-testing.yaml](capabilities/api-security-testing.yaml) |

## JSON Schema

| Schema | Path |
|---|---|
| Scan | [json-schema/stackhawk-scan-schema.json](json-schema/stackhawk-scan-schema.json) |
| Security Finding | [json-schema/stackhawk-finding-schema.json](json-schema/stackhawk-finding-schema.json) |

## JSON Structure

| Structure | Path |
|---|---|
| Scan | [json-structure/stackhawk-scan-structure.json](json-structure/stackhawk-scan-structure.json) |

## JSON-LD

| Context | Path |
|---|---|
| StackHawk Context | [json-ld/stackhawk-context.jsonld](json-ld/stackhawk-context.jsonld) |

## Examples

| Example | Path |
|---|---|
| List Findings | [examples/stackhawk-list-findings-example.json](examples/stackhawk-list-findings-example.json) |

## Vocabulary

| Vocabulary | Path |
|---|---|
| StackHawk Vocabulary | [vocabulary/stackhawk-vocabulary.yml](vocabulary/stackhawk-vocabulary.yml) |

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-02
