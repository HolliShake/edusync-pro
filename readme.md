# EduSync

**A proprietary higher-education administration and quality-improvement platform.**

[![Administrator guide](https://img.shields.io/badge/Documentation-Administrator%20guide-2563eb?style=for-the-badge)](https://hollishake.github.io/edusync-base/)

EduSync brings academic administration, admissions, enrollment, student services, and continuous quality improvement together in one platform for higher-education institutions.

> **Proprietary software.** EduSync is not open source. This page is a product overview; source code and implementation materials are not provided for public use. All rights are reserved by the applicable rights holder. No license to copy, modify, distribute, or create derivative works is granted.

## Product features

### Academic and institutional administration

- Manage agencies and campuses, colleges, departments, academic programs, buildings, rooms, and offices.
- Configure academic terms, subterms, cycles, fees, requirements, and account settings.
- Maintain courses, course catalogs, prerequisites, modules, sections, and schedules.
- Organize curriculum, program outcomes, capabilities, capability indicators, and skills frameworks.
- Configure EQA types and labels, agency goals, vision and mission information, and key performance indicators.

### Admissions and enrollment

- Support university and program admissions, applicant eligibility, invitations, and application requirements.
- Collect and review application submissions, supporting documents, and application history.
- Coordinate admission schedules and enrollment invitations.
- Validate enrollment and manage enrollment applications through to officially enrolled status.

### Teaching, assessment, and quality improvement

- Provide role-specific academic views for faculty, department chairs, college deans, program chairs, and registrars.
- Manage gradebook templates, grading periods, student grades, and course schedules.
- Build assessment tools, instruments, rating scales, and survey invitations.
- Collect survey responses and assessment results.
- Track CQI inputs, feedback, and issue reports to support continuous improvement.

### Student services and payments

- Publish office services and accept student service requests.
- Track request status and service processing through office queues and service windows.
- Manage service applications, fees, and payment status.
- Support online payments through Stripe and recorded cash payments.

### Administration and operations

- Manage users, accounts, designations, and role-based access controls.
- Provide role-aware dashboards and campus information views, including a campus map.
- Configure AI providers and monitor background jobs and server information.

Feature availability depends on an institution's configuration and the signed-in user's permissions.

## Technology

The application uses the following technologies. Badges link to their official project or documentation pages.

<p>
  <a href="https://dotnet.microsoft.com/"><img alt=".NET 10" src="https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white"></a>
  <a href="https://learn.microsoft.com/ef/core/"><img alt="Entity Framework Core 10" src="https://img.shields.io/badge/Entity%20Framework%20Core-10-512BD4?logo=dotnet&logoColor=white"></a>
  <a href="https://react.dev/"><img alt="React 19" src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black"></a>
  <a href="https://www.typescriptlang.org/"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-6-3178C6?logo=typescript&logoColor=white"></a>
  <a href="https://vite.dev/"><img alt="Vite 8" src="https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white"></a>
  <a href="https://tailwindcss.com/"><img alt="Tailwind CSS 4" src="https://img.shields.io/badge/Tailwind%20CSS-4-06B6D4?logo=tailwindcss&logoColor=white"></a>
  <a href="https://capacitorjs.com/"><img alt="Capacitor 8" src="https://img.shields.io/badge/Capacitor-8-119EFF?logo=capacitor&logoColor=white"></a>
  <a href="https://orval.dev/"><img alt="Orval" src="https://img.shields.io/badge/Orval-OpenAPI%20client-7C3AED"></a>
  <a href="https://www.microsoft.com/sql-server"><img alt="Microsoft SQL Server" src="https://img.shields.io/badge/SQL%20Server-Database-CC2927?logo=microsoftsqlserver&logoColor=white"></a>
</p>

- **Backend:** ASP.NET Core Web API on .NET 10, Entity Framework Core 10, and SQL Server.
- **Frontend:** React 19, TypeScript, Vite 8, and Tailwind CSS 4.
- **Mobile:** Capacitor 8 for Android and iOS app packaging.
- **API integration:** OpenAPI-based client generation with Orval.
- **Additional services:** ASP.NET Core Identity and JWT authentication, Hangfire background jobs, and Stripe payments.

## Documentation

See the [EduSync Administrator guide](https://hollishake.github.io/edusync-base/) for product and administration documentation.

## Proprietary notice

EduSync and its associated software, product design, and materials are proprietary. No part may be copied, redistributed, reverse engineered, or used to create derivative works without prior written permission from the rights holder, except where applicable law expressly permits it.
