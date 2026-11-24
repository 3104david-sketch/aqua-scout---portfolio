# AquaScout | Map-Based Prospect Research & Marketing Operations

> **Portfolio case study · Documentation-only · Original source remains private**

A local-first application for exploring property records, organizing residential prospects, and managing follow-up. Built with AI-assisted development workflows.

## The problem
Residential prospecting can involve fragmented property research, inconsistent lead records, and missed follow-ups.

## My contribution
Product concept, workflow design, business use case, and iterative AI-assisted application development. I used AI coding assistance alongside practical testing and product decisions; I do not claim to have manually written every line of the private implementation.

## How it works
1. Explore a neighborhood on a map using public parcel and geocoder data.
2. Inspect parcel records, data provenance, and unit information.
3. Save selected properties to a local prospect list.
4. Organize statuses and follow-up dates; honor Do Not Contact flags.

## Architecture and technical approach
Public parcel data and geocoding are accessed through server-side providers. A React/Leaflet UI presents records; Fastify and SQLite handle local records. TypeScript schema validation and automated checks support development.

**Technologies:** React · TypeScript · Vite · Leaflet · Fastify · Zod · SQLite · Vitest · Playwright.

## Why it matters to AI marketing
A prospecting workflow designed to support audience research, lead organization, and follow-up operations; no quantified outcome is demonstrated by this repository.

## Project status and limitations
**Status:** Working local prototype documented in private source; feature branch M2 not merged or deployed in the source README.

- No implemented phone lookup.
- No automated outbound marketing or messaging.
- No externally verified lead or appointment performance attributable to this project.

## Explore the project without screenshots
Read [WORKFLOW.md](WORKFLOW.md) for a step-by-step, text-only case study and [PROJECT_FACTS.json](PROJECT_FACTS.json) for structured project metadata. No screenshots, recordings, customer data, or deployable application code are included in this portfolio repository.

## Privacy and scope
This showcase was written independently from the original private repository. It shares high-level architecture and documented functionality only. It does **not** contain original production source, API keys, customer lists, call transcripts, internal pricing, environment files, or original Git history. See [SECURITY.md](SECURITY.md).

## Contact and project ownership
**Benjamin Jackson** — [GitHub profile](https://github.com/3104david-sketch) · AI marketing automation, applied AI systems, and growth operations.
