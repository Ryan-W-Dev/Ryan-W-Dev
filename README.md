<h1 align="center">Hi, I'm Ryan Wynn 👋</h1>

<p align="center">
  <strong>Full-Stack Software Developer</strong><br>
  React · TypeScript · Next.js · PostgreSQL
</p>

<p align="center">
  Relocating to the United States · Authorized to work in the U.S. without sponsorship
</p>

<p align="center">
  <a href="https://ryanwynn.dev/"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://reasonandrender.com/"><img src="https://img.shields.io/badge/Reason_%26_Render-E21E26?style=for-the-badge" alt="Reason &amp; Render"></a>
  <a href="https://www.linkedin.com/in/ryan-wynn-dev"><img src="https://img.shields.io/badge/LinkedIn-0F172A?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:ryan.james.wynn@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge" alt="Email Ryan"></a>
</p>

---

I build web applications, client dashboards, and tools for everyday business workflows, covering interfaces, server-side logic, authentication, databases, and integrations. I care about how software behaves when someone actually uses it, including the permissions, failed requests, and awkward cases around the main feature.

## Selected work

All projects below are solo builds.

| Project | What it does | Built with | Status |
| :--- | :--- | :--- | :--- |
| **Snapback** | Receipt capture and expense claims with AI field extraction | React, TanStack Start, Supabase, Azure AI | [Live](https://usesnapback.app/) |
| **Returns dashboard** | Returns tracking and manufacturer approvals for a client | Next.js, Supabase, GitHub Actions | Private client app |
| **Reason & Render** | Business website and customer support portal | Next.js, NextAuth, HubSpot, Playwright | [Live](https://reasonandrender.com/) |
| **PartsRelay** | React frontend for an automotive parts search platform | React, TanStack Router, TanStack Query, OpenAPI | Private |
| **Portfolio** | Portfolio and CV site with accessibility testing | Next.js, Motion, Playwright | [Live](https://ryanwynn.dev/) |

### Snapback

A receipt and reimbursement app for capturing documents, reviewing expenses, and preparing claims.

**Role:** Solo developer · **Status:** Live · [usesnapback.app](https://usesnapback.app/)

<!-- <img src="assets/snapback.png" alt="Snapback receipt review screen" width="720"> -->

- Extracts receipt fields and line items with Azure AI Document Intelligence, flagging uncertain values for review.
- Exports claims to CSV and to company Excel templates while keeping their formulas and formatting.
- Supabase authentication, PostgreSQL, and private file storage, with automated tests for parsing, PDF handling, and exports.

<details>
<summary>More detail</summary>

- Photo and PDF receipt uploads, document previews, and parsing for supported flight tickets.
- Expense folders, submission tracking, and currency conversion.
- Postmark authentication emails and deployment through GitHub and Vercel.

</details>

`React` `TypeScript` `TanStack Start` `Supabase` `Azure AI Document Intelligence` `PDF.js` `ExcelJS` `Vercel`

### Client returns and approval dashboard

A private client application for managing product returns from intake and inspection through manufacturer review, shipment, and closure.

**Role:** Solo developer · **Status:** Private client application (client identity withheld)

- Manufacturer approval and rejection workflows, staff and reviewer permissions, multi-factor authentication, and audit history.
- Authenticated server endpoints, database access rules, and private document storage.
- Automated application, database, and authentication tests, deployed with GitHub Actions and Vercel.

<details>
<summary>More detail</summary>

- A central dashboard with searchable records, filters, and return-status tracking.
- Shipment statuses, dates, and tracking references.
- Excel and CSV exports.

</details>

`Next.js` `React` `TypeScript` `Supabase` `PostgreSQL` `ExcelJS` `GitHub Actions` `Vercel`

### Reason & Render

A business website and customer support portal.

**Role:** Solo developer · **Status:** Live · [reasonandrender.com](https://reasonandrender.com/)

<!-- <img src="assets/reason-and-render.png" alt="Reason & Render website" width="720"> -->

- Support portal with Google and Microsoft sign-in, HubSpot tickets, and attachments.
- Validated server-side inquiry forms that send leads to HubSpot with source-page attribution and duplicate protection.
- Migrated the site from Umbraco to repository-managed content and media, deployed on Vercel.

<details>
<summary>More detail</summary>

- Responsive service and industry pages built from reusable components.
- Playwright browser checks for navigation, forms, and key interactions.

</details>

`Next.js` `React` `TypeScript` `Tailwind CSS` `HubSpot` `NextAuth` `Playwright` `Vercel`

### PartsRelay

A React frontend for an existing automotive parts backend, built from the product design for workshop staff and service advisers.

**Role:** Solo frontend developer · **Status:** Private

<!-- <img src="assets/partsrelay.png" alt="PartsRelay parts search screen" width="720"> -->

- Search creation, history, and result details, with loading and error states.
- Contacts, team management, workspace settings, and role-aware access.
- English and Italian interfaces, typed API integration, and automated checks for sessions, permissions, forms, and responsive layouts.

`React` `TypeScript` `TanStack Router` `TanStack Query` `Tailwind CSS` `OpenAPI` `Bun` `Vite`

### Personal portfolio

My portfolio and CV website.

**Role:** Solo developer · **Status:** Live · [ryanwynn.dev](https://ryanwynn.dev/)

- Responsive layouts, a downloadable CV, and Motion interactions with reduced-motion support.
- Keyboard navigation, visible focus states, structured data, and accessibility and browser testing with Playwright and BrowserStack.

`Next.js` `React` `TypeScript` `Tailwind CSS` `Motion` `Playwright` `Vercel`

## Currently building and learning

- **Windows quoting and document tool:** a Tauri, Rust, React, and TypeScript desktop app with Word and PDF templates, quote calculations, saved drafts, document versions, and PDF/DOCX exports. Local development build.
- **Study:** completed the Zero To Mastery Complete Python Developer certificate in July 2026. Now focused on TypeScript, testing, data structures and algorithms, SQL, and backend development.
- **Coursework:** [Web development](https://github.com/Ryan-W-Dev/Complete_Web_Developer) · [Python](https://github.com/Ryan-W-Dev/ztm-python-course)

## Skills

- **Languages:** TypeScript, JavaScript, Python, SQL, HTML, CSS
- **Frontend:** React, Next.js, TanStack Start, Tailwind CSS, shadcn/ui, Motion
- **Backend and data:** Node.js, REST APIs, PostgreSQL, Supabase
- **Authentication:** Supabase Auth, NextAuth, OAuth, role-based access, multi-factor authentication
- **Integrations:** Azure AI Document Intelligence, HubSpot, Postmark, PDF.js, ExcelJS
- **Testing:** Playwright, Vitest, BrowserStack, accessibility checks, database integration tests
- **Delivery:** Git, GitHub Actions, Vite, Bun, Docker Compose, Vercel
- **Also used:** Tauri, Rust, Astro, Umbraco

## Background

I came to software from operations, growth, and client delivery, so I start with the workflow someone needs. I check AI-assisted code with code review, automated tests, and manual testing.

- **Head of Growth & Partnerships, Quantum Media ME:** client and partner relationships, delivery briefs, and coordination across teams.
- **Founder, Smooth Sailing:** ran a maritime services business, scoped client requirements, and coordinated technical partners.
- **Project Specialist, Aspen Medical:** coordinated healthcare project deployments, timelines, and documentation.

## Get in touch

I'm open to full-stack software development roles, contract work, and project collaborations.

[LinkedIn](https://www.linkedin.com/in/ryan-wynn-dev) · [Email](mailto:ryan.james.wynn@gmail.com) · [Portfolio](https://ryanwynn.dev/)
