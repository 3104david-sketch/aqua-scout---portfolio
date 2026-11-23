# AquaScout | Map-Based Prospecting & Marketing Operations

## Overview
A local-first prospecting application built to help a residential sales team research property records, organize leads, and prioritize follow-ups.

## Features
- Interactive property map with Colorado public parcel data
- Address search and parcel inspection
- Local prospect list and pipeline status tracking
- Follow-up queue and Do Not Contact safeguards
- Fixture-based demo mode using fictional records
- Automated local database backup and integrity checks

## Technical stack
React, TypeScript, Vite, Leaflet, Fastify, Zod, SQLite, Vitest, Playwright

## Architecture
- Public parcel provider and geocoder → validated server APIs
- Fastify service → local SQLite prospect records and status
- React map UI → selection, prospect management, follow-up queue

## Relevance to AI marketing and operations
This project demonstrates lead research, audience segmentation infrastructure, pipeline organization, and operational safeguards. Any claimed 50% improvement in leads or appointments is not independently verified by this showcase.

## Project status and limitations
The source README reports that M2 prospecting readiness runs locally on a feature branch and has not been merged or deployed. No phone-number lookup or automated outbound messaging is claimed.

## Public demo and privacy
Fictional parcels and prospects only. No customer names, contact lists, access credentials, or property-owner records included.

This is a **new, documentation-only public portfolio showcase** based on a review of selected repository documentation and metadata. It does **not** include or publish the original private source repository, code, customer data, credentials, commit history, or deployable system. Screenshots and video demonstrations may be added only after confirming they contain synthetic or redacted information.

## Authorship and AI-assisted development
Product direction and project ownership: Benjamin Jackson. Development involved AI-assisted coding tools and iterative testing. Do not interpret this showcase as a claim that every line of implementation was personally hand-written.

## Next steps
- Record a short walkthrough with only fictional/test data.
- Add screenshots in `assets/` after visually checking for confidential information.
- Add a verified results section with the measurement period and baseline, where available.
