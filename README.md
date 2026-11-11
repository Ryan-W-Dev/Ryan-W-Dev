<h1 align="center">Ryan Wynn</h1>

<p align="center">
  <strong>Full-Stack Software Engineer · AI/ML Engineer</strong><br>
  React · Next.js · TypeScript · Node.js · PostgreSQL · Supabase · Python
</p>

<p align="center">
  Relocating to the United States · Authorized to work in the U.S. without sponsorship<br>
  Open to full-time roles, contract work and project collaborations
</p>

<p align="center">
  <a href="https://ryanwynn.dev/"><img src="https://img.shields.io/badge/Portfolio-ryanwynn.dev-0F172A?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/ryan-wynn-dev"><img src="https://img.shields.io/badge/LinkedIn-ryan--wynn--dev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://reasonandrender.com/"><img src="https://img.shields.io/badge/Reason_%26_Render-Studio-E21E26?style=for-the-badge" alt="Reason &amp; Render"></a>
  <a href="mailto:ryan.james.wynn@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-0F172A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

I build web applications, client dashboards and internal tools that support real business workflows, from responsive interfaces to server-side logic, authentication, databases, integrations and AI-powered features. **7 client sites delivered**, plus production tools in daily use.

Before software I worked in operations, growth and client delivery, including founding a services business and growing it to AED 1.2M in revenue. That background shapes how I build: I start from the workflow someone actually needs, and I treat permissions, validation, error handling and accessibility as part of the feature rather than an afterthought.

I use AI-assisted development every day, and I back it with code review, automated tests and manual verification before anything ships.

## Selected work

All projects below are solo builds.

| Project | What it does | Built with | Status |
| :--- | :--- | :--- | :--- |
| **[Snapback](#snapback)** | Receipt capture and expense claims with AI field extraction | React, TanStack Start, Supabase, Azure AI | [Live](https://usesnapback.app/) |
| **[Returns dashboard](#client-returns-and-approval-dashboard)** | Returns tracking and manufacturer approvals for a client | Next.js, Supabase, PostgreSQL | Private client app |
| **[Reason & Render](#reason--render)** | Business website and customer support portal | Next.js, NextAuth, HubSpot | [Live](https://reasonandrender.com/) |
| **[PartsRelay](#partsrelay)** | React frontend for an automotive parts search platform | React, TanStack Router, OpenAPI | Private |
| **[Portfolio](#portfolio)** | Portfolio and CV site with accessibility testing | Next.js, Motion, Playwright | [Live](https://ryanwynn.dev/) |

### Snapback

Receipt and reimbursement app for capturing documents, reviewing expenses and preparing claims. **Processes ~250 receipts a month for 15 users.**

**Role:** Solo developer · **Status:** Live · [usesnapback.app](https://usesnapback.app/)

- Extracts receipt fields and line items with Azure AI Document Intelligence, flagging uncertain values for human review.
- Exports claims to CSV and into company Excel templates while preserving their formulas and formatting.
- Supabase Auth, PostgreSQL and private file storage, with automated tests covering parsing, PDF handling and exports.

<details>
<summary>More detail</summary>

- Photo and PDF uploads, document previews, and parsing for supported flight tickets.
- Expense folders, submission tracking and currency conversion.
- Postmark authentication emails; deployed through GitHub and Vercel.

</details>

`React` `TypeScript` `TanStack Start` `Supabase` `Azure AI Document Intelligence` `PDF.js` `ExcelJS` `Vercel`

### Client returns and approval dashboard

Private client application managing product returns from intake and inspection through manufacturer review, shipment and closure. **Used daily by a 6-person team.**

**Role:** Solo developer · **Status:** Private client application (client identity withheld)

- Manufacturer approval and rejection workflows, staff and reviewer roles, multi-factor authentication and full audit history.
- Authenticated server endpoints, database access rules and private document storage.
- Automated application, database and authentication tests; deployed with GitHub Actions and Vercel.

<details>
<summary>More detail</summary>

- Central dashboard with searchable records, filters and return-status tracking.
- Shipment statuses, dates and tracking references.
- Excel and CSV exports for reporting.

</details>

`Next.js` `React` `TypeScript` `Supabase` `PostgreSQL` `ExcelJS` `GitHub Actions` `Vercel`

### Reason & Render

Business website and customer support portal for my studio.

**Role:** Solo developer · **Status:** Live · [reasonandrender.com](https://reasonandrender.com/)

- Support portal with Google and Microsoft sign-in, HubSpot ticketing and file attachments.
- Validated server-side inquiry forms that send leads to HubSpot with source-page attribution and duplicate protection.
- Migrated the site from Umbraco to repository-managed content and media, deployed on Vercel.

<details>
<summary>More detail</summary>

- Responsive service and industry pages built from reusable components.
- Playwright browser checks for navigation, forms and key interactions.

</details>

`Next.js` `React` `TypeScript` `Tailwind CSS` `HubSpot` `NextAuth` `Playwright` `Vercel`

### PartsRelay

React frontend for an existing automotive parts backend, built from the product design for workshop staff and service advisers.

**Role:** Solo frontend developer · **Status:** Private

- Search creation, history and result details, with complete loading and error states.
- Contacts, team management, workspace settings and role-aware access.
- English and Italian interfaces, typed OpenAPI integration, and automated checks for sessions, permissions, forms and responsive layouts.

`React` `TypeScript` `TanStack Router` `TanStack Query` `Tailwind CSS` `OpenAPI` `Bun` `Vite`

### Portfolio

My portfolio and CV website.

**Role:** Solo developer · **Status:** Live · [ryanwynn.dev](https://ryanwynn.dev/)

- Responsive layouts, a downloadable CV, and Motion interactions with reduced-motion support.
- Keyboard navigation, visible focus states and structured data, verified with Playwright and BrowserStack.

`Next.js` `React` `TypeScript` `Tailwind CSS` `Motion` `Playwright` `Vercel`

## Currently building

- **Windows quoting and document tool:** desktop app in Tauri, Rust, React and TypeScript with Word and PDF templates, quote calculations, saved drafts, document versioning and PDF/DOCX export.
- **Learning:** completed the Zero To Mastery Complete Python Developer certificate (July 2026). Now going deeper on machine learning, backend engineering, testing, SQL, and data structures and algorithms.
- **Coursework:** [Web development](https://github.com/Ryan-W-Dev/Complete_Web_Developer) · [Python](https://github.com/Ryan-W-Dev/ztm-python-course)

## Tech stack

| Area | Tools |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, Python, SQL, HTML, CSS |
| **Frontend** | React, Next.js, TanStack Start, TanStack Router, TanStack Query, Tailwind CSS, shadcn/ui, Motion |
| **Backend and data** | Node.js, REST APIs, OpenAPI, PostgreSQL, Supabase |
| **AI and integrations** | Azure AI Document Intelligence, LLM integrations, HubSpot, Postmark, PDF.js, ExcelJS |
| **Auth and security** | Supabase Auth, NextAuth, OAuth, role-based access, multi-factor authentication |
| **Testing** | Playwright, Vitest, BrowserStack, accessibility checks, database integration tests |
| **Delivery** | Git, GitHub Actions, Docker Compose, Vite, Bun, Vercel |
| **Also used** | Tauri, Rust, Astro, Umbraco |

## Experience

| Role | Organization | Dates |
| :--- | :--- | :--- |
| **Full-Stack Software Engineer** | Self-employed | Sep 2025 to present |
| **Head of Growth and Partnership** | Quantum Media ME, Dubai | Apr 2026 to present |
| **Founder** | Smooth Sailing | Nov 2021 to Aug 2025 |
| **Project Specialist** | Aspen Medical | Nov 2020 to Aug 2021 |

- **Quantum Media ME:** signed 18 partnerships and built the team's internal tooling, including an operations dashboard, CRM integration with partner and campaign data, automated reporting scripts, and AI tooling used by the content team.
- **Smooth Sailing:** founded and ran a maritime services company, growing it to 8 retained clients and AED 1.2M in revenue; scoped client requirements and coordinated technical partners.
- **Aspen Medical:** coordinated healthcare project deployments, timelines, documentation and stakeholder communication.

## Get in touch

I'm open to full-stack and AI/ML engineering roles, contract projects and collaborations.

[LinkedIn](https://www.linkedin.com/in/ryan-wynn-dev) · [Email](mailto:ryan.james.wynn@gmail.com) · [Portfolio](https://ryanwynn.dev/) · [Start a project](https://reasonandrender.com/contact/)
