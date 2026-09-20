# Sahiti

### A unified digital platform for schemes, finance, business support, and local economic resources.

**Sahiti V0.1** is the first development release of the new Sahiti platform, designed to bring government schemes, financial tools, business resources, and community-oriented services into a single digital experience.

> **Current release:** `v0.1`
> **Status:** Early development / prototype

---

## About

Accessing government schemes and financial support often involves navigating disconnected information, different application processes, and multiple sources of data.

Sahiti is being developed as a unified platform that brings these resources together through a single interface.

The project has evolved from an earlier government-site implementation into a broader platform focused on discoverability, accessibility, financial awareness, and digital assistance.

### Project evolution

```text
Government Site
      │
      │  Original / Legacy Implementation
      ▼
   Sahiti V0.1
      │
      ├── Scheme Discovery
      ├── Financial Tools
      ├── Business Resources
      ├── Community
      ├── Digital Assistance
      └── Location-based Services
```

The original government website is retained as the **legacy/reference implementation**. Sahiti V0.1 is the new platform built to expand upon that foundation.

---

## What Sahiti Provides

### Government Schemes

Discover relevant government schemes and access information about eligibility, benefits, and application processes through a centralized interface.

### Financial Tools

Sahiti V0.1 includes tools and interfaces for:

* Loan calculations
* Loan monitoring
* ROI analysis
* Market information
* Financial documents

### Business Support

The platform provides business-oriented functionality including shop/business information, business discovery, and supporting financial resources.

### Community

A community layer allows users to interact through feeds and discussions, creating a space for sharing information and experiences.

### Digital Assistant

Sahiti includes an assistant interface intended to help users navigate information and interact with the platform more naturally.

### Location & Risk Mapping

Location-aware functionality provides the foundation for geographically relevant information, mapping, and risk-related features.

---

## Core Features

| Area                      | V0.1 |
| ------------------------- | ---- |
| Scheme Discovery          | ✓    |
| Scheme Application Flow   | ✓    |
| Loan Calculator           | ✓    |
| Loan Monitoring           | ✓    |
| ROI Tools                 | ✓    |
| Market Information        | ✓    |
| Business / Shop Data      | ✓    |
| Community Feed            | ✓    |
| Discussions               | ✓    |
| Digital Assistant         | ✓    |
| Risk Mapping              | ✓    |
| Location Switching        | ✓    |
| User Accounts             | ✓    |
| User Profiles             | ✓    |
| Authentication            | ✓    |
| Database Integration      | ✓    |
| Multi-language Foundation | ✓    |

Some features in V0.1 are experimental and may require backend configuration or external services.

---

## Technology

Sahiti V0.1 is built around a modern web application architecture.

### Frontend

* TypeScript
* Component-based UI
* Responsive design
* Reusable interface components

### Backend & Data

* Supabase
* Database migrations
* Server-side API routes
* Authentication
* Session management
* Secure storage

### Application Structure

```text
src/
├── components/
├── data/
├── integrations/
├── lib/
└── routes/

drizzle/
└── database migrations

public/
└── static assets
```

---

## Getting Started

### Requirements

Before running Sahiti locally, make sure you have:

* Node.js
* npm
* A configured Supabase project
* Required environment variables

### Installation

Clone the repository:

```bash
git clone <repository-url>
cd sahiti
```

Install dependencies:

```bash
npm install
```

Create your local environment file:

```bash
cp .env.example .env
```

Configure the required environment variables.

Then start the development server:

```bash
npm run dev
```

The application should now be available through the local development server.

---

## Environment Variables

Create a `.env` file and configure the variables required by the application.

Typical configuration may include:

```env
SUPABASE_URL=
SUPABASE_ANON_KEY=
```

Do not commit credentials, API keys, service-role keys, or other secrets to the repository.

---

## Project Architecture

Sahiti is structured around separate application concerns to keep the platform extensible as new services are introduced.

```text
                    ┌──────────────────┐
                    │      Sahiti      │
                    │      V0.1        │
                    └────────┬─────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
        ▼                    ▼                    ▼
   User Layer          Service Layer         Data Layer
        │                    │                    │
   Authentication       Schemes              Supabase
   Profiles             Finance              Database
   Settings             Business             Storage
   Community             Assistant            Migrations
   Location              Mapping
```

This structure allows individual services to evolve without requiring the entire platform to be rebuilt.

---

## Development Status

Sahiti V0.1 is an early development release.

The current version establishes the application's core architecture and introduces the major platform modules. Several areas are expected to change as development continues.

Areas for future development include:

* Production deployment
* Expanded government-service integrations
* Improved scheme verification
* Advanced financial analytics
* Better accessibility
* Performance optimization
* Stronger security hardening
* Expanded multilingual support
* Improved data validation
* Additional APIs and integrations

---

## Versioning

Sahiti currently follows a simple development versioning system.

```text
v0.1
│
└── Initial Sahiti platform release
```

Future releases will increment the version as major functionality and architectural changes are introduced.

---

## Legacy Implementation

The original government-site implementation remains separate from Sahiti V0.1.

It serves as the historical/reference version of the project, while this repository represents the newer Sahiti platform.

This distinction is intentional:

```text
Legacy Government Site
        │
        │ Reference
        ▼
     Sahiti
      V0.1
        │
        ├── Expanded platform
        ├── New architecture
        └── Additional services
```

---

## Contributing

Contributions, suggestions, and technical feedback are welcome as the platform develops.

Before submitting major changes, consider opening an issue to discuss the proposed functionality or architectural change.

---

## License

Add the project's chosen license here before publishing the repository publicly.

For example:

```text
MIT License
```

if the project is intended to use the MIT License.

---

## Project

**Sahiti**
**Version:** `v0.1`
**Stage:** Early Development

A platform focused on making schemes, financial resources, business information, and digital services easier to discover and access through one unified interface.
