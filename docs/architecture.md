# Architecture Proposal (Not Yet Implemented)

Candidate stack: Next.js, TypeScript, Tailwind CSS, Sanity CMS, PostgreSQL/PostGIS, Mapbox, HubSpot and GA4. Final choice depends on existing infrastructure and operating systems.

## Data domains
- Venue: location, category, visibility settings, partner status.
- Screen: venue, size, orientation, operating hours and specifications.
- Product/package: approved offer and pricing rules.
- Campaign enquiry: objectives, geography, budget, dates, shortlist and consent.
- Editorial: pages, case studies, FAQs, insights and media assets.

## Security and privacy
Do not expose private venue coordinates or confidential commercial data. Validate forms server-side, use least-privilege access and store secrets outside Git.

## Deployment
Preview builds for pull requests; protected production deployment from approved `main` changes. Production configuration is pending.
